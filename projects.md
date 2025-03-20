---
layout: default
title: "Projects"
---

<h1>{{ page.title }}</h1>
<div class="projects-list">
  {% for project in site.projects %}
    <div class="project-item">
      <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
      <p>{{ project.description }}</p>
      <img src="{{ project.image }}" alt="{{ project.title }} thumbnail">
    </div>
  {% endfor %}
</div>
