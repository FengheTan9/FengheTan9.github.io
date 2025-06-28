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

# 😊About Me

- I am a PhD student at the University of Science and Technology of China [(USTC)](https://en.ustc.edu.cn/) supervised by Prof. [S. Kevin Zhou](https://www.linkedin.com/in/s-kevin-zhou-231a094b). I focus on Self-supervised Learning, LVM, Medical Image Analysis, Computer Vision, and Pattern Recognition. I received my bachelor's and master's degrees from Harbin Institute of Technology [(HIT)](http://www.hit.edu.cn/) in 2021 and 2023, respectively. My master's tutor is Prof. [Jianrui Ding](https://scholar.google.com/citations?user=4TsvOR8AAAAJ&hl=zh-CN).  I have published 20+ papers at conferences and journals with citations [![citations](https://img.shields.io/badge/citations-200+-blue)](https://scholar.google.com/citations?user=x1pODsMAAAAJ)
- Hobbies: 🎞️🏀🀄🃏🍔

# 🔥 News

**Find collaborators on Foundation Model & Segmentation 🤗, feel free to contact me at fhtan9@mail.ustc.edu.cn** 😎🥰

- *2025.06*: &nbsp;Three paper accepted to *MICCAI*-25.
- *2025.04*: &nbsp;One paper accepted to *npj Digital Medicine*.
- *2025.04*: &nbsp;One paper accepted to *Nature Communications*.
- *2025.04*: &nbsp;One paper accepted to *Medical Image Analysis*.
- *2025.03*: &nbsp;One paper accepted to *MIDL*-25.
- *2025.03*: &nbsp;One paper accepted to *CVPR*-25.
- *2024.06*: &nbsp;One paper accepted to *MICCAI*-24.
- *2024.05*: &nbsp;One paper accepted to *MICCAI*-24 (**<font color="#ff0000">Early Accept, Top 11 %</font>**).
- *2024.04*: &nbsp;One paper accepted to *MIDL*-24 (**<font color="#ff0000">Oral, Best Oral Paper Finalists</font>**).
- *2024.02*: &nbsp;One paper accepted to *ISBI*-24 (**<font color="#ff0000">Oral</font>**).

# 📝 Selected publications

### Self-supervised learning & Foundation model

- ``MedIA'25``  MambaMIM: Pre-training Mamba with State Space Token-interpolation and its Application to Medical Image Segmentation

  **Fenghe Tang\***, Bingkun Nian\*, Yingtai Li\*, Jie Yang, Wei Liu, S. Kevin Zhou.    [**[paper]**](https://arxiv.org/pdf/2408.08070.pdf)  [**[code]**](https://github.com/FengheTan9/MambaMIM) ![GitHub Repo stars](https://img.shields.io/github/stars/FengheTan9/MambaMIM)

- `arXiv'25` Hi-End-MAE: Hierarchical encoder-driven masked autoencoders are stronger vision learners for medical image segmentation

  **Fenghe Tang**, Qingsong yao, Wenxin Ma, Chenxu Wu, Zihang Jiang, S. Kevin Zhou.   [**[paper]**](https://arxiv.org/pdf/2502.08347)  [**[code]**](https://github.com/FengheTan9/Hi-End-MAE) ![GitHub Repo stars](https://img.shields.io/github/stars/FengheTan9/Hi-End-MAE) 

- ``MICCAI'24``  HySparK: Hybrid Sparse Masking for Large Scale Medical Image Pre-Training  (**<font color="#ff0000">Early Accept</font>**)

  **Fenghe Tang**, Ronghao Xu, Qingsong Yao, Xueming Fu, Heqin Zhu, Zaiyi Liu, S. Kevin Zhou.   [**[pape]**](https://arxiv.org/pdf/2408.05815.pdf)  [**[code]**](https://github.com/FengheTan9/HySparK) ![GitHub Repo stars](https://img.shields.io/github/stars/FengheTan9/HySparK)

- ``MIDL'24``  Slide-SAM: Medical SAM Meets Sliding Window  (**<font color="#ff0000">Oral, Best Oral Paper Finalists</font>**)

  Quan Quan*, **Fenghe Tang\***, Zikang Xu, Heqin Zhu, S. Kevin Zhou.   [**[paper]**](https://arxiv.org/pdf/2311.10121.pdf)  [**[code]**](https://github.com/Curli-quan/Slide-SAM)   ![GitHub Repo stars](https://img.shields.io/github/stars/Curli-quan/Slide-SAM)

### Medical Image Segmentation

- ``MICCAI'25``   Pre-Trained LLM is a Semantic-Aware and Generalizable Segmentation Booster

  **Fenghe Tang***, Wenxin Ma*, Zhiyang He, Xiaodong Tao, Zihang Jiang, S. Kevin Zhou.    [**[paper]**](https://arxiv.org/pdf/2506.18034.pdf)  [**[code]**](https://github.com/FengheTan9/LLM4Seg)   ![GitHub Repo stars](https://img.shields.io/github/stars/FengheTan9/LLM4Seg)

- ``ISBI'24``   CMUNeXt: An Efficient Medical Image Segmentation Network based on Large Kernel and Skip Fusion  (**<font color="#ff0000">Oral</font>**)

  **Fenghe Tang**, ‪Jianrui Ding‬‬, Quan Quan, Lingtao Wang, Chunping Ning,‪ S. Kevin Zhou‬‬.    [**[paper]**](https://arxiv.org/pdf/2308.01239)  [**[code]**](https://github.com/FengheTan9/CMUNeXt)   ![GitHub Repo stars](https://img.shields.io/github/stars/FengheTan9/CMUNeXt)

- ``ISBI'23``   CMU-Net: A Strong ConvMixer-based Medical Ultrasound Image Segmentation Network

  **Fenghe Tang**, Lingtao Wang, Chunping Ning, Min Xian, Jianrui Ding.   [**[paper]**](https://arxiv.org/abs/2210.13012)  [**[code]**](https://github.com/FengheTan9/CMU-Net)  ![GitHub Repo stars](https://img.shields.io/github/stars/FengheTan9/CMU-Net)
  
- ``npj Digit. Med.'25``   Fair ultrasound diagnosis via adversarial protected attribute aware perturbations on latent embeddings

  Zikang Xu, **Fenghe Tang**, Quan Quan, Qingsong Yao, Qingpeng Kong, Jianrui Ding, Chunping Ning, S. Kevin Zhou.  [**[paper]**](https://www.nature.com/articles/s41746-025-01641-y)  [**[code]**](https://github.com/XuZikang/APPLE) ![img](https://camo.githubusercontent.com/debfb1bad4f3efe9dcb8c5946ce7eeadfe222c8d3cf3591a92c115d9761a3444/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f58755a696b616e672f4150504c452e7376673f6c6162656c3d5374617273267374796c653d736f6369616c)

**<font color="#9DC3E6">More publications are available at: </font>** [Google Scholar](https://scholar.google.com/citations?user=x1pODsMAAAAJ) 


# 🏅 Honors and Awards
- **Suzhou Industrial Park Scholarship**, University of Science and Technology of China, 2024
- **Outstanding Master's Theses**, Harbin Institute of Technology, *2023*
- **National Scholarship for Postgraduates**, Chinese Ministry of Education, *2023*
- **Outstanding Graduate Reward**, Harbin Institute of Technology, *2023*
- **Excellent Developer of Mindspore** , HUAWEI, *2022*
- **Outstanding Graduate Reward**, Shandong Province, *2021*
- **The Grand Prize of CANN**, HUAWEI, *2021*

# 📖 Educations
- *2023.09 -  (now)*, Ph.D of Electronic Information, School of BME, [University of Science and Technology of China](https://en.ustc.edu.cn/). 
- *2021.09 - 2023.06*, Master of Computer Technology, School of Computer Science and Technology, [Harbin Institute of Technology](http://encs.hit.edu.cn/). 
- *2017.09 - 2021.06*, Bachelor of Software Engineering, School of Computer Science and Technology, [Harbin Institute of Technology](http://encs.hit.edu.cn/). 

# 💬 Professional Services

*Conference Reviewers:*

- The IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2025
- ACM International Conference on Multimedia (ACM MM), 2025
- International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI), 2024-2025

*Teaching Assistant:*

- 2024 Fall, USTC, Medical Image Computing (*BMED6208P.01_152261*)

# 💻 Internships
- *2021.04 - 2022.04*, HUAWEI, Ascend,  [Mindspore developer](https://github.com/mindspore-ai/mindspore).

# 🙌 Developed contribution

- Benchmarks of Medical Image Segmentation [**[code]**](https://github.com/FengheTan9/Medical-Image-Segmentation-Benchmarks)  ![GitHub Repo stars](https://img.shields.io/github/stars/FengheTan9/Medical-Image-Segmentation-Benchmarks)
- open-source [SPPNet](https://gitee.com/mindspore/models/tree/master/research/cv/SPPNet) with [MindSpore](https://gitee.com/mindspore)  [**[code]**](https://gitee.com/mindspore/models/tree/master/research/cv/SPPNet)



<div style="max-width:300px; width:100%; margin: 0 auto; text-align: center;">
  <script type="text/javascript" id="clustrmaps" 
    src="//clustrmaps.com/map_v2.js?d=jaOYIPr0TvknXrE-gi6cz5uHkp6qI9mtwrj_B6wtt10&cl=ffffff&w=a">
  </script>
</div>
