---
layout: archive
title: ""
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


## Preprint

1. Li, Z., **Wu, S.**, & Feng, L. (2024). Time series generative learning with application to brain imaging
analysis, under review. [[Arxiv]](https://arxiv.org/abs/2407.14003)

## Publications

3. **Wu, S.**, Wang, F., & Feng, L. (2024). Individualized image region detection with total variation. In
Statistical analysis and data mining: The asa data science journal (Vol. 17, e11684). [[Paper]](https://onlinelibrary.wiley.com/doi/abs/10.1002/sam.11684)

2. **Wu, S.**, & Feng, L. (2023). Sparse kronecker product decomposition: A general framework of signal
region detection in image regression. In Journal of the royal statistical society series b: Statistical
methodology (Vol. 85, pp. 783–809). [[Paper]](https://arxiv.org/abs/2210.09128)

1. **Wu, S.**, Feng, X., & Zhou, F. (2020). Metric learning by similarity network for deep semi-supervised
learning. In Developments of artificial intelligence technologies in computation and robotics: Proceedings of
the 14th international flins conference (flins 2020) (pp. 995–1002). [[Paper]](https://arxiv.org/abs/2004.14227)
