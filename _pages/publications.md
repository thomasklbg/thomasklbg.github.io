---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[Bandits Meet Mechanism Design to Combat Clickbait in Online Recommendation](https://openreview.net/pdf?id=iIhXNqNh1c) <br />
Thomas Kleine Buening, [Aadirupa Saha](https://aadirupa.github.io/), [Christos Dimitrakakis](https://sites.google.com/site/christosdimitrakakis), [Haifeng Xu](https://www.haifeng-xu.com/) <br />
Interactive Learning Workshop at NeurIPS 2023, working paper 


[An Improved Dynamic Regret Algorithm for Adaptive Non-Stationary Dueling Bandits](https://arxiv.org/abs/2210.14322) <br /> 
Thomas Kleine Buening, [Aadirupa Saha](https://aadirupa.github.io/) <br />
AISTATS 2023


[Interactive Inverse Reinforcement Learning for Cooperative Games](https://proceedings.mlr.press/v162/buning22a/buning22a.pdf) <br /> 
Thomas Kleine Buening, [Anne-Marie George](https://scholar.google.de/citations?user=uOuR7XgAAAAJ&hl=en), [Christos Dimitrakakis](https://sites.google.com/site/christosdimitrakakis) <br /> 
ICML 2022, Best Paper Award at the Cooperative AI Workshop at NeurIPS 2021 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
