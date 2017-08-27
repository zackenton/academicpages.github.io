---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD in Physics, Queen Mary University of London, 2017
* MA (Cantab) MMath, Mathematics, University of Cambridge, Distinction, 2013

Work experience
======
* Data Scientist, ASI Data Science, Jan 2017 - August 2017
  * Built a recommendation system for a major supermarket
  * Predictive modelling for a political campaign
  * Improved donor engagement for a breast cancer charity
  * Built educational tools for machine learning on a Raspberry Pi

* QMUL: Teaching Assistant, 2013 - 2016
  * Statistical Physics
  * Quantum Mechanics
  * General Relativity


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
