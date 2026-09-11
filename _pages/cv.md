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
* Combined Master's–Doctoral Student, Seoul National University, September 2026–present
  * Advisor: Prof. Minhao Cui
  * Laboratory: Meta Perception Lab
* B.S. in Computer Science and Technology, Southeast University, 2026

Work experience
======
* Research Assistant, HKUST UbiquitousX Lab
  * Completed internship focused on contactless vital-sign monitoring and edge deployment of remote photoplethysmogram networks.
* Research Assistant, Southeast University AI-native IoT Lab
  * Conducted multi-sensor fusion research using mmWave radar and infrared systems for human parsing.
* Vehicle Control Algorithm Engineer, Southeast University Formula Racing Team
  * Designed four-wheel independent steering systems and real-time telemetry monitoring solutions.
  
Skills
======
* Programming: Python, C++, Java, MATLAB, JavaScript, Verilog
* Frameworks and tools: PyTorch, TensorFlow, ROS, Docker, Git, Linux
* Research interests: Intelligent IoT, Edge Computing, Autonomous Systems, Human-Centered AI

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
