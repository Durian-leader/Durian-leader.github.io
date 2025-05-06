---
layout: page
title: 学术
permalink: /academic/
---

这里是学术分类的介绍...

<ul>
  {% for post in site.categories.学术 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%Y-%m-%d" }}</span>
    </li>
  {% endfor %}
</ul>