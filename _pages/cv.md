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
* Ph.D in Computational Physical Chemistry, Technical University Darmstadt, Germany, 2021 - 2025 (expected)
* M.Sc. in Chemistry, Indian Institute of Technology Kanpur, India, 2017 - 2019
* B.Sc. in Chemistry, Ramakrishna Mission Vidyamandira, India, 2014 - 2017

Work experience
======
* Oct, 2021 - Dec, 2024: Scientific Research Assistant
  * Technical University of Darmstadt, Germany

* Nov, 2019 - Oct 2020: Research Assistant
  * Ruhr University Bochum, Germany
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
