---
layout: default
title: {{ Accessible Research }}
---

<div id="home">
  <h1>Blog Posts</h1>
  <ul class="about">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>
