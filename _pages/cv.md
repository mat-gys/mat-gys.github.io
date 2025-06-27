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
* M.S. in Economics, Universidad de San Andrés, 2022
* B.S. in Economics, Universidad de San Andrés, 2021

Work experience
======
* October 2023-June 2025: Data Analyst
  * Move37
  * Duties included: Building predictive models for horse racing.

* February 2023-February 2024: Research Assistant
  * Harvard Business School
  * Supervisor: Professor Alberto Cavallo
    
* September 2022-October 2023: Research Assistant
  * EBRD
  * Supervisor: Professor Cevat Giray Aksoy
    
* July 2022-October 2024: Research Assistant
  * Universidad de San Andrés
  * Supervisor: Professor Walter Sosa Escudero
    
* March 2020-February 2022: Research Assistant
  * Universidad de San Andrés
  * Supervisor: Professor Tommy Murphy

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
