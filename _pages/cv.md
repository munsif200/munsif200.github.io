---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* **Ph.D in Computer Science** (In Progress)
  * Sejong University, Seoul, South Korea
  * Expected: 2024
  * Focus: Computer Vision, Deep Learning, Materials Informatics

## Work Experience

* **Researcher** (September 2021 - Present)
  * Intelligent Media Laboratory, Sejong University
  * Seoul, South Korea
  * Supervisor: [Supervisor Name]
  * Research areas: Computer Vision, Deep Learning, VR/AR, Materials Informatics

## Skills

### Programming Languages
* Python
* MATLAB
* C++

### AI/ML Frameworks
* TensorFlow
* PyTorch
* Keras
* OpenCV

### Development Tools
* Git/GitHub
* Jupyter Notebook
* Unity (VR/AR Development)
* Docker

## Publications

### Journal Articles
  <ul>{% for post in site.publications %}
    {% if post.venue contains 'Journal' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>

### Conference Papers
  <ul>{% for post in site.publications %}
    {% if post.venue contains 'Conference' %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>

## Talks
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

## Teaching
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Research Projects
  <ul>{% for post in site.portfolio %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Awards and Honors
* [Add your awards and honors here]
* [Second award]
* [Third achievement]

## Professional Memberships
* [Professional organization memberships]
* [Academic societies]

## Languages
* English (Fluent)
* [Other languages as applicable]

## References
Available upon request.