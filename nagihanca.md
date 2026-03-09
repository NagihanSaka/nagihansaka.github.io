---
layout: default
title: Nagihanca
---

<h2>Nagihan'ca</h2>

<ul>
{% for item in site.nagihanca %}
  <li>
    <a href="{{ item.url }}">{{ item.title }}</a>
  </li>
{% endfor %}
</ul>
