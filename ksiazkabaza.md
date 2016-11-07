---
layout: page
title: Ksiazki
---
<ul>
{% for item in site.data.ksiazki %}
<li style="{% if item.przeczytane%}color: red {%endif %}">
{{ item.name }} (<em>{{item.seria}}</em>) {{item.nr_tom}}
</li>
{% endfor %}
</ul>
