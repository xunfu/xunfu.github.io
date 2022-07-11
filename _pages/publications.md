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

D. Bruder, X. Fu, and R. Vasudevan, “Advantages of Bilinear Koopman Realizations for the Modeling and Control of Systems with Unknown Dynamics”, _IEEE Robotics and Automation Letters_, 2021.

D. Bruder, X. Fu, R. B. Gillespie, C. D. Remy, and R. Vasudevan, "Koopman-Based Control of a Soft Continuum Manipulator under Variable Loading Conditions”, _IEEE Robotics and Automation Letters_, 2021.

D. Bruder, X. Fu, R. B. Gillespie, C. D. Remy, and R. Vasudevan, “Data-Driven Control of Soft Robots Using Koopman Operator Theory”, _IEEE Transactions on Robotics_, 2021.

X. Fu and X. Mo, “Review: The Application of Wearable Sensors on the Diagnosis and Monitoring of Parkinson’s Disease”, _DEStech Transactions on Engineering and Technology Research_, 2018.
