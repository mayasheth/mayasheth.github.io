---
layout: default
title: what i'm reading
---
# {{ page.title }}
## (and/or listening to, watching, discussing, etc.)

_For complete reading pipeline, check out my [Goodreads](https://www.goodreads.com/user/show/31600461-maya-sheth)._

<iframe src="https://sulfuric-kumquat-542.notion.site/ebd/20f4e31537538068bc0cd3b879dca3e3" width="100%" height="600" frameborder="0" allowfullscreen></iframe>

 
<ul class="posts">
	
	{% for post in site.categories.reading %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
