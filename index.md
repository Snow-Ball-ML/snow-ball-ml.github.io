---
layout: home
title: "Snow-Ball-ML Blog"
author_profile: true   # 右侧显示个人信息
---


<h1>{{ page.title }}</h1>

<p>This is my ML notes Github Blogs</p>

<h2>Index</h2>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span>（{{ post.date | date: "%Y-%m-%d" }}）</span>
    </li>
  {% endfor %}
</ul>
