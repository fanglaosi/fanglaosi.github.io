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

# 😀️ Biography
I am currently a graduate student at **[Sun Yat-sen University](https://www.sysu.edu.cn/)**, advised by Prof. **[Mengyuan Liu](https://www.ece.pku.edu.cn/info/1046/2596.htm)** (Assistant Professor in PeKing Uiniversity).

I received a B.S. degree from **[Jinan University](https://www.jnu.edu.cn/main.htm)**.

My research focuses on **3D Point Cloud Analysis** and **In-Context Learning**. I am also highly interested in Large Language and Multimodal Models.

I am fortunate to have the opportunity to collaborate with Dr. [Xia Li](https://xialipku.github.io/) (ETH Zurich) and Dr. [Xiangtai Li](https://xialipku.github.io/) (MMLab@NTU).


# 🔥 News
- *2024.12*: &nbsp; [PlayGen](https://arxiv.org/pdf/2412.00887) is released on arXiv, the [Code](https://github.com/GreatX3/Playable-Game-Generation) and [Demo](http://124.156.151.207/) is also open-sourced. 
- *2024.06*: &nbsp; [ModelNet-O & PointMLS](https://arxiv.org/abs/2401.08210) is accepted by **CVIU'2024**. 🎉🎉🎉
- *2024.04*: &nbsp; [Point-In-Context-Seg](https://fanglaosi.github.io/Point-In-Context_Pages/) is released on Arxiv, 2024.
- *2024.02*: &nbsp; [Skeleton-in-Context](https://arxiv.org/abs/2312.03703) is accepted by **CVPR'2024**. 🎉🎉🎉
- *2023.09*: &nbsp; [Point-In-Context](https://proceedings.neurips.cc/paper_files/paper/2023/hash/8407d254b5baacf69ee977aa34f0e521-Abstract-Conference.html) is accepted by **NeurIPS'2023** as a **spotlight**. 🎉🎉🎉
- *2023.06*: &nbsp; [Point-In-Context](https://arxiv.org/abs/2306.08659) is released on arXiv, and the [Code](https://github.com/fanglaosi/Point-In-Context) is also open-sourced. 
- *2023.03*: &nbsp; [ModelNet-O & PointMLS](https://arxiv.org/abs/2401.08210) is released on Arxiv, 2023.

[//]: # (# 💻 Internships)


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2024</div><img src='images/PlayGen.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Playable Game Generation](https://arxiv.org/abs/2412.00887) \\
Mingyu Yang, Junyou Li, **Zhongbin Fang**, Sheng Chen, Yangbin Yu, Qiang Fu, Wei Yang, Deheng Ye.

<a href='https://arxiv.org/pdf/2412.00887'>
  <img src='https://img.shields.io/badge/Paper-PDF-orange?style=flat&logo=arXiv&logoColor=orange' alt='arXiv PDF'>
</a>
<a href='https://github.com/GreatX3/Playable-Game-Generation' style='padding-left: 0.5rem;'>
  <img src='https://img.shields.io/badge/Code-Link-orange?style=flat&logo=Google%20chrome&logoColor=orange' alt='Code'>
</a>
<a href='http://124.156.151.207/' style='padding-left: 0.5rem;'>
  <img src='https://img.shields.io/badge/Demo-Link-orange?style=flat&logo=Google%20chrome&logoColor=orange' alt='Demo'>
</a>

- We develop PlayGen to enable playable game generation with real-time interaction, sufficient visual quality, and accurate simulation of interactive mechanics.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2024</div><img src='images/PIC-Seg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Point-In-Context: Understanding Point Cloud via In-Context Learning](https://arxiv.org/abs/2404.12352) \\
Mengyuan Liu, **Zhongbin Fang📧**, Xia Li📧, Joachim M Buhmann, Deheng Ye, Xiangtai Li, Chen Change Loy

<a href='https://arxiv.org/pdf/2404.12352.pdf'>
  <img src='https://img.shields.io/badge/Paper-PDF-blue?style=flat&logo=arXiv&logoColor=blue' alt='arXiv PDF'>
</a>
<a href='https://fanglaosi.github.io/Point-In-Context_Pages/' style='padding-left: 0.5rem;'>
  <img src='https://img.shields.io/badge/Project-Page-blue?style=flat&logo=Google%20chrome&logoColor=blue' alt='Project Page'>
</a>

- Possess stronger performance and generalization ability and achieve SOTA in multi-dataset segmentation tasks.
- Can perform unique part segmentation tasks via customized prompts.

</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/SiC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Skeleton-in-Context: Unified Skeleton Sequence Modeling with In-Context Learning](https://arxiv.org/abs/2312.03703) \\
Xinshun Wang*, <strong>Zhongbin Fang*</strong>, Xia Li, Xiangtai Li, Chen Chen, Mengyuan Liu📧

<a href='https://arxiv.org/pdf/2312.03703.pdf'>
  <img src='https://img.shields.io/badge/Paper-PDF-green?style=flat&logo=arXiv&logoColor=green' alt='arXiv PDF'>
</a>
<a href='https://bradleywang0416.github.io/skeletonincontext/' style='padding-left: 0.5rem;'>
  <img src='https://img.shields.io/badge/Project-Page-green?style=flat&logo=Google%20chrome&logoColor=green' alt='Project Page'>
</a>

- The **first** to explore in-context learning for skeleton sequence modeling.
- Solve the over-fitting problem encountered when using the masked-modeling-style training framework of existing methods.

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/PIC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Explore In-Context Learning for 3D Point Cloud Understanding](https://proceedings.neurips.cc/paper_files/paper/2023/hash/8407d254b5baacf69ee977aa34f0e521-Abstract-Conference.html) **<span style="color:red">(Spotlight)</span>** \\
**Zhongbin Fang**, Xiangtai Li, Xia Li, Joachim M Buhmann, Chen Change Loy, Mengyuan Liu📧

<a href='https://arxiv.org/pdf/2306.08659.pdf'>
  <img src='https://img.shields.io/badge/Paper-PDF-red?style=flat&logo=arXiv&logoColor=red' alt='arXiv PDF'>
</a>
<a href='https://github.com/fanglaosi/Point-In-Context' style='padding-left: 0.5rem;'>
  <img src='https://img.shields.io/badge/Source-Code-red?style=flat&logo=Google%20chrome&logoColor=red' alt='Project Page'>
</a>

- The **first** to explore in-context learning for 3D point cloud.
- Solve the information leakage problem caused by previous MPM methods.
- Can improve the performance by selecting higher-quality prompts

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVIU 2024</div><img src='images/PointMLS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ModelNet-O: A Large-Scale Synthetic Dataset for Occlusion-Aware Point Cloud Classification](https://arxiv.org/abs/2401.08210) \\
**Zhongbin Fang**, Xia Li, Xiangtai Li, Shen Zhao📧, Mengyuan Liu📧

<a href='https://arxiv.org/pdf/2401.08210.pdf'>
  <img src='https://img.shields.io/badge/Paper-PDF-yellow?style=flat&logo=arXiv&logoColor=yellow' alt='arXiv PDF'>
</a>
<a href='https://github.com/fanglaosi/PointMLS' style='padding-left: 0.5rem;'>
  <img src='https://img.shields.io/badge/Source-Code-yellow?style=flat&logo=Google%20chrome&logoColor=yellow' alt='Project Page'>
</a>

-  Propose a challenging occluded point cloud classification dataset ModelNet-O.
-  Propose a robust occlusion-aware method, PointMLS, based on a multi-level sampling strategy.

</div>
</div>





# 🎖 Honors and Awards
- *2024.11* &nbsp; **National Scholarship** of Sun Yat-sen University (4%)
- *2022.10* &nbsp; The **First Prize Scholarship** of Sun Yat-sen University
- *2022.06* &nbsp; **Outstanding Graduate** of Jinan University
- *2021.10* &nbsp; **National Scholarship** of Jinan University (4%)
- *2020.10* &nbsp; The **First Prize Scholarship** and Outstanding Student Leader of Jinan University
- *2019.10* &nbsp; The **First Prize Scholarship** and Outstanding Student Leader of Jinan University

# 📖 Educations
- *2022.09 - (Now)* &nbsp; Master, Sun Yat-sen University, Shenzhen.
- *2018.09 - 2022.06* &nbsp; Undergraduate, Jinan University, Zhuhai.
- *2015.09 - 2018.06* &nbsp; No.113 Middle School, Guangzhou.
