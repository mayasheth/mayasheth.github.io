---
layout: default
title: what i'm reading
---
# {{ page.title }}
## (and/or listening to, watching, discussing, etc.)

<iframe src="https://sulfuric-kumquat-542.notion.site/ebd/88ee1ff2388a42238e7c1033c8ab6385?v=1994e315375380378786000c1b53bfda" width="100%" height="600" frameborder="0" allowfullscreen </iframe>


_For complete reading pipeline, check out my [Goodreads](https://www.goodreads.com/user/show/31600461-maya-sheth)._

<ul class="posts">
	
	{% for post in site.categories.reading %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
