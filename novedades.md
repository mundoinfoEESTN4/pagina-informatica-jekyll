---
layout: default
title: "Novedades"
---

<h2>Últimas Novedades</h2>

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    — <small>{{ post.date | date: "%d/%m/%Y" }}</small>
  </li>
  {% endfor %}
</ul>

<p><a href="/feed.xml" target="_blank">📡 Ver Feed RSS</a></p>
