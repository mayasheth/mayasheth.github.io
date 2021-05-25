---
layout: default
title: recently
---


# {{ page.title }}
## (musings, updates, and other such words)

<ul class="posts">
	
	{% for post in site.categories.review %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
