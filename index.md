---
layout: default
title: Home
---

# Benvenuto nel mio blog

Qui pubblico articoli e note su sviluppo, progetti personali e idee.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) <small>({{ post.date | date: "%d/%m/%Y" }})</small>
{% endfor %}
