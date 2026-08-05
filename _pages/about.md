---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About Me

* I am an Assistant Professor at the [Technion](https://www.technion.ac.il), in the Faculties of [Electrical and Computer Engineering](https://ece.technion.ac.il) and of [Computer Science](https://www.cs.technion.ac.il). I'm also a TCE Faculty Recruitment Fellow.
* I'm boardly interested in program analysis, systems, and security. My current research thrusts are automatic software reverse-engineering and securing agentic systems.
* I was a PostDoc at [Columbia University](https://www.columbia.edu), were I worked with [Junfeng Yang](http://www.cs.columbia.edu/~junfeng/).
* I earned my PhD from the [Technion](https://www.technion.ac.il), advised by [Eran Yahav](https://www.cs.technion.ac.il/~yahave/).

{% include recruiting-notice.html %}

# Publications

{% assign publications = site.publications | sort: "display_order" %}
{% for publication in publications %}
  {% include publication-entry.html publication=publication %}
{% endfor %}
