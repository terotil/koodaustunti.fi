---
layout: kaksi-palstaa
title: Blogi
permalink: /blogi/
jarjestys: 10

---

## Blogiartikkelit

<ul>
	{% for artikkeli in site.posts %}
		<li>{{ artikkeli.date | date:"%d.%m.%Y" }}: <a href="{{ artikkeli.url }}">{{ artikkeli.title }}</a></li>
	{% endfor %}
</ul>