---
layout: default
title: "Rehberler"
permalink: /rehberler/
---

# Rehberler

Aşağıda yaptığım rehberler listelenmektedir:

<ul>
{% for post in site.categories.Rehberler %}
  <li><a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%d %B %Y" }}</li>
{% endfor %}
</ul>
