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
From 2022 to January 2025, I pursued my Master's degree at the School of Electrical and Information Engineering, Tianjin University, under the supervision of Associate Prof. [Jiale Cao](https://seea.tju.edu.cn/info/1014/2183.htm).

Since January 2025, I have been working as a Researcher in the Foundation Model Group at MEGVII Technology. 

My research interests primarily focus on three areas: (1) **Robotics**, (2) **Multi-Modal**, and (3) **RL**.

<span style="color: red;">We are hiring research interns all year round, please feel free to drop me your resume at xiebin@dexmal.com.</span>

# 🔥 News
- *2026.01*: One paper (MemoryVLA) is accepted by ICLR 2026. Congratulations to [@Hao Shi](https://shihao1895.github.io/) !
- *2025.11*: One paper (SpatialActor) is accepted by AAAI 2026 (Oral). Congratulations to [@Hao Shi](https://shihao1895.github.io/) !
- *2025.10*: One paper (SED++) is accepted by IEEE TPAMI 2025.
- *2025.01*: One paper (Glad) is accepted by ICLR 2025.

# Publications 

## Preprint Papers
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/papers/geovla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

GeoVLA: Empowering 3D Representations in Vision-Language-Action Models<br>
[Paper](https://arxiv.org/abs/2508.09071) | [Demo](https://linsun449.github.io/GeoVLA/)

Lin Sun, **Bin Xie**, Yingfei Liu, Hao Shi, Tiancai Wang, Jiale Cao

- <strong style="color:green"> GeoVLA is a vision-language-action framework that integrates 3D geometry for better robotic manipulation. It fuses image-language data with point cloud features to enhance spatial awareness, achieving state-of-the-art performance and robustness in simulation and real-world tasks. </strong>
</div>
</div>

## Published Papers
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/papers/memoryvla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

MemoryVLA: Perceptual-Cognitive Memory in Vision-Language-Action Models for Robotic Manipulation<br>
[Paper](https://arxiv.org/abs/2508.19236) | [Demo](https://shihao1895.github.io/MemoryVLA/)

Hao Shi, **Bin Xie**, Yingfei Liu, Lin Sun, Fengrong Liu, Tiancai Wang, Erjin Zhou, Haoqiang Fan, Xiangyu Zhang, Gao Huang

- <strong style="color:green"> MemoryVLA is a Cognition-Memory-Action framework for long-horizon robotic manipulation inspired by human working memory and hippocampal systems. It uses a Perceptual-Cognitive Memory Bank to store temporal context and adaptively fuses past experience with current observations for temporally aware action generation. </strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026 (Oral)</div><img src='images/papers/spatial_actor.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

SpatialActor: Exploring Disentangled Spatial Representations for Robust Robotic Manipulation<br>

Hao Shi, **Bin Xie**, Yingfei Liu, Yang Yue, Tiancai Wang, Haoqiang Fan, Xiangyu Zhang, Gao Huang

- <strong style="color:green"> SpatialActor is a disentangled framework for robust robotic manipulation. It decouples perception into complementary high-level geometry from fine-grained but noisy raw depth and coarse but robust depth expert priors, along with low-level spatial cues and appearance semantics.</strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/papers/glad.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Glad: A Streaming Scene Generator for Autonomous Driving<br>
[Paper](https://arxiv.org/abs/2503.00045)

**Bin Xie**, Yingfei Liu, Tiancai Wang, Jiale Cao, Xiangyu Zhang

- <strong style="color:green"> Glad is an efficient framework for generating video data in autonomous driving scenarios. It produces temporally coherent videos frame-by-frame, serving as a robust baseline for data synthesis and simulation in autonomous driving.</strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/papers/sed.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

SED: A Simple Encoder-Decoder for Open-Vocabulary Semantic Segmentation<br>
[Paper](https://arxiv.org/abs/2311.15537) | [Code](https://github.com/xb534/SED)

**Bin Xie**, Jiale Cao, Jin Xie, Fahad Shahbaz Khan,  Yanwei Pang

- <strong style="color:green"> By utilizing the simple yet efficient CER module, SED achieves a better trade-off between accuracy and performance for open-vocabulary semantic segmentation.</strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Pattern Recognition</div><img src='images/papers/qlseg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Multi-Query and Multi-Level Enhanced Network for Semantic Segmentation<br>
[Paper](https://xb534.github.io/) | [Code](https://github.com/xb534/QLSeg)

**Bin Xie**, Jiale Cao, Rao Muhammad Anwer, Jin Xie, Jing Nie, Aiping Yang, Yanwei Pang

- <strong style="color:green"> To address the limitations of current single-query designs, which fail to fully exploit the diverse, multi-level information available in plain Vision Transformers (ViT), we propose a multi-query and multi-level enhanced network for semantic segmentation.</strong>
</div>
</div>

# Service
Invited Reviewer for conferences:
- ICLR 2026, CVPR 2026, ECCV 2026
- ICLR 2025
  
Invited Reviewer for journals:
- International Journal of Computer Vision (IJCV)
- Pattern Recognition (PR)
