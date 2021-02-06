---
layout: page
permalink: /research/
title: research
description:
years: [2018, 2017, 2016, 2015, 2014, 2013, 2012, 2009, 2007]
nav: true
---

My research interests are on systems, from hardware to software, but always
close to the former.  Within this broad area, computer architecture, memory hierarchy,
and heterogeneous systems are the topics where I have worked the most.

### publications

These are some of my publications in reversed chronological order. For the full
list please find me at [google
scholar](https://scholar.google.es/citations?user=GMN3oxEAAAAJ&hl=en&oi=ao) and
[DBLP](http://dblp.uni-trier.de/pers/hd/g/Gracia:Dar=iacute=o_Su=aacute=rez)

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

### intelectual property

While working at industry, we filled some patents. For a detailed list
please visit [WIPO](https://patentscope.wipo.int/search/en/search.jsf) or [google patents](https://patents.google.com/?inventor=dario+suarez+gracia).
