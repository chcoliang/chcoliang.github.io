---
permalink: /
title: "Congliang Chen"
excerpt: "Research Assistant Professor at Shenzhen Loop Area Institute. Recruiting in optimization algorithms and machine learning systems."
author_profile: true
navigation_data: navigation
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

<section class="profile-intro" id="about-me">
  <p class="profile-intro__kicker">Research Assistant Professor · Shenzhen Loop Area Institute</p>
  <h1>Congliang Chen</h1>
  <p class="profile-intro__lead">I am a Research Assistant Professor at the <a href="https://www.slai.edu.cn/en/home">Shenzhen Loop Area Institute</a>, affiliated with the <a href="https://www.slai.edu.cn/en/node/377">Center for AI Theoretical Foundation and Systems</a>. I received my B.S. from the <a href="https://eecs.pku.edu.cn/">School of Electronics Engineering and Computer Science, Peking University</a>, and my Ph.D. from <a href="https://www.cuhk.edu.cn/en">The Chinese University of Hong Kong, Shenzhen</a>, advised by <a href="https://tomluo123.github.io/">Prof. Zhi-Quan (Tom) Luo</a>.</p>
  <p>My research focuses on optimization algorithms and machine learning systems for modern AI models. My broader research goal is to build core methodological capabilities for large-model agents from mathematical structure and theoretical analysis, and to turn those capabilities into verifiable performance gains for real training and inference workloads.</p>
  <p>I am especially interested in structured quasi-Newton and second-order optimization, generalization-oriented training algorithms, post-training and alignment optimization, distributed optimization, optimization methods for reinforcement learning, low-precision training and inference, model adaptation and parameter-efficient tuning, and high-performance operator generation, benchmarking, and performance modeling.</p>
  <p class="profile-links">
    <a href="mailto:chencongliang@slai.edu.cn">Email</a>
    <a href="https://scholar.google.com/citations?user=O1P1-EAAAAAJ">Google Scholar</a>
    <a href="https://github.com/chcoliang">GitHub</a>
    <a href="https://www.slai.edu.cn/en/teacher/168">SLAI Profile</a>
    <a href="/zh">中文</a>
  </p>
</section>

<section class="homepage-block homepage-block--notice" id="recruiting">
  <h2>Recruiting</h2>
  <p><strong>I am recruiting Research Assistants, prospective PhD students, and motivated interns</strong> in two directions: optimization algorithms and machine learning systems.</p>
  <p>Please email <a href="mailto:chencongliang@slai.edu.cn">chencongliang@slai.edu.cn</a> with your CV, transcript if available, a short research/engineering summary, and links to papers, code, or projects. PhD applicants should also follow official SLAI admissions information, including the <a href="https://www.slai.edu.cn/en/InternationalAdmissions">International Admissions Information</a> page when applicable.</p>
  <details class="fold-block" open>
    <summary>Open directions and student fit</summary>
    <div class="fold-block__content">
      <h3>Optimization Algorithms</h3>
      <ul>
        <li>Structured quasi-Newton and second-order algorithms for large-scale learning and adaptation.</li>
        <li>Generalization-oriented optimization algorithms and theory-informed training principles.</li>
        <li>Post-training and alignment optimization algorithms.</li>
        <li>Distributed optimization algorithms for multi-worker and heterogeneous training environments.</li>
        <li>Optimization methods for reinforcement learning and agent training.</li>
      </ul>
      <h3>Machine Learning Systems</h3>
      <ul>
        <li>Low-precision training and inference systems.</li>
        <li>Model adaptation, parameter-efficient tuning, and deployment-oriented fine-tuning systems.</li>
        <li>High-performance operator generation, benchmarking, and performance modeling for modern AI workloads.</li>
      </ul>
      <p><strong>Good fit:</strong> strong math foundations, solid Python/deep-learning programming, and interest in both theory and real-model experiments. CUDA/Triton/systems experience is a plus.</p>
    </div>
  </details>
</section>

<section class="homepage-block" id="news">
  <h2>News</h2>
  <ul class="news-list">
    <li><span>2026</span> We are looking for research assistants, prospective PhD students, and interns in optimization algorithms and machine learning systems.</li>
    <li><span>2025</span> <a href="https://openreview.net/forum?id=iBExhaU3Lc">Adam-mini</a> and <a href="https://openreview.net/forum?id=NQEe7B7bSw">GEM for diversity-preserving SFT</a> were accepted to ICLR 2025.</li>
    <li><span>2024</span> <a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/ee0e45ff4de76cbfdf07015a7839f339-Abstract-Conference.html">Why Transformers Need Adam</a> appeared at NeurIPS 2024.</li>
  </ul>
</section>

<section class="homepage-block" id="research">
  <h2>Research Interests</h2>
  <ul class="interest-list">
    <li><strong>Optimization algorithms:</strong> structured quasi-Newton and second-order methods, generalization-oriented optimization, post-training and alignment optimization, distributed optimization, and reinforcement-learning optimization.</li>
    <li><strong>Machine learning systems:</strong> low-precision training and inference, model adaptation and parameter-efficient tuning, and high-performance operator generation, benchmarking, and performance modeling.</li>
  </ul>
</section>

<section class="homepage-block" id="selected-work">
  <h2>Selected Publications</h2>
  <p class="publication-note">(* indicates equal contribution, † indicates corresponding author). <a href="https://scholar.google.com/citations?user=O1P1-EAAAAAJ"><img class="citation-badge" src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations" alt="Google Scholar citations"></a></p>

  <div class="pub-list">
    <div class="pub-item">
      <div class="pub-year">2025</div>
      <div class="pub-body">
        <h3><a href="https://openreview.net/forum?id=iBExhaU3Lc">Adam-mini: Use Fewer Learning Rates To Gain More</a></h3>
        <p>Yushun Zhang*, <strong>Congliang Chen*</strong>, Ziniu Li, Tian Ding, Chenwei Wu, Diederik P. Kingma, Yinyu Ye, Zhi-Quan Luo, and Ruoyu Sun. ICLR 2025.</p>
      </div>
    </div>
    <div class="pub-item">
      <div class="pub-year">2025</div>
      <div class="pub-body">
        <h3><a href="https://openreview.net/forum?id=NQEe7B7bSw">Preserving Diversity in Supervised Fine-Tuning of Large Language Models</a></h3>
        <p>Ziniu Li, <strong>Congliang Chen</strong>, Tian Xu, Zeyu Qin, Jiancong Xiao, Zhi-Quan Luo, and Ruoyu Sun. ICLR 2025.</p>
      </div>
    </div>
    <div class="pub-item">
      <div class="pub-year">2024</div>
      <div class="pub-body">
        <h3><a href="https://proceedings.neurips.cc/paper_files/paper/2024/hash/ee0e45ff4de76cbfdf07015a7839f339-Abstract-Conference.html">Why Transformers Need Adam: A Hessian Perspective</a></h3>
        <p>Yushun Zhang, <strong>Congliang Chen</strong>, Tian Ding, Ziniu Li, Ruoyu Sun, and Zhi-Quan Luo. NeurIPS 2024.</p>
      </div>
    </div>
    <div class="pub-item">
      <div class="pub-year">2023</div>
      <div class="pub-body">
        <h3><a href="https://ieeexplore.ieee.org/abstract/document/10237319/">Efficient-Adam: Communication-Efficient Distributed Adam</a></h3>
        <p><strong>Congliang Chen</strong>, Li Shen, Wei Liu, and Zhi-Quan Luo. IEEE Transactions on Signal Processing, 2023.</p>
      </div>
    </div>
    <div class="pub-item">
      <div class="pub-year">2022</div>
      <div class="pub-body">
        <h3><a href="https://www.jmlr.org/papers/v23/20-1438.html">Towards Practical Adam: Non-Convexity, Convergence Theory, and Mini-Batch Acceleration</a></h3>
        <p><strong>Congliang Chen*</strong>, Li Shen*, Fangyu Zou*, and Wei Liu. JMLR 2022.</p>
      </div>
    </div>
  </div>

  <details class="fold-block" id="publications">
    <summary>Show more publications</summary>
    <div class="fold-block__content">
      <ul class="publication-list">
        <li><a href="https://dl.acm.org/doi/abs/10.1145/3470890">Quantized Adam with Error Feedback</a><br><strong>Congliang Chen</strong>, Li Shen, Haozhi Huang, and Wei Liu. ACM Transactions on Intelligent Systems and Technology, 2021.</li>
        <li><a href="https://ieeexplore.ieee.org/abstract/document/10149826/">A Unified Analysis of AdaGrad with Weighted Aggregation and Momentum Acceleration</a><br>Li Shen, <strong>Congliang Chen</strong>, Fangyu Zou, Zequn Jie, Ju Sun, and Wei Liu. IEEE Transactions on Neural Networks and Learning Systems, 2023.</li>
        <li><a href="https://proceedings.neurips.cc/paper_files/paper/2022/hash/b6260ae5566442da053e5ab5d691067a-Abstract-Conference.html">Adam Can Converge Without Any Modification On Update Rules</a><br>Yushun Zhang, <strong>Congliang Chen</strong>, Naichen Shi, Ruoyu Sun, and Zhi-Quan Luo. NeurIPS 2022.</li>
        <li><a href="https://proceedings.mlr.press/v130/chen21c.html">Communication Efficient Primal-Dual Algorithm for Nonconvex Nonsmooth Distributed Optimization</a><br><strong>Congliang Chen</strong>, Jiawei Zhang, Li Shen, Peilin Zhao, and Zhi-Quan Luo. AISTATS 2021.</li>
      </ul>
    </div>
  </details>
</section>

<section class="homepage-block" id="experience">
  <h2>Experience</h2>
  <div class="compact-columns">
    <div>
      <h3>Education</h3>
      <ul>
        <li>2018.08 - 2025.03, Ph.D., The Chinese University of Hong Kong, Shenzhen.</li>
        <li>2014.09 - 2018.06, B.S., Peking University.</li>
      </ul>
    </div>
    <div>
      <h3>Experience & Service</h3>
      <ul>
        <li>2025 - Present, Research Assistant Professor, Shenzhen Loop Area Institute.</li>
        <li>2019.07 - 2023.07, Research Intern, Tencent AI Lab, Shenzhen.</li>
        <li>Reviewer for ICML, NeurIPS, ICLR, ICCV, CVPR, and related venues.</li>
      </ul>
    </div>
  </div>
</section>
