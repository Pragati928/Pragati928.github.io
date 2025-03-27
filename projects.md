---
layout: single
title: "🚀 Featured Projects"
permalink: /projects/
---

<div class="project-container">
  {% for project in site.data.projects %}
  <div class="project-card">
    <img src="{{ project.image }}" alt="{{ project.title }}">
    <h3>{{ project.title }}</h3>
    <p><strong>Tech Used:</strong> {{ project.tech }}</p>
    <p>{{ project.description }}</p>
    <a href="{{ project.link }}" target="_blank">View Project</a>
  </div>
  {% endfor %}
</div>
