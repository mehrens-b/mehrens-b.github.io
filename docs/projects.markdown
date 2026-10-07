---
layout: page
title: Projects
permalink: /projects/
---

Here you can find projects that I have worked on for vairous professional and personal interests.

{% for project in site.projects %}
  <h2>
    <a href="{{ project.url }}">
      {{ project.name }}
    </a>
  </h2>
  <p>{{ project.content | markdownify }}</p>
{% endfor %}
