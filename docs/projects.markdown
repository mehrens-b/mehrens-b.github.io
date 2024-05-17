---
layout: page
title: Projects
permalink: /projects/
---

Here you can find projects that I have worked on for vairous professional and personal interests.

Check them out here:

{% for course in site.courses %}
  <h2>
    <a href="{{ course.url }}">
      {{ course.name }} - {{ course.code }}
    </a>
  </h2>
  <p>{{ course.content | markdownify }}</p>
{% endfor %}