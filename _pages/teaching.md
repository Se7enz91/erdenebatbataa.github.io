---
layout: page
permalink: /teaching/
title: teaching
description: Эконометрикийн хичээлүүд
nav: true
nav_order: 6
---

<div class="courses">
  {% for course in site.courses %}
  <div class="card mt-3">
    <div class="p-3">
      <h5 class="card-title">
        <a href="{{ course.url | relative_url }}">{{ course.title }}</a>
      </h5>
      <p class="card-text">{{ course.description }}</p>
    </div>
  </div>
  {% endfor %}
</div>
