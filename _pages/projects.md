---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

Currently working on a Full-Stack Web Application to handle the requirements of the postal office in IIT Hyderabad.

My other recent Projects are listed below:





{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
