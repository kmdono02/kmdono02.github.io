---
title: "Publications"
layout: archive
permalink: /pubs/
---

{% for y in page.years %}
  <h3  id="{{y}}" class="pubyear">{{y}}</h3>
{% bibliography -f CV -q @*[year={{y}}]* %}
{% endfor %}
