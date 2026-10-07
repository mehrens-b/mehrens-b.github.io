---
layout: page
title: Courses
permalink: /courses/
---

Here you can find formation on courses I teach.

Check them out here:

{% for course in site.courses %}
  <h2>
    <a href="{{ course.url }}">
      {{ course.name }} - {{ course.code }}
    </a>
  </h2>
  <p>{{ course.content | markdownify }}</p>
{% endfor %}
