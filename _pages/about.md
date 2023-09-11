---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a third-year CS Ph.D. student advised by Prof.Yi Yang in ReLER, Zhejiang University. My research interests include virtual human generation and 3D vision.

<br />

Publications
=======
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br />
