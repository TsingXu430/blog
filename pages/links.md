---
layout: default
title: 友情链接
css: [blog.css,links.css]
js: [common.js,header.js,totop.js]
---

<ul>
	{% for link in site.data.links %}
	<li>
		<p><a href="{{ link.url }}" title="{{ link.title }}" target="_blank">{{ link.content }}</a></p>
		<p>{{ link.desc }}</p>
	</li>
	{% endfor %}
</ul>

<!--
<div id="links">
	<ul>
		{% for link in site.data.links %}
			<li>
				<a href="{{ link.url }}" title="{{ link.url }}" target="_blank">{{ link.name }}</a>
				<span>&nbsp;{{ link.description }}</span>
			</li>
		{% endfor %}
	</ul>
</div>-->
