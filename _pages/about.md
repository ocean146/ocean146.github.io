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

<p>
  He is currently a 3rd-year master student of 
  <a href="http://aim-nercms.whu.edu.cn/">AIM Lab</a> at 
  <a href="http://multimedia.whu.edu.cn/">National Engineering Research Center for Multimedia Software (国家多媒体软件工程技术研究中心)</a> and 
  <a href="https://www.whu.edu.cn/">Wuhan University (武汉大学)</a>, 
  advised by <a href="https://wangzwhu.github.io/home/">Prof. Zheng Wang</a>.
</p>

<p>
  His research interests include crowd counting, object detection, and computer vision. 
  He is actively seeking <strong>industry opportunities</strong> in computer vision, machine learning, or related fields, 
  and welcomes roles such as algorithm engineer or applied scientist.
</p>

<p>
  If you are interested in <strong>academic collaboration</strong> on crowd counting or raw object detection, 
  or would like to discuss potential <strong>industry positions</strong>, 
  please feel free to email him at 
  <a href="mailto:whuocean@whu.edu.cn">whuocean@whu.edu.cn</a>.
</p>

<a href='../assets/xiehaiyang_cv_cn.pdf'>CV<strong></strong></a>

# 🔥 News

- _2025.11_: &nbsp;🎉🎉 [SimROD](https://ocean146.github.io/SimROD2025/) is accepted by AAAI 2026. Code and paper are available at Project [Page](https://ocean146.github.io/SimROD2025/)
- _2024.06_: &nbsp;🎉🎉 He won the national scholarship at Wuhan University!(Top 2%)
- _2024.06_: &nbsp;🎉🎉 He won the first place in the Challenge on Low-light Object Detection and instance Segmentation (Detection) and the third place in (Segmentation), the 4th Physics-Based Vision meets Deep Learning Workshop, CVPR 2024！
- _2023.07_: &nbsp;🎉🎉 One paper is accepted by ACM MM 2023!

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/SimROD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SimROD: A Simple Baseline for Raw Object Detection with Global and Local Enhancements](https://ocean146.github.io/SimROD2025/)

<strong>Haiyang Xie</strong>, <a href="https://xishen0220.github.io" target="_blank">Xi Shen</a>, <a href="http://www.shihuahuang.cn" target="_blank">Shihua Huang</a>, <a href="https://qiruiwang0728.github.io/homepage/" target="_blank">Qirui Wang</a>, <a href="https://wangzwhu.github.io/home/" target="_blank">Zheng Wang</a>

- SimROD takes a packed RAW image as input and first learns a global gamma transformation through the Global Gamma Enhancement (GGE) module. The transformed data is then processed by Green-Guided Local Enhancement (GGLE) to enhance local details. SimROD outperformed the state-of-the-art method with just 1% of the parameters. Code and paper are available at <a href="https://ocean146.github.io/SimROD2025/">Project Page</a>.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/mm23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Striking a balance: Unsupervised cross-domain crowd counting via knowledge diffusion](https://dl.acm.org/doi/abs/10.1145/3581783.3611797)

<strong>Haiyang Xie\*</strong>, Zhengwei Yang\*, Huilin Zhu, Zheng Wang†

- This paper introduces a Selfawareness Knowledge Diffusion method (SaKnD) that leverages the self-knowledge without establishing cross-domain knowledge relationships, which aims to balance the knowledge bias between general and domain-specific knowledge
</div>
</div>

# 🎖 Honors and Awards

- _2024.06_ He won the national scholarship at Wuhan University!(Top 2%)
- _2024.06_ He won the first place in the Challenge on Low-light Object Detection and instance Segmentation (Detection) and the third place in (Segmentation), the 4th Physics-Based Vision meets Deep Learning Workshop, CVPR 2024.
- _2022.09_ He received the first prize Tencent Scholarship.
- _2022.09_ He received the first-class scholarship from Wuhan University.
- _2020.12_ He won the first prize in the Hubei Province division of the National College Student Mathematics Competition.

# 📖 Educations

- _2023.09 - 2026.06 (now)_, Master, Wuhan University, Wuhan.
- _2018.09 - 2023.06_, Bachelor, Wuhan University, Wuhan.
- _2020.03 - 2021.06_, Minor in Economics, Wuhan University, Wuhan.

# 💻 Internships

- _2025.05 - 2025.09_, Tencent, Shenzhen, China.
- _2024.05 - 2024.08_, TeleAI, Beijing, China.
- _2023.06 - 2023.09_, [intellindust](https://intellindust.cn/), Shenzhen, China, advised by [Xi Shen](https://xishen0220.github.io/).
