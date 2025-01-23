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
From 2022 to January 2025, I pursued my Master's degree at the School of Electrical and Information Engineering, Tianjin University, under the supervision of Associate Prof. [Jiale Cao](https://jialecao001.github.io/).

Since January 2025, I have been working as a Researcher in the Foundation Model Group at MEGVII Technology.

My research interests primarily focus on three areas: (1) **Embodied AI**, (2) **Video Generation**, and (3) **Autonomous Driving**.

<!-- From 2023 to Jan. 2025, I am a research intern at Foundation model group in MEGVII Technology, supervised by [Tiancai Wang](https://scholar.google.com.hk/citations?user=YI0sRroAAAAJ&hl=zh-CN) and [Yingfei Liu](https://scholar.google.com.hk/citations?user=pF9KA1sAAAAJ&hl=zh-CN). -->

# 🔥 News
- *2025.01*: We are hiring research interns all year round, please feel free to drop me your resume at bin_xie@tju.edu.cn.

- *2025.01*: One paper(Glad) is accepted by ICLR2025.

- *2024.11*: I’m awarded National Scholarship!

- *2024.07*: One paper(QLSeg) is accepted by Pattern Recognition.
<!-- - **2024.04**: I am actively pursuing PhD program opportunities for the Fall of 2025. Should my work align with your interests, I warmly invite you to get in touch with me. -->
- *2024.02*: One paper(SED) is accepted by CVPR2024.

# Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/papers/sed.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

SED: A Simple Encoder-Decoder for Open-Vocabulary Semantic Segmentation
|**CVPR2024**|[Paper](https://arxiv.org/abs/2311.15537)|[Code](https://github.com/xb534/SED)|

**Bin Xie**, Jiale Cao, Jin Xie, Fahad Shahbaz Khan,  Yanwei Pang

- <strong style="color:green"> By utilizing the simple yet efficient CER module, SED achieves a better trade-off between accuracy and performance for open-vocabulary semantic segmentation.</strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Pattern Recognition</div><img src='images/papers/qlseg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Multi-Query and Multi-Level Enhanced Network for Semantic Segmentation
|**Pattern Recognition**|[Paper](https://xb534.github.io/)|[Code](https://github.com/xb534/QLSeg)|

**Bin Xie**, Jiale Cao, Rao Muhammad Anwer, Jin Xie, Jing Nie, Aiping Yang, Yanwei Pang

- <strong style="color:green"> To address the limitations of current single-query designs, which fail to fully exploit the diverse, multi-level information available in plain Vision Transformers (ViT), we propose a multi-query and multi-level enhanced network for semantic segmentation.</strong>
</div>
</div>

# Service
Invited Reviewer for conferences:
- ICLR 2025
  
Invited Reviewer for journals:
- Pattern Recognition (PR)
