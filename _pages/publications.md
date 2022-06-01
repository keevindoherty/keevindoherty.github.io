---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015]
preprint-years: [2022]
thesis-years: [2019, 2017]
nav: true
---
Publications by categories in reverse chronological order. See [Google Scholar](https://scholar.google.com/citations?user=IYPhbO0AAAAJ) for an up-to-date list.
<!-- _pages/publications.md -->
<div class="publications">

<h2> Theses </h2>

{%- for y in page.thesis-years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f theses -q @*[year={{y}}]* %}
{% endfor %}

<hr>

<h2> Preprints </h2>

{%- for y in page.preprint-years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f preprints -q @*[year={{y}}]* %}
{% endfor %}

<hr>

<h2> Refereed Conference and Journal Publications </h2>

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
