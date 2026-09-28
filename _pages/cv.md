---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

## Research Profile

Ph.D. student in Electrical and Computer Engineering at the **University of Iowa** working on machine learning for biomedical and healthcare data, with interests in generative modeling, biomedical NLP, clinical risk prediction, incomplete multimodal data, and structured biomedical knowledge.

## Education

**University of Iowa** — Ph.D. in Electrical and Computer Engineering, 2023–Present  
**Tribhuvan University, Institute of Engineering** — M.Sc. in Information and Communication Engineering, 2012–2014  
**Kantipur Engineering College, Tribhuvan University** — B.E. in Electronics and Communication Engineering, 2007–2011

## Experience

**Graduate Research Assistant**, University of Iowa, 2023–Present  
**Senior Telecom Engineer**, Nepal Telecom, 2017–2023  
**Engineer**, Nepal Television, 2014–2017  
**Lecturer**, Kantipur Engineering College, 2012–2014

## Teaching

- ECE 5450: Machine Learning — Teaching Assistant, Fall 2024 and Fall 2025
- ECE 5995: Large Language Models — Teaching Assistant, Spring 2025
- Kantipur Engineering College — Microprocessor, Instrumentation II, Data Communication

## Awards

- NSF Travel Grant for presenting work at WSDM 2026
- Gold Medal from the President of Nepal for academic excellence in the M.Sc. program
- Semester scholarship for seven consecutive semesters during the bachelor's degree

## Skills

Python · C · C++ · MATLAB · Linux

## Publications

<ul>{% assign sorted_pubs = site.publications | sort: "date" | reverse %}
{% for post in sorted_pubs %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
