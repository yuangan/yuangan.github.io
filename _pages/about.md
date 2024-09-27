---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a final-year Ph.D. student advised by Prof.Yi Yang in ReLER, Zhejiang University. My research interests include virtual human generation and privacy protection. I am looking for a post-doctor position. If you are interested in me, please contact: ganyuan@zju.edu.cn

<br />

Publications
=======
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br />
