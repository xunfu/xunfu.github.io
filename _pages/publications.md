---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

I am a Ph.D. Candidate in Robotics at the [University of Michigan](https://umich.edu/), co-advised by Prof. Ram Vasudevan and Prof. Talia Moore. I am a member of Robotics and Optimization for Analysis of Human Motion [(ROAHM)](http://www.roahmlab.com/) Lab and Evolution and Motion of Biology and Robotics [(EMBiR)](https://www.embirlab.com/) Lab. 

My research interests lie in modeling and control of complex dynamical systems via modern optimization techniques, with applications to soft robotics and high-performance bipedal locomotion.

I received a B.E. in Mechatronics Engineering from [Northwestern Polytechnical University](https://en.nwpu.edu.cn/) in 2018, and an M.S. in Mechanical Engineering from the [University of Michigan](https://umich.edu/) in 2020.
