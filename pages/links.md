---
layout: default
title: 友情链接
css: [blog.css,links.css]
js: [common.js,blog.js]
---

<ul>
	{% for link in site.data.links %}
	<li>
		<span>{{ link.desc }}</span>
		<a href="{{ link.url }}" title="{{ link.title }}" target="_blank">{{ link.content }}</a>
	</li>
	{% endfor %}
</ul>
