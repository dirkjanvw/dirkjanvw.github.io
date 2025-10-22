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
* PhD in Bioinformatics, Wageningen University, 2020-2025
* MSc in Plant Biotechnology, Wageningen University, 2018-2020
* BSc in Plant Sciences, Wageningen University, 2015-2018

Experience
======
* 2020-2025: PhD Bioinformatics
  * Wageningen University
  * Promotor: Dick de Ridder
  * Co-promotors: Eric Schranz & Sandra Smit
  * Daily supervisor: Sandra Smit
* 2018-2020: MSc Internship
  * GeneTwister
  * Supervisor: Peter van Dam
  
Skills (not limited to the below)
======
* Programming
  * Bash
  * Java
  * Snakemake
  * Python
  * R
* Research
  * Genomics
  * Pangenomics
  * Comparative genomics
  * Transcriptomics

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Software
======
  <ul>{% for post in site.software %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
