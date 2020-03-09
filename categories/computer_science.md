---
title: Computer Science
permalink: "/projects/categories/computer_science"
layout: page
---

<h5> Posts by Category : {{ page.title }} </h5>

<div class="card">
  {% for post in site.categories.computer_science %}
    <li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</div>
