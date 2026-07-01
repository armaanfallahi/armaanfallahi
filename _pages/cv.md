---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- Optional: link a PDF version once you add it to /files/
[Download CV (PDF)]({{ site.baseurl }}/files/CV.pdf)
-->

Education
======
* MD–PhD, University of Toronto & Hospital for Sick Children (in progress)
  <!-- Add: PhD field/department, expected year, supervisor -->
<!-- Add prior degrees, e.g.:
* B.Sc. in ____, University of ____, 20__ -->

Research experience
======
<!-- Add positions, e.g.:
* 20XX–present: Graduate Researcher
  * Hospital for Sick Children / University of Toronto
  * Focus: early-life stress, amygdala engrams, interneuron circuits
  * Supervisor: ____ -->

Skills
======
<!-- Add skills, e.g.:
* Computational modelling (Python)
* Electrophysiology / imaging techniques -->

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

Awards and honours
======
<!-- Add awards, e.g. CIHR studentship, scholarships -->

Service and leadership
======
<!-- Add, e.g.:
* Co-led equity and inclusivity events at Massey College
* Student leadership, University of Toronto Medical Society -->
