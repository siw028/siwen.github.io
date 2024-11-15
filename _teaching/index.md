---
title: "Teaching"
layout: default
---

# Teaching

<ul>
  {% for item in site.teaching %}
    <li>
      <a href="{{ item.url }}">{{ item.title }}</a><br>
      {{ item.type }}, {{ item.venue }}, {{ item.date | date: "%Y" }}
    </li>
  {% endfor %}
</ul>
