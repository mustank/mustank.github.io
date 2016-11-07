---
layout: page
title: Mustang
---
<ul>
{% for item in site.data.mustang %}
  <li>
  {{ item.name}} (<em>{{item.rok_rozpoczecia_produkcji}}-{{item.rok_zakonczenia_produkcji}}</em>)
  </li>
{% endfor %}
</ul>
