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

Hi! 

Currently I'm a master student of **University of Science and Technology of China** (Sep. 2022 - Jun. 2025), advised by Prof. [S. Kevin Zhou](https://scholar.google.com/citations?user=8eNm2GMAAAAJ&hl=en). I am fortunate to be a member of [Medical Imaging, Robotics, Analytic Computing & Learning (MIRACLE) Lab](https://miracle.ustc.edu.cn/). Prior to this, I obtained my Bachelor's degree in Computer Science from **Hefei University of Technology** (Sep. 2018 - Jun. 2022).

My recent work focuses on diffusion models for ID-preserving image synthesis and image editing. If you are also interested, feel free to drop me an email.

My long-term research goal is to develop generative AI systems that possess creativity on par with professional artists and designers.

I enjoy creating beautiful things, such as photography and painting. I have over 50,000 followers on Pixiv and DeviantArt.

📣 <font color="#dd0000">I am actively looking for Ph.D. / researcher opportunities.</font> Please check out my resume [here](resume/Sijin Chen's Resume.pdf).

# 🔥 News


- *May. 2024*. &nbsp;🎉🎉 We release [Mojo](https://arxiv.org/abs/2311.12342), a training-free method for image editing by manipulating skip connection features.
- *May. 2024*. &nbsp;🐧🐧 Join <font color="#dd0000">Tencent</font> as a research intern, working on ID-preserving image synthesis. 
- *Dec. 2023*. &nbsp;🥇🥇 Win the <font color="#dd0000">Suzhou Industrial Park Scholarship</font>. 
- *Nov. 2023*. &nbsp;🎉🎉 We are excited to release [LoCo](https://arxiv.org/abs/2311.12342), a state-of-the-art layout-to-image synthesis method. LoCo is a training-free plugin designed to enhance the compositional capabilities of text-to-image diffusion models. A demo is available [here](https://huggingface.co/spaces/Pusheen/LoCo).
- *Jun. 2023*. &nbsp;🎉🎉 Our [DiffULD](https://arxiv.org/abs/2303.15728) paper is accepted to <font color="#dd0000">MICCAI 2023</font>. 




# 📝 Selected Publications 




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv</div><img src='images/mojo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**<font size=4>Mojo: Training-Free Text-guided Image Editing via Skip Connection Modulation</font>**](https://arxiv.org/abs/2405.20853) \\
**<font color="#dd0000">ArXiv</font>** \\
**<u>Peiang Zhao</u>**, Han Li, Ruiyang Jin, [S. Kevin Zhou](https://scholar.google.com/citations?user=8eNm2GMAAAAJ&hl=en)$^{\ddagger}$

[arXiv](https://arxiv.org/abs/2405.20853) \| [project](https://momopusheen.github.io/Mojo/) 

- A plug-and-play approach for text-guided image editing by modulating skip connection features.
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv</div><img src='images/loco_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**<font size=4>LoCo: Locally Constrained Training-Free Layout-to-Image Synthesis</font>**](https://arxiv.org/abs/2311.12342) \\
**<font color="#dd0000">ArXiv</font>** \\
**<u>Peiang Zhao</u>**, Han Li, Ruiyang Jin, [S. Kevin Zhou](https://scholar.google.com/citations?user=8eNm2GMAAAAJ&hl=en)$^{\ddagger}$

[arXiv](https://arxiv.org/abs/2311.12342) \| [project](https://momopusheen.github.io/LoCo/) \| [demo](https://huggingface.co/spaces/Pusheen/LoCo) 

- State-of-the-art training-free method for layout-to-image synthesis. 
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2023</div><img src='images/diffULD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**<font size=4>DiffULD: Diffusive Universal Lesion Detection</font>**](https://arxiv.org/pdf/2303.15728) \\
**<font color="#dd0000">MICCAI 2023</font>** \\
**<u>Peiang Zhao</u>**, Han Li, Ruiyang Jin, [S. Kevin Zhou](https://scholar.google.com/citations?user=8eNm2GMAAAAJ&hl=en)$^{\ddagger}$

[paper](https://link.springer.com/chapter/10.1007/978-3-031-43904-9_10) \| [arXiv](https://arxiv.org/pdf/2303.15728) 

- Proposed a diffusion model for Universal Lesion Detection (ULD).
</div>
</div>



# 🥇 Awards and Scholarships

- *Dec. 2023*. **Suzhou Industrial Park Scholarship**.
- *Oct. 2023*. **1st** Class Scholarship, University of Science and Technology of China.
- *Oct. 2022*. **1st** Class Scholarship, University of Science and Technology of China.
- *Jun. 2022*. **Outstanding Graduate**, Hefei University of Technology.
- *Aug. 2021*. **2nd** Prize, National Intelligent Car Race for University Students.
- *Dec. 2020*. **2nd** Prize, National Intelligent Car Race for University Students.
- *Jun. 2019*. **1st** Prize, Competition of Embedded Systems of Anhui Province.


# 📖 Educations

- *Sep. 2022 - Jun. 2025 (expected)*. Master student at University of Science and Technology of China. 
- *Sep. 2018 - Jun. 2022*. Bachelor student at Hefei University of Technology. 




<!-- # 💬 Oral Presentations

- *Oct. 2023*. Winner presentation of the Scan2Cap Challenge in the 3rd Language for 3D Scene Workshop at **<font color="#dd0000">ICCV 2023</font>**. \[[talk](https://www.youtube.com/watch?v=RLrdi-Yhn1o) \| [slides](presentation/[ICCV 2023 workshop talk] Vote2Cap-DETR.pdf)\]
- *Jun. 2023*. Paper presentation for "*End-to-End 3D Dense Captioning with Vote2Cap-DETR*" at the Workshop for Advances in 3D Vision, **<font color="#dd0000">VALSE 2023</font>**, Wuxi, China.  -->



# 💻 Internships

- *2024.05 - Present*. Tencent, QQ Image Lab, Shanghai, China.
- *2020.06 - 2020.18*. FISTCO Shanghai R&D Center, Shanghai, China.
  