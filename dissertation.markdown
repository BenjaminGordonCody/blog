---
layout: page
permalink: /categories/
title: Dissertation
---

{% for post in site.categories.Dissertation %}

My final piece of work for my MSc in Computer Science with Big Data Analytics. A
study into user attitudes towards the use of Mastodon data in Big Data research.

 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
