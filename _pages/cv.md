---
layout: archive
title: "Resume"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download PDF](/files/resume.pdf)

## Education
- Ph.D in Engineering Sciences: Electrical Engineering, ESAT, KU Leuven, 2024
- Master of Artificial Intelligence, Computer Science, KU Leuven, 2019
- M.S. in Advanced Management (Option Finance), Solvay Brussels School of Economics and Management, 2015
- B.S. in Business Engineering, Solvay Brussels School of Economics and Management, ULB, 2013

## Work experience
- 2019-2024: PhD Researcher
  - KU Leuven
  - Duties includes: Academic research from ideation and experimentation to publication, participating in research projects with the industry sector, teaching, coaching students
  - Supervisors: Hugo Van hamme and Marie-Francine Moens

- 2018: Intership as Machine Learning Researcher
  - Euranova
  - Duties included: Semi-supervised learning for Computer Vision with Generative Adversarial Networks

- 2016-2017: Business Consultant
  - DFakto
  - Duties included: Support for Project Management Office in a large financial institution.

- 2015-2016: Business Developer
  - Partena Ziekenfonds
  - Duties included: Development and implementation of IT solutions for healthcare

## Skills
- Artificial Intelligence: Design, training and evaluation of Deep Neural Networks
  - Transformers: Pretraining, finetuning and adapting Transformer models
  - Low Resource Training: Methods to learn from few data
  - Multitask and Multilingual Learning: Create multitask and multilingual models
  - Spoken Language Understanding: Teach a computer to understand speech
  - Natural Language Processing: Language modeling 
- Computer Skills:
  - Python
    - Deep Learning: Huggingface, PyTorch, Tensorflow, Fairseq
    - Data Science: scikit-learn, numpy, pandas, opencv
    - Visualization: matplotlib, seaborn, dash, plotly
    - Web Development: Flask, Django
  - System Administration: Linux, Docker, Podman
  - Office: Microsoft Office

## Publications
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Talks
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
## Teaching
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
