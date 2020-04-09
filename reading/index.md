---
layout: default
title: what i'm reading
---
# {{ page.title }}
## (and/or listening to, watching, discussing, etc.)

/For complete reading pipeline, check out my [Goodreads](https://www.goodreads.com/user/show/31600461-maya-sheth)./

<ul class="posts">
	
	{% for post in site.categories.reading %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
