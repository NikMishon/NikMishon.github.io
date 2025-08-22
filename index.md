---
layout: page
title: Главная
permalink: /
---

## Последние посты

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%d.%m.%Y" }}
{% endfor %}

## Быстрые ссылки

- [Все посты](/posts/)
- [GitHub репозиторий](https://github.com/NikMishon/NikMishon.github.io)
