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
* B.S. in Mathematics, University of Antwerp, 2019
* M.S. in Fundamental Mathematics, University of Antwerp, 2021
* Ph.D in Computer Science, Delft University of Technology, 2026 (expected)

Research activities
======
* (PC membership) [7th International Conference on Applied Category Theory](https://oxford24.github.io/act_cfp.html)

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
  
