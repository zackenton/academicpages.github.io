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
* Postdoctoral Researcher, Computer Science Department, University of Oxford, Sep 2018 -
  * Lead on AI Safety projects in Prof Yarin Gal's machine learning group.

* Research Assistant, Future of Humanity Institute, University of Oxford, Feb 2018 -
  * Author on [Predicting Human Deliberative Judgments with Machine Learning](https://zackenton.github.io/files/predicting_judgments_final.pdf), in collaboration with Ought.
  * Project lead on meta-learning project for safe exploration.

* Visiting Researcher, Montreal Institute for Learning Algorithms (MILA), University of Montreal, Sept 2017 -
  * Joint lead author on [Three Factors Influencing Minima in SGD](https://arxiv.org/abs/1711.04623), with Jastrzebski, Arpit, Ballas, Fischer, Bengio and Storkey
  * Second author on [DNNs Sharpest Directions Along the SGD Trajectory](https://arxiv.org/abs/1807.05031), with Jastrzebski, Ballas, Fischer, Bengio and Storkey
  * Gave MILA Seminar on Three Factors Influencing Minima in SGD



* Data Scientist, ASI Data Science, Jan 2017 - August 2017
  * Built a recommendation system for a major supermarket
  * Predictive modelling for a political campaign
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
