---
title: Artificial Intelligence and Machine Learning
permalink: "/projects/categories/ai_and_ml"
layout: page
---

<h5> Posts by Category : {{ page.title }} </h5>

<div class="card">
  {% for post in site.categories.AI %}
    <li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</div>
