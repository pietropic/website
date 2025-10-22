---
layout: archive
title: "CV"
permalink: /cv-json/
author_profile: false
redirect_from:
  - /resume-json
---

{% include base_path %}


Education
======
* Ph.D in Mathematics, Sorbonne Université, 2025 
* M.S. in Mathematics, Sorbonne Université, 2021
* B.S. in Mathematics, University of São Paulo, 2020

Work experience
======
* Ongoing: Postdoc 
  * University of Gothenburg
  * Supervisor: David Witt Nyström


* Fall 2025: Short postdoc visit
  * Erdos center


  

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
  
Service 
======
* 2021: Organizer of the [A5 Group](https://www.ime.usp.br/~acinco/en.html)
  * A student runned academic group
  * Over [25 weekly seminars](https://www.ime.usp.br/~acinco/past-seminars.html) organized
  * IME - University of São Paulo

* 2019: Deputy Student Representative in the Mathematics Department Council
  * IME - University of São Paulo

* 2018: Deputy Student Representative in the Mathematics Department Council
  * IME - University of São Paulo

Languages
======
* Portuguese: native speaker
* Italian: native speaker
* English: fluent
* Spanish: fluent
* French: fluent
* Catalan: intermediate
* Swedish: hopefully in two years :)


{% include cv-template.html %}

<div class="cv-download-links">
  <a href="{{ base_path }}/files/cv.pdf" class="btn btn--primary">Download CV as PDF</a>
  <a href="{{ base_path }}" class="btn btn--inverse">View Markdown CV</a>
</div>
