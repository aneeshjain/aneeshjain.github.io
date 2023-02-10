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
<h3>Thapar Institute of Engineering & Technology</h3>

* B.E. in Computer Engineering, *Jul 2015 - Jun 2019*
  * ***GPA 8.24/10.0***

<h3>Virginia Tech</h3>

* M.S. in Computer Science (*Thesis Track*), *Jan 2021 - Dec 2022*
  * *Master’s Thesis in Deep Learning for Code Generation and AI assisted Software Development*
  * *Advisor: [Dr. Chandan K. Reddy](https://people.cs.vt.edu/reddy/)*
  * ***GPA 4.0/4.0***
  * *[Graduate Certificate in Data Analytics](https://www.michaelsutter.com/ediploma?fn=diplomastatuscheck&key=02000000ffd21ae1c9aa397065f48993e175be119b2c8558268e0c474a8dcb2e815e8797d2d83a7a62300a5890b6aa379f2cfe444fa8e5417935b361b5669a92c903290d)*

Work experience
======
<h3>Cadence Solutions</h3>

  **ML Engineering Intern, May 2022 - Present**

  *Automated evaluation of clinical reports for hypertensive patients using Neural Question Answering*
  * Utilized technologies like **NLP**, **(Named Entity Recigniton)NER**, **OCR**, **Redis**, **Python** and **AWS**, to design, develop, and deploy an advanced **ML** solution for medical report parsing.
  * Significantly improved operational efficiency, saving an estimated **50 work hours** per week of clinician time since reports were originally manually perused.
  * Increased patient enrollment by **100%** by virtue of processing a higher volume of documents and more accurate patient identification.

<h3>Virginia Tech</h3>

  **Research Assistant, Aug 2021 - Dec 2022**
  * Released a **novel, large, parallel** programming language dataset to foster Deep Learning research in **code search, translation, summarization and synthesis**; presented benchmarks for all tasks([GitHub](https://github.com/reddy-lab-code-research/XLCoST), [HuggingFace](https://huggingface.co/datasets/codeparrot/xlcost-text-to-code)).
  * Developed a **Reinforcement Learning(RL)** algorithm and reward function in **PyTorch**, that uses code compilation signal, syntax trees and data flow graphs as feedback to improve **code translation** quality.
  * Achieved a **6.5%** improvement in the compilation rate of generated translations using the RL algorithm.
  * Developed an **evaluation** framework for code translation quality using **Python** which **automated compilation, test
  generation and execution**.

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
  

