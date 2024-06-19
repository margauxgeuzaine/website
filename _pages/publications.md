---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
years_papers: [2018, 2019, 2020, 2021, 2022, 2023, 2024]
nav_order: 2
---
## Journal articles
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years_papers %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
