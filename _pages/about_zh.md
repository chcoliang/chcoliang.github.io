---
permalink: /zh
title: "陈淙靓"
excerpt: ""
author_profile: true
navigation_data: navigation_zh
redirect_from: 
  - /about/
  - /about_zh.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 🧑‍🎓 关于我

我是陈淙靓。 我本科毕业于北京大学信息科学技术学院，博士毕业于香港中文大学（深圳），导师为[罗智泉教授](https://tomluo123.github.io/)。目前，我在深圳河套学院担任研究助理教授。我的研究方向主要包括数值计算、大语言模型优化算法，以及算子生成与优化。

我在分布式 Adam 方面的工作证明了其在多机训练场景下的理论加速效果，并提出了一种通信高效的 Adam 变体，使得神经网络训练过程中每轮每个参数仅需 1 bit 的通信开销。我也参与了 Adam-mini 的研究，该方法是一种轻量且实用的优化器变体，面向大规模训练的高效需求。此外，我还参与了 GEM 工作，研究如何在大模型监督微调过程中保持输出多样性，以缓解模式坍塌并提升泛化能力。我的研究成果发表于 JMLR、IEEE TSP 等期刊以及 NeurIPS、ICLR 等顶级国际会议，<a href='https://scholar.google.com/citations?user=O1P1-EAAAAA'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>。


**招募信息**：我们正在招募**研究助理（Research Assistant**和**博士生**，研究方向包括大模型优化以及算子生成与优化。

研究主题包括：

- 大语言模型的优化算法

- 算子生成与性能优化

如有兴趣，请发送邮件并附上：（1）个人简历（CV），（2）简要的科研/工程经历介绍，（3）相关论文或代码链接（如有）。


<span class='anchor' id='publication'></span>

# 📝 论文列表 

(* indicates equal contributions, † indicates corresponding author).

## 期刊
-  [Towards practical adam: Non-convexity, convergence theory, and mini-batch acceleration](https://www.jmlr.org/papers/v23/20-1438.html)<br> **Congliang Chen\***, Li Shen\*, Fangyu Zou\*, and Wei Liu, Journal of Machine Learning Research 23, no. 229 (2022): 1-47.

-   [Efficient-adam: Communication-efficient distributed adam](https://ieeexplore.ieee.org/abstract/document/10237319/) <br> **Congliang Chen**, Li Shen, Wei Liu, and Zhi-Quan Luo, IEEE Transactions on Signal Processing 71 (2023): 3257-3266.

-  [Quantized adam with error feedback](https://dl.acm.org/doi/abs/10.1145/3470890) <br>  **Congliang Chen**, Li Shen, Haozhi Huang, and Wei Liu, ACM Transactions on Intelligent Systems and Technology (TIST) 12, no. 5 (2021): 1-26.

- [A unified analysis of AdaGrad with weighted aggregation and momentum acceleration](https://ieeexplore.ieee.org/abstract/document/10149826/)<br> Li Shen, **Congliang Chen**, Fangyu Zou, Zequn Jie, Ju Sun, and Wei Liu, IEEE Transactions on Neural Networks and Learning Systems 35, no. 10 (2023): 14482-14490.

## 会议


- [Communication efficient primal-dual algorithm for nonconvex nonsmooth distributed optimization](https://proceedings.mlr.press/v130/chen21c.html) <br>  **Congliang Chen**, Jiawei Zhang, Li Shen, Peilin Zhao, and Zhiquan Luo, In International conference on artificial intelligence and statistics, pp. 1594-1602. PMLR, 2021.

- [Adam-mini: Use fewer learning rates to gain more.](https://openreview.net/forum?id=iBExhaU3Lc)<br> Yushun Zhang\*, **Congliang Chen\***, Ziniu Li, Tian Ding, Chenwei Wu, Diederik P. Kingma, Yinyu Ye, Zhi-Quan Luo, and Ruoyu Sun,  In The Thirteenth International Conference on Learning Representations.


- [Preserving Diversity in Supervised Fine-Tuning of Large Language Models](https://openreview.net/forum?id=NQEe7B7bSw)<br> Ziniu Li, **Congliang Chen**, Tian Xu, Zeyu Qin, Jiancong Xiao, Zhi-Quan Luo, and Ruoyu Sun, In The Thirteenth International Conference on Learning Representations.

- [Why transformers need adam: A hessian perspective](https://proceedings.neurips.cc/paper_files/paper/2024/hash/ee0e45ff4de76cbfdf07015a7839f339-Abstract-Conference.html) <br> Yushun Zhang, **Congliang Chen**, Tian Ding, Ziniu Li, Ruoyu Sun, and Zhiquan Luo, Advances in neural information processing systems 37 (2024): 131786-131823.


- [Adam can converge without any modification on update rules](https://proceedings.neurips.cc/paper_files/paper/2022/hash/b6260ae5566442da053e5ab5d691067a-Abstract-Conference.html)<br> Yushun Zhang, **Congliang Chen**, Naichen Shi, Ruoyu Sun, and Zhi-Quan Luo, Advances in neural information processing systems 35 (2022): 28386-28399.

<span class='anchor' id='education'></span>

# 📖 教育经历
- *2018.08 - 2025.03*, 博士，香港中文大学（深圳）。
- *2014.09 - 2018.06*, 本科， 北京大学。


<span class='anchor' id='internship'></span>

# 💻 实习经历
- *2019.07 - 2023.07*, 腾讯AI Lab，深圳，中国。

<span class='anchor' id='service'></span>

# 🏫 服务经历
- ICML, NeurIPS, ICLR, ICCV, CVPR等会议审稿人.