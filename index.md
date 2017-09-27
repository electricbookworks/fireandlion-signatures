---
---

# {{ site.title }}

<ul>
{% for person in site.data.team %}
	<li><a href="{{ person.file }}.html">{{ person.name }}</a></li>
{% endfor %}
</ul>
