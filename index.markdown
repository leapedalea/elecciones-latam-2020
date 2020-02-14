---
layout: home
---
<ul>
{% for election in site.elections %}
  <li>{{ election.country }} - {{ election.subject }} ({{ election.election-date | date: "%d %b"}})
    <a href="{{ election.url }}">Ver más</a>
  </li>
{% endfor %}
</ul>