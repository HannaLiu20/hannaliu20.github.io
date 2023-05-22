---
layout: archive
title: "Talks"
permalink: /talks/
author_profile: true
---

ISMRM Presentations
----
* ISMRM 2020: 
  **Hongyan Liu**, Oscar van der Heide, Cornelis A.T. van den Berg, and Alessandro Sbrizzi. Accelerated MR-STAT Algorithm: Achieving 10-minute High-Resolution Reconstructions on a Desktop PC.
  * Digital poster (Abstract 3477)

* ISMRM 2021:

* ISMRM 2022:

* ISMRM 2023:


 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}