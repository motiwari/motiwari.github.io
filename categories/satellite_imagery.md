---
title: Satellite Imagery
permalink: "/projects/categories/satellite_imagery"
layout: page
---

<h5> Posts by Category : {{ page.title }} </h5>

<div class="card">
  {% for post in site.categories.satellite_imagery %}
    <li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</div>
