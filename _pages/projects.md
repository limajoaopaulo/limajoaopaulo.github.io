---
title:
layout: default
permalink: /projects/
published: true
---


<div class="ProjectContainer">

	<div class="gallery">


  {% for project in site.projects %}

  {% if project.redirect %}
  <div class="projectTile">
          <a href="{{ project.redirect }}" target="_blank">
          <span>
              <h2>{{ project.title }}</h2>
              <br/>
              <p>{{ project.description }}</p>
          </span>
          </a>
  </div>


  

{% else %}

  {% if project.image %}

    <div class="projectTile">
            <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
            <span>
                <h2>{{ project.title }}</h2>
                <br/>
                <p>{{ project.description }}</p>
            </span>
            <img class="gallery-image"  src= "{{ project.image }}">
            </a>
    </div>

    {% else %}
    <div class="projectTile">
            <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
            <span>
                <h2>{{ project.title }}</h2>
                <br/>
                <p>{{ project.description }}</p>
            </span>
            </a>
    </div>
 {% endif %}
  {% endif %}

  {% endfor %}

	</div>

</div>
