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

<h2> In the News </h2>

- Ruth and Paul Fye Award for Excellence in Oceanographic Research Best Paper Award, MIT-WHOI Joint Program, June 2020 <&nbsp;<a href="https://mit.whoi.edu/research/awards/ruth-and-paul-fye-award/">link</a>&nbsp;>

- "How Stevens Researchers are Creating Better Maps for Robots, Self-Driving Cars," <i>Stevens University News</i>, June 2019. <&nbsp;<a href="https://www.stevens.edu/news/how-stevens-researchers-are-creating-better-maps-robots-self-driving-cars">link</a>&nbsp;>

- "Coding Curiosity," <i>MIT Graduate Program in Science Writing</i>, May 2018. <&nbsp;<a href="https://youtu.be/gMP_DvTO4wY">link</a>&nbsp;>

- "Robot Explorers," <i>WHOI Multimedia</i>, March 2018. <&nbsp;<a href="https://www.whoi.edu/multimedia/robot-explorers/">link</a>&nbsp;>

- "Engineering New Solutions," <i>Stevens University News</i>, March 2017. <&nbsp;<a href="https://www.stevens.edu/news/engineering-new-solutions">link</a>&nbsp;>

- "Robust Robotics for a Safer World," <i>Stevens University News</i>, March 2017. <&nbsp;<a href="https://www.stevens.edu/news/robust-robotics-safer-world">link</a>&nbsp;>

