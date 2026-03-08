---
layout: page
title: "Teaching"
permalink: /teaching/
---

<ul class="teaching-list">
{% for course in site.data.teaching %}
  <li class="teaching-item">
    <p class="teaching-course">{{ course.course }}</p>
    <p class="teaching-role">{{ course.role }} &mdash; {{ course.institution }}, {{ course.years }}</p>
    {% if course.description %}
    <p class="teaching-details">{{ course.description }}</p>
    {% endif %}
  </li>
{% endfor %}
</ul>
