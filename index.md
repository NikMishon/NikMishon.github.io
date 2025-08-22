---
layout: page
title: Главная
permalink: /
---

# Адреса

Добро пожаловать в документацию по адресным системам.

## Последние посты

{% raw %}{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%d.%m.%Y" }}
{% endfor %}{% endraw %}

## О проекте

Этот сайт содержит документацию и материалы по различным адресным системам, используемым в современном мире.

## Быстрые ссылки

- [Все посты](/posts/)
- [О проекте](/about/)
- [GitHub репозиторий](https://github.com/NikMishon/repository)
