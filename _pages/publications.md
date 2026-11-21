---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<sup>&#42;</sup> First author; <sup>#</sup> Equal contribution.

## Preprints

1. **Wu, S.**<sup>&#42;</sup>, Wei, Y., & Wang, K. (2026). Latent-driven imputation and forecasting for partially observed time series (LIFTS). [[arXiv]](https://arxiv.org/abs/2610.03916)

2. **Wu, S.**<sup>&#42;</sup>, Yang, D., Xu, Y., & Feng, L. (2025). Sparsity-induced global matrix autoregressive model with auxiliary network data. Under review. [[arXiv]](https://arxiv.org/abs/2503.08579)

3. Tian, Y., **Wu, S.**, & Feng, L. (2025). Nonlinear multiple response regression and learning of latent spaces. Under review. [[arXiv]](https://arxiv.org/abs/2503.21608)

4. Li, Z., **Wu, S.**<sup>#</sup>, & Feng, L. (2024). Time series generative learning with application to brain imaging analysis. Under review. [[arXiv]](https://arxiv.org/abs/2407.14003)

## Publications

1. Li, Y., **Wu, S.**, Yang, Z., Xu, Q., Liu, Y., Lin, Z., Zhang, M. M., Djurić, P., & Thiery, A. H. (2026). Continuous-depth deep Gaussian processes. Accepted at *NeurIPS 2026*.

2. **Wu, S.**<sup>&#42;</sup>, Wang, F., & Feng, L. (2024). Individualized image region detection with total variation. *Statistical Analysis and Data Mining: The ASA Data Science Journal*, *17*(3), e11684. [[Paper]](https://onlinelibrary.wiley.com/doi/abs/10.1002/sam.11684) [[Code]](https://github.com/sanyouwu/Individual-Region-Dection)

3. **Wu, S.**<sup>&#42;</sup>, & Feng, L. (2023). Sparse Kronecker product decomposition: A general framework of signal region detection in image regression. *Journal of the Royal Statistical Society Series B: Statistical Methodology*, *85*(3), 783–809. [[Paper]](https://arxiv.org/abs/2210.09128) [[Code]](https://github.com/sanyouwu/SKPD)

4. **Wu, S.**<sup>&#42;</sup>, Feng, X., & Zhou, F. (2020). Metric learning by similarity network for deep semi-supervised learning. In *Developments of Artificial Intelligence Technologies in Computation and Robotics: Proceedings of the 14th International FLINS Conference (FLINS 2020)* (pp. 995–1002). [[Paper]](https://arxiv.org/abs/2004.14227)
