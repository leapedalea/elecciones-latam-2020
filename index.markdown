---
layout: home
---
<ul>
{% for election in site.elections %}
  <li><a href="{{ election.url }}">{{ election.country }} - {{ election.subject }}</a></li>
{% endfor %}
</ul>