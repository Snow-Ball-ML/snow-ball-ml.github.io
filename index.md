---
layout: default
title: Snow-Ball-ML Blog
---

<h1>{{ page.title }}</h1>

<p>Welcome to my Blogs</p>

<h2>Articals</h2>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span>（{{ post.date | date: "%Y-%m-%d" }}）</span>
    </li>
  {% endfor %}
</ul>
