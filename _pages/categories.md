---
layout: page
title: Categories
permalink: /categories/
---

{% for category in site.categories %}
### {{ category[0] }}
<ul>
  {% for post in category[1] %}
  <li><a href="{{ https://omnifyi.github.io/side%20hustle/passive%20income/2026/01/01/earning-online-with-serpclix.html }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
{% endfor %}
