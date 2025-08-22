---
layout: page
title: Все посты
permalink: /posts/
---

# Все посты

Здесь собраны все материалы по адресным системам:

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})

**Дата:** {{ post.date | date: "%d.%m.%Y" }}  
**Автор:** {{ post.author }}

{% if post.categories %}
**Категории:** {{ post.categories | join: ", " }}
{% endif %}

{% if post.tags %}
**Теги:** {{ post.tags | join: ", " }}
{% endif %}

{{ post.excerpt | default: post.content | strip_html | truncatewords: 30 }}

---

{% endfor %}
