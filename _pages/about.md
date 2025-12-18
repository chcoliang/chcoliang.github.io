---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 🧑‍🎓 About Me

I am Congliang Chen (陈淙靓). I received my B.S. from the School of Electronics Engineering and Computer Science, Peking University, and my Ph.D. from The Chinese University of Hong Kong, Shenzhen, advised by [Prof. Zhi-Quan (Tom) Luo](https://tomluo123.github.io/). Now, I am working as a research assistant professor at Shenzhen Loop Area Institute. My research focuses on numerical computation, optimization algorithms for large language models, and kernel generation and optimization.

My work on distributed Adam establishes theoretical acceleration in multi-worker settings, and I developed a communication-efficient Adam variant that enables neural network training with only 1-bit communication per parameter. I also contributed to Adam-mini, a lightweight and practical optimizer variant tailored for efficient large-scale training. In addition, I worked on GEM, which studies how to maintain output/response diversity during SFT to mitigate mode collapse and improve generalization. My research has been published in venues such as JMLR, IEEE TSP, and top-tier conferences including NeurIPS and ICLR with <a href='https://scholar.google.com/citations?user=O1P1-EAAAAA'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


**Recruiting:** We’re recruiting **Research Assistants** and **PhD students** to work on LLM optimization and kernel generation & optimization.

Topics include:

- Optimization algorithms for large language models 

- Kernel generation, scheduling, and low-level performance optimization

If you’re interested, please email me with (1) your CV, (2) a short summary of your research/engineering experience, and (3) links to papers/code (if any).

# 📝 Publications 

(* indicates equal contributions, † indicates corresponding author).

## Journal
-  [Towards practical adam: Non-convexity, convergence theory, and mini-batch acceleration](https://www.jmlr.org/papers/v23/20-1438.html)<br> **Congliang Chen\***, Li Shen\*, Fangyu Zou\*, and Wei Liu, Journal of Machine Learning Research 23, no. 229 (2022): 1-47.

-   [Efficient-adam: Communication-efficient distributed adam](https://ieeexplore.ieee.org/abstract/document/10237319/) <br> **Congliang Chen**, Li Shen, Wei Liu, and Zhi-Quan Luo, IEEE Transactions on Signal Processing 71 (2023): 3257-3266.

-  [Quantized adam with error feedback](https://dl.acm.org/doi/abs/10.1145/3470890) <br>  **Congliang Chen**, Li Shen, Haozhi Huang, and Wei Liu, ACM Transactions on Intelligent Systems and Technology (TIST) 12, no. 5 (2021): 1-26.

- [A unified analysis of AdaGrad with weighted aggregation and momentum acceleration](https://ieeexplore.ieee.org/abstract/document/10149826/)<br> Li Shen, **Congliang Chen**, Fangyu Zou, Zequn Jie, Ju Sun, and Wei Liu, IEEE Transactions on Neural Networks and Learning Systems 35, no. 10 (2023): 14482-14490.

## Conference


- [Communication efficient primal-dual algorithm for nonconvex nonsmooth distributed optimization](https://proceedings.mlr.press/v130/chen21c.html) <br>  **Congliang Chen**, Jiawei Zhang, Li Shen, Peilin Zhao, and Zhiquan Luo, In International conference on artificial intelligence and statistics, pp. 1594-1602. PMLR, 2021.

- [Adam-mini: Use fewer learning rates to gain more.](https://openreview.net/forum?id=iBExhaU3Lc)<br> Yushun Zhang\*, **Congliang Chen\***, Ziniu Li, Tian Ding, Chenwei Wu, Diederik P. Kingma, Yinyu Ye, Zhi-Quan Luo, and Ruoyu Sun,  In The Thirteenth International Conference on Learning Representations.


- [Preserving Diversity in Supervised Fine-Tuning of Large Language Models](https://openreview.net/forum?id=NQEe7B7bSw)<br> Ziniu Li, **Congliang Chen**, Tian Xu, Zeyu Qin, Jiancong Xiao, Zhi-Quan Luo, and Ruoyu Sun, In The Thirteenth International Conference on Learning Representations.

- [Why transformers need adam: A hessian perspective](https://proceedings.neurips.cc/paper_files/paper/2024/hash/ee0e45ff4de76cbfdf07015a7839f339-Abstract-Conference.html) <br> Yushun Zhang, **Congliang Chen**, Tian Ding, Ziniu Li, Ruoyu Sun, and Zhiquan Luo, Advances in neural information processing systems 37 (2024): 131786-131823.


- [Adam can converge without any modification on update rules](https://proceedings.neurips.cc/paper_files/paper/2022/hash/b6260ae5566442da053e5ab5d691067a-Abstract-Conference.html)<br> Yushun Zhang, **Congliang Chen**, Naichen Shi, Ruoyu Sun, and Zhi-Quan Luo, Advances in neural information processing systems 35 (2022): 28386-28399.

# 📖 Educations
- *2018.08 - 2025.03*, Ph.D., The Chinese University of Hong Kong, Shenzhen, Shenzhen, China. 
- *2014.09 - 2018.06*, Undergraduate, Peking University, Beijing, China. 


# 💻 Internships
- *2019.07 - 2023.07*, Tencent AI Lab, Shenzhen, China.

# 🏫 Services
- Reviwers of ICML, NeurIPS, ICLR, ICCV, CVPR.