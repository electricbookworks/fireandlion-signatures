---
title: Fire and Lion email signatures
---

# {{ site.title }}

<ul>
{% for person in site.data.team %}
	<li><a href="{{ person.file }}.html">{{ person.name }}</a></li>
{% endfor %}
</ul>

To get your signature, select your name. Then Ctrl+A/Cmd+A to select all, and copy-paste the signature into your email program's signature field or into individual messages.

Email programs will display signatures differently. The hope is that your signature should never look awful. If you do find an awful rendering in an email program, please take a screenshot and log an issue [here](https://github.com/fireandlion/signatures/issues) with details of the email program and device it was on.

Change the signature itself by contributing to the repo [here](https://github.com/fireandlion/signatures).
