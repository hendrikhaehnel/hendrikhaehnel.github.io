---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Academic Education
======
* Currently a Postdoc at Goethe University Frankfurt, since 2017
* Ph.D in Accelerator Physics, Goethe University Frankfurt, 2017
* MSc Physics, Philipps-University Marburg, 2011
* BSc Physics, Philipps-University Marburg, 2011

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
