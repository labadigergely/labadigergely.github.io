---
layout: page
title: Olvasó kabinét
---

> Az Olvasó Kabinét 18–19. századi, nehezen hozzáférhető kiadványokat tesz elérhetővé, illetve máshol digitalizált anyagok elérhetőségét tartalmazza. A [Címkék](/pages/cimkek/) oldalon címszó szerint kereshet.


> A kiadványok utolsó elérését a posztok dátuma jelzi. A tulajdonosok-szolgáltatók a kiadványokkal kapcsolatos jogaikat fenntartják maguknak.

{% capture posts %}
  {% for post in site.categories.lesebibliothek %}
    |{{ post.title }}#{{ post.url }}
  {% endfor %}
{% endcapture %}
{% assign sortedposts = posts | split: '|' | sort %}
{% for post in sortedposts %}
    {% assign postitems = post | split: '#' %}
<div>{% if postitems[1] %}    <a href={{ postitems[1] }}">{{ postitems[0] }}</a><br> {% endif %}</div>
{% endfor %}
