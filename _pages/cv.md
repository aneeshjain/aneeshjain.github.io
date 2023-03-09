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
<h2>Thapar Institute of Engineering & Technology</h2>

* B.E. in Computer Engineering, *Jul 2015 - Jun 2019*
  * ***GPA 8.24/10.0***

<h2>Virginia Tech</h2>

* M.S. in Computer Science (*Thesis Track*), *Jan 2021 - Dec 2022*
  * *Master’s Thesis in Deep Learning for Code Generation and AI assisted Software Development*
  * *Advisor: [Dr. Chandan K. Reddy](https://people.cs.vt.edu/reddy/)*
  * ***GPA 4.0/4.0***
  * *[Graduate Certificate in Data Analytics](https://www.michaelsutter.com/ediploma?fn=diplomastatuscheck&key=02000000ffd21ae1c9aa397065f48993e175be119b2c8558268e0c474a8dcb2e815e8797d2d83a7a62300a5890b6aa379f2cfe444fa8e5417935b361b5669a92c903290d)*

Work experience
======
<h2>Cadence Solutions</h2>

  <h3>Data Analytics & ML Engineering Intern</h3>
  
  *May 2022 - Present*
  
  *Automated data extraction from patients’ clinical reports, saving 50 work hours/week for clinicians*
  * Engineered the service to convert pdfs into plain text(OCR), redact protected health information(Named Entity Recognition) and extract data from unstructured text using Transformer based Neural Question Answering..
  * Significantly improved operational efficiency, saving an estimated **50 work hours** per week of clinician time since reports were originally manually perused.
  * Accelerated run-time by implementing asynchronous batch processing, created session management cache using Redis, used S3 as intermediate data stores and surfaced final results to Snowflake.

<h2>Virginia Tech</h2>

  <h3>Research Assistant</h3>

  *Aug 2021 - Dec 2022*
  
  *A multi-lingual dataset to benchmark Generative AI for Code*
  * Curated 1 M data points in 7 programming languages and their natural language descriptions to support code translation, natural language to code generation, code summarization and natural language to code search([GitHub](https://github.com/reddy-lab-code-research/XLCoST), [HuggingFace](https://huggingface.co/datasets/codeparrot/xlcost-text-to-code)).
  * Benchmarked the performance of current state of the art Transformer models like T5 and BERT on all supported tasks within our novel, large and multilingual dataset.
  
  *Execution-based Code Generation using Deep Reinforcement Learning*
  * Developed evaluation framework for code translation quality to evaluate code compilability and executability.
  * Conceptualized Reinforcement Learning(RL) algorithm in PyTorch, leveraging code compilation signal, syntax trees and data flow graphs as feedback; outperformed benchmark models by 13.4% in code translation.

<h2>Unilever</h2>

  <h3>Project Lead</h3>

  *Jul 2019 - Jun 2020*
  * Led a team of 3 software developers to build ETL data pipelines enabling automated processing of financial documents (vendor invoices, shipment logs, tax documents, etc.) saving ∼ $1 M annually.
  * Coordinated end-to-end project management – planning and leading sprints, identifying and removing bottlenecks, negotiating costs and balancing resource allocation.

  <h3>Software Development Intern</h3>

  *Aug 2018 - Dec 2018*
  * Developed an end-to-end ETL pipeline for automated attendance verification using Microsoft Face API and deployed it to AWS Lambda which reduced verification time by 75% and cost by ∼ $50 K annually.

Skills
======
* **Languages & Tools:** Python, C++, SQL, PyTorch, Git, OpenCV, Pandas, AWS
* **Courses:** Data Structures & Algorithms, Advanced ML, Deep Learning, NLP, Data Analytics, Computer Vision, DBMS


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

