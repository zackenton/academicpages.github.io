---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


Work experience
======
* Visiting Researcher, Montreal Institute for Learning Algorithms (MILA), University of Montreal, Sept 2017 - Dec 2017
  * Joint lead author on [Three Factors Influencing Minima in SGD](https://arxiv.org/abs/1711.04623), with Jastrzebski, Arpit, Ballas, Fischer, Bengio and Storkey
  * Gave MILA Seminar on Three Factors Influencing Minima in SGD
  * Began project on evolutionary exploration in SGD with David Krueger
  * Reading groups on theoretical deep learning, reinforcement learning, adversarial learning
  * AI Safety lunch discussions

* Data Scientist, ASI Data Science, Jan 2017 - August 2017
  * Built a recommendation system for a major supermarket
  * Predictive modelling for a political campaign
  * Improved donor engagement for a breast cancer charity
  * Built educational tools for machine learning on a Raspberry Pi

* QMUL: Teaching Assistant, 2013 - 2016
  * Statistical Physics
  * Quantum Mechanics
  * General Relativity

Education
======
* PhD in Physics, Queen Mary University of London, 2017
* MA (Cantab) MMath, Mathematics, University of Cambridge, Distinction, 2013


Publications
======
  <ul>{% for post in site.publications reversed %}
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
