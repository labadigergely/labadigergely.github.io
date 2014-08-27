---
layout: page
title: Kurzusok
---

> Az aktuális félév [oktatási naptára](https://www.google.com/calendar/embed?src=lrqh2drcev41fevg3htl7argfk%40group.calendar.google.com&ctz=Europe/Budapest).

{% capture posts %}
  {% for post in site.categories.kurzusok_2014_osz %}
    |{{ post.title }}#{{ post.url }}
  {% endfor %}
{% endcapture %}
{% assign sortedposts = posts | split: '|' | sort %}
{% for post in sortedposts %}
    {% assign postitems = post | split: '#' %}
<div>{% if postitems[1] %}    <a href={{ postitems[1] }}">{{ postitems[0] }}</a><br> {% endif %}</div>
{% endfor %}
