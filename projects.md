---
layout: page
title: "🚀 Featured Projects"
permalink: /projects/
---

<div class="projects-container">
  {% for project in site.data.projects %}
  <div class="project-card">
    <img src="{{ project.image }}" alt="{{ project.title }}" class="project-image">
    <h3>{{ project.title }}</h3>
    <p><strong>Tech Used:</strong> {{ project.tech }}</p>
    <p>{{ project.description }}</p>
    <a href="{{ project.link }}" class="btn">View Project</a>
  </div>
  {% endfor %}
</div>
