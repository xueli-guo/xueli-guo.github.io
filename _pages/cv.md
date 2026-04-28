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
* Ph.D. Candidate, LIESMARS, Wuhan University

Research interests
======
* Event-based and LiDAR SLAM
* LEO satellite navigation enhancement
* Multi-sensor fusion

Research experience
======
* Developed bionic navigation algorithms using event cameras for high-dynamic and variable-lighting scenarios.
* Integrated event cameras and LiDAR for improved accuracy and robustness in autonomous mapping.
* Participated in national and provincial research projects, including multi-sensor data fusion work.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
