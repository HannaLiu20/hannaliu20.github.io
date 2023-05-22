---
layout: archive
title: "Talks"
permalink: /talks/
author_profile: true
---

ISMRM Presentations
----

* ISMRM 2023:

  **Hongyan Liu**, Oscar van der Heide, Edwin Versteeg, Miha Fuderer, Fei Xu, Martijn Froeling, Cornelis A.T. van den Berg, and Alessandro Sbrizzi. High-resolution three-dimensional MR-STAT for musculoskeletal applications.
  * Oral presentation (Abstract 0672)

* ISMRM 2022:

  **Hongyan Liu**, Oscar van der Heide, Miha Fuderer, Cornelis A.T. van den Berg, and Alessandro Sbrizzi. 3D MR-STAT: towards a fast multi-parametric protocol with increased SNR. 
  * Digital poster (Abstract 1348)

  **Hongyan Liu**, Tom Bruijnen, Maaike van Haandel, Oscar van der Heide, Miha Fuderer, Cornelis A.T. van den Berg, and Alessandro Sbrizzi. Increasing the T2 sensitivity of MR-STAT sequences by small quadratic RF phase increments.
  * Oral presentation (Abstract 0625)
  * Magna Cum Laude Merit Award

* ISMRM 2021:

  **Hongyan Liu**, Oscar van der Heide, Cornelis A.T. van den Berg, and Alessandro Sbrizzi.Fast and Accurate Modeling of Transient-state Sequences by Recurrent Neural Networks.
  * Oral presentation (Abstract 0329)
  * Magna Cum Laude Merit Award

* ISMRM 2020: 

  **Hongyan Liu**, Oscar van der Heide, Cornelis A.T. van den Berg, and Alessandro Sbrizzi. Accelerated MR-STAT Algorithm: Achieving 10-minute High-Resolution Reconstructions on a Desktop PC.
  * Digital poster (Abstract 3477)









 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}