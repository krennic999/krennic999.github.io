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

<br><br>
# 👀 About Me

Hi,

🌱 I’m Xiaoxiao Ma, a first-year PhD student at USTC, in [USTC-BIVLab](https://bivlab123.github.io/) supervised by [Prof. Feng Zhao](https://scholar.google.com/citations?user=r6CvuOUAAAAJ). I am currently a research intern at Meituan

📖 My research interest includes:
  - Generative models & image synthesis, autoregressive models, vision-language models
  - Image restoration, image enhancement

📫 Looking forward to any collaborations or internship positions, feel free to contact me via email

<br><br>
# 🔥 News
- *2025.06*: &nbsp; Delighted to announce that [HQ-CLIP](https://arxiv.org/abs/2507.22431) was accepted by ICCV 2025!
- *2024.09*: &nbsp; Delighted to announce that [MPI](https://arxiv.org/abs/2401.14966) was accepted by NeurIPS 2024!
- *2024.09*: &nbsp;  I was invited to give a talk at ByteDance as the author of [STAR](https://arxiv.org/abs/2406.10797)! See slides [here](https://github.com/krennic999/krennic999.github.io/blob/main/files/star_pre_talk.pdf)
- *2024.06*: &nbsp; [STAR](https://arxiv.org/abs/2406.10797) was released on Arxiv.


<br><br>
# 📝 Publications

<!-- ----------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2024</div><img src='images/STAR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[STAR: Scale-wise Text-to-image generation via Auto-Regressive representations](https://arxiv.org/abs/2406.10797)
<iframe src="https://ghbtns.com/github-btn.html?user=krennic999&repo=STAR&type=star&count=true" frameborder="0" scrolling="0" width="150" height="20" title="GitHub"></iframe>

**Xiaoxiao Ma\***, Mohan Zhou\*, Tao Liang, Yalong Bai, et al.

[**Project**](https://krennic999.github.io/STAR/) <strong><span class='show_paper_citations' data='EE_KGzcAAAAJ:UeHWp8X0CEIC'></span></strong>
- STAR is a novel scale-wise text-to-image model that is effective and efficient in performance
- Notably, STAR shows efficiency by requiring 2.95s to generate 512×512 images (compared to 6.48s for PixArt-α)
</div>
</div>

<!-- ----------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/MPI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Masked Pre-trained Model Enables Universal Zero-shot Denoiser](https://arxiv.org/abs/2401.14966)
<iframe src="https://ghbtns.com/github-btn.html?user=krennic999&repo=MPI&type=star&count=true" frameborder="0" scrolling="0" width="150" height="20" title="GitHub"></iframe>

**Xiaoxiao Ma\***, Zhixiang Wei\*, Yi Jin, Pengyang Ling, et al.

[**Project**](https://github.com/krennic999/MPI) <strong><span class='show_paper_citations' data='EE_KGzcAAAAJ:9yKSN-GCB0IC'></span></strong>
- MPI is a zero-shot denoising pipeline designed for many types of noise degradations
- Only around 10s takes for a MPI to denoise on single noisy image
</div>
</div>

<!-- ----------------------------------------------------------- -->


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/hqclip.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HQ-CLIP: Leveraging Large Vision-Language Models to Create High-Quality Image-Text Datasets and CLIP Models](https://arxiv.org/abs/2507.22431)
<iframe src="https://ghbtns.com/github-btn.html?user=w1oves&repo=hqclip&type=star&count=true" frameborder="0" scrolling="0" width="150" height="20" title="GitHub"></iframe>

Zhixiang Wei\*, Guangting Wang\*, **Xiaoxiao Ma**, et al.

[**Project**](https://zxwei.site/hqclip/) <strong><span class='show_paper_citations' data='EE_KGzcAAAAJ:YsMSGLbcyi4C'></span></strong>
- A CLIP training framework trained on 1.3B bidirectional image–text pairs, combining bidirectional supervision and label classification, achieving SoTA zero-shot and retrieval performance.
</div>
</div>

<!-- ----------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/Reins.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Stronger, Fewer, \& Superior: Harnessing Vision Foundation Models for Domain Generalized Semantic Segmentation](https://arxiv.org/abs/2312.04265)
<iframe src="https://ghbtns.com/github-btn.html?user=w1oves&repo=Rein&type=star&count=true" frameborder="0" scrolling="0" width="150" height="20" title="GitHub"></iframe>

Zhixiang Wei\*, Lin Chen\*, Yi Jin\*, **Xiaoxiao Ma**, et al.

[**Project**](https://github.com/w1oves/Rein) <strong><span class='show_paper_citations' data='EE_KGzcAAAAJ:2osOgNQ5qMEC'></span></strong>
- Rein is a PEFT framework based on vision foundation models for domain generalized semantic segmentation (DGSS) with merely 1% trainable parameters
</div>
</div>

<!-- ----------------------------------------------------------- -->

<br><br>
# 💻 Experiences
- *2025.04 - Persent*, Meituan, Beijing. 
- *2024.12 - 2025.03*, Shanghai AI Laboratory, Shanghai.
- *2024.04 - 2024.12*, Duxiaoman, Beijing.

<br><br>
# 📝 Academic Service (Reviewer)
- NeurIPS 2025
- IEEE TPAMI


<br><br>
# 🎖 Honors and Awards
- 2022~2024 The First Prize Scholarship of USTC for three continusous years
- 2024 National Scholarship for Undergraduate Students


<br><br>
# 📖 Educations
- *2022.09 - now*, University of Science and Technology of China, Anhui, Master candidate in Computer Vision
- *2018.09 - 2022.06*, China Agricultural University, Beijing. B. Eng in Computer Science

<br><br>

<!-- # 💬 Invited Talks
- *2021.06*, Xiaoxiao Ma dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Xiaoxiao Ma dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)-->
