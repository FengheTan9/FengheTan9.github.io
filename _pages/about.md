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

- I am a PhD student at the University of Science and Technology of China [(USTC)](https://en.ustc.edu.cn/) supervised by Prof. [Shaohua Kevin Zhou](https://www.linkedin.com/in/shaohua-kevin-zhou-231a094b/). I focus on *self-supervised learning*, *foundation model*, *medical image analysis*, *computer vision and pattern recognition*. I received my bachelor's and master's degrees from Harbin Institute of Technology [(HIT)](http://www.hit.edu.cn/) in 2021 and 2023, respectively. My master's tutor is Prof. [Jianrui Ding](https://scholar.google.com/citations?user=4TsvOR8AAAAJ&hl=zh-CN).  I have published 30+ papers at Top Conferences and Journals with [![citations](https://img.shields.io/badge/citations-800+-blue)](https://scholar.google.com/citations?user=x1pODsMAAAAJ)
- Hobbies: 🎞️🏀🀄🃏🍔
- **<font color="#cc0000">Seeking postdoctoral and research intern positions, feel free to contact me at </font> fhtan9@mail.ustc.edu.cn** 😎🥰🤗

# 🔥 News

- *2026.06*: &nbsp;One paper accepted to *ECCV*-26.
- *2026.02*: &nbsp;One paper accepted to *CVPR*-26 Findings.
- *2026.01*: &nbsp;One paper accepted to *ICLR*-26.
- *2026.01*: &nbsp;Two papers accepted to *ISBI*-26 (Both are**<font color="#ff0000"> Orals</font>**).
- *2025.11*: &nbsp;Start my research internship at Alibaba DAMO Academy.
- *2025.11*: &nbsp;One paper accepted to *WACV*-26.
- *2025.10*: &nbsp;We released [**U-Bench**](https://arxiv.org/pdf/2510.07041), banchmarking with 100 u-shape variants. 🤗🤗🤗
- *2025.08*: &nbsp;One paper accepted to *IEEE Transactions on Image Processing*.
- *2025.08*: &nbsp;One paper accepted to *Medical Image Analysis*.
- *2025.07*: &nbsp;One paper accepted to *ECAI*-25 (**<font color="#ff0000">Orals</font>**).
- *2025.07*: &nbsp;One paper accepted to *ACM MM*-25.
- *2025.06*: &nbsp;Three papers accepted to *MICCAI*-25.
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

**$\dagger$: Equal contributions; $\ast$: Corresponding author**  [(*All publications*)](https://scholar.google.com/citations?user=x1pODsMAAAAJ) 

### Self-supervised Learning & Foundation Model 💪

- ![citations](https://img.shields.io/badge/Medical Image Analysis-2026-white) [Hi-End-MAE: Hierarchical encoder-driven masked autoencoders are stronger vision learners for medical image segmentation](https://www.sciencedirect.com/science/article/abs/pii/S1361841525003160), **Fenghe Tang**, Qingsong Yao, Wenxin Ma, Chenxu Wu, Zihang Jiang<sup>$\ast$</sup>, S. Kevin Zhou<sup>$\ast$</sup>. *Medical Image Analysis. (Impact factor=11.8)*  [**[code]**](https://github.com/FengheTan9/Hi-End-MAE) ![GitHub Repo stars](https://img.shields.io/github/stars/FengheTan9/Hi-End-MAE) 

- ![citations](https://img.shields.io/badge/ICLR-2026-white)  [MedGMAE: Gaussian Masked Autoencoders for Medical Volumetric Representation Learning](https://openreview.net/pdf?id=Z2XIRLv535), Xueming Fu<sup>$\dagger$</sup>, **Fenghe Tang**<sup>$\dagger$</sup>, Rongsheng Wang, Yingtai Li, Lixia Han, Jian Lu, Zihang Jiang<sup>$\ast$</sup>, S Kevin Zhou<sup>$\ast$</sup>. [**[code]**](https://github.com/windrise/MedGMAE) ![GitHub Repo stars](https://img.shields.io/github/stars/windrise/MedGMAE)

- ![citations](https://img.shields.io/badge/Medical Image Analysis-2025-white)  [MambaMIM: Pre-training Mamba with State Space Token-interpolation and its Application to Medical Image Segmentation](https://arxiv.org/pdf/2408.08070.pdf), **Fenghe Tang**<sup>$\dagger$</sup>, Bingkun Nian<sup>$\dagger$</sup>, Yingtai Li<sup>$\dagger$</sup>, Zihang Jiang, Jie Yang, Wei Liu<sup>$\ast$</sup>, S. Kevin Zhou<sup>$\ast$</sup>. *Medical Image Analysis. (Impact factor=11.8)*  [**[code]**](https://github.com/FengheTan9/MambaMIM) ![GitHub Repo stars](https://img.shields.io/github/stars/FengheTan9/MambaMIM)

- ![citations](https://img.shields.io/badge/MICCAI-2025-white) [SimCroP: Radiograph Representation Learning with Similarity-driven Cross-granularity Pre-training](https://arxiv.org/pdf/2509.08311), Rongsheng Wang<sup>$\dagger$</sup>, **Fenghe Tang**<sup>$\dagger$</sup>, Qingsong Yao, Rui Yan<sup>$\ast$</sup>, Xu Zhang, Zhen Huang, Haoran Lai, Zhiyang He, Xiaodong Tao, Zihang Jiang<sup>$\ast$</sup>, S. Kevin Zhou<sup>$\ast$</sup>. [**[code]**](https://github.com/ToniChopp/SimCroP)  ![GitHub Repo stars](https://img.shields.io/github/stars/ToniChopp/SimCroP)

- ![citations](https://img.shields.io/badge/MICCAI-2024-white)  [HySparK: Hybrid Sparse Masking for Large Scale Medical Image Pre-Training](https://arxiv.org/pdf/2408.05815.pdf), **Fenghe Tang**, Ronghao Xu, Qingsong Yao, Xueming Fu, Heqin Zhu, Zaiyi Liu, S. Kevin Zhou<sup>$\ast$</sup>.   *(Early Accept)*  [**[code]**](https://github.com/FengheTan9/HySparK) ![GitHub Repo stars](https://img.shields.io/github/stars/FengheTan9/HySparK)

- ![citations](https://img.shields.io/badge/MIDL-2024-white)  [Slide-SAM: Medical SAM Meets Sliding Window](https://arxiv.org/pdf/2311.10121.pdf), Quan Quan<sup>$\dagger$</sup>, **Fenghe Tang**<sup>$\dagger$</sup>, Zikang Xu, Heqin Zhu, S. Kevin Zhou<sup>$\ast$</sup>. *(Oral, Best Oral Paper Finalists)*  [**[code]**](https://github.com/Curli-quan/Slide-SAM) ![GitHub Repo stars](https://img.shields.io/github/stars/Curli-quan/Slide-SAM)


### Medical Image Segmentation 🫀🫁🧠

- ![citations](https://img.shields.io/badge/ECCV-2026-white)  [Concept-to-Pixel: Prompt-Free Universal Medical Image Segmentation](https://arxiv.org/pdf/2603.17746), Haoyun Chen$\dagger$, **Fenghe Tang**<sup>$\dagger$</sup>, Wenxin Ma, S. Kevin Zhou<sup>$\ast$</sup>. [**[code]**](https://github.com/Yundi218/Concept-to-Pixel)  ![GitHub Repo stars](https://img.shields.io/github/stars/Yundi218/Concept-to-Pixel)

- ![citations](https://img.shields.io/badge/arXiv-2025-white)  [U-Bench: A Comprehensive Understanding of U-Net through 100-Variant Benchmarking](https://arxiv.org/pdf/2510.07041), **Fenghe Tang**, Chengqi Dong, Wenxin Ma, Zikang Xu, Heqin Zhu, Zihang Jiang, Rongsheng Wang, Yuhao Wang, Chenxu Wu, S. Kevin Zhou<sup>$\ast$</sup>.  [**[project]**](https://fenghetan9.github.io/ubench)  [**[data]**](https://huggingface.co/datasets/FengheTan9/U-Bench)  [**[weights]**](https://huggingface.co/FengheTan9/U-Bench)  [**[code]**](https://github.com/FengheTan9/U-Bench)   ![GitHub Repo stars](https://img.shields.io/github/stars/FengheTan9/U-Bench)

- ![citations](https://img.shields.io/badge/ACM MM-2025-white)  [Mobile U-ViT: Revisiting large kernel and U-shaped ViT for efficient medical image segmentation](https://arxiv.org/pdf/2508.01064), **Fenghe Tang**<sup>$\dagger$</sup>, Bingkun Nian<sup>$\dagger$</sup>,  Jianrui Ding, Wenxin Ma, Quan Quan, Chengqi Dong, Jie Yang, Wei Liu<sup>$\ast$</sup>, S. Kevin Zhou<sup>$\ast$</sup>. [**[code]**](https://github.com/FengheTan9/LLM4Seg)   ![GitHub Repo stars](https://img.shields.io/github/stars/FengheTan9/Mobile-U-ViT)

- ![citations](https://img.shields.io/badge/MICCAI-2025-white) [Pre-Trained LLM is a Semantic-Aware and Generalizable Segmentation Booster](https://arxiv.org/pdf/2506.18034.pdf), **Fenghe Tang**<sup>$\dagger$</sup>, Wenxin Ma<sup>$\dagger$</sup>, Zhiyang He, Xiaodong Tao, Zihang Jiang<sup>$\ast$</sup>, S. Kevin Zhou<sup>$\ast$</sup>.  [**[code]**](https://github.com/FengheTan9/LLM4Seg)   ![GitHub Repo stars](https://img.shields.io/github/stars/FengheTan9/LLM4Seg)

- ![citations](https://img.shields.io/badge/IEEE--TIP-2025-white) [SRS: Siamese Reconstruction-Segmentation Network based on Dynamic-Parameter Convolution](https://ieeexplore.ieee.org/abstract/document/11174084), Bingkun Nian<sup>$\dagger$</sup>, **Fenghe Tang**<sup>$\dagger$</sup>,  Jianrui Ding, Jie Yang, Zhonglong Zheng, S. Kevin Zhou<sup>$\ast$</sup>, Wei Liu<sup>$\ast$</sup>. *IEEE Transactions on Image Processing. (Impact factor=13.7)*  [**[code]**](https://github.com/fidshu/SRSNet)  ![GitHub Repo stars](https://img.shields.io/github/stars/fidshu/SRSNet)

- ![citations](https://img.shields.io/badge/npj Dig. Med.-2025-white) [Fair ultrasound diagnosis via adversarial protected attribute aware perturbations on latent embeddings](https://www.nature.com/articles/s41746-025-01641-y), Zikang Xu, **Fenghe Tang**, Quan Quan, Qingsong Yao, Qingpeng Kong, Jianrui Ding, Chunping Ning, S. Kevin Zhou<sup>$\ast$</sup>. *npj Digital Medicine. (Impact factor=15.1)*  [**[code]**](https://github.com/XuZikang/APPLE) ![GitHub Repo stars](https://img.shields.io/github/stars/XuZikang/APPLE)

- ![citations](https://img.shields.io/badge/ISBI-2024-white) [CMUNeXt: An Efficient Medical Image Segmentation Network based on Large Kernel and Skip Fusion](https://arxiv.org/pdf/2308.01239), **Fenghe Tang**, ‪Jianrui Ding‬‬, Quan Quan, Lingtao Wang, Chunping Ning,‪ S. Kevin Zhou<sup>$\ast$</sup>‬‬. *(Oral)* [**[code]**](https://github.com/FengheTan9/CMUNeXt)   ![GitHub Repo stars](https://img.shields.io/github/stars/FengheTan9/CMUNeXt)

- ![citations](https://img.shields.io/badge/ISBI-2023-white) [CMU-Net: A Strong ConvMixer-based Medical Ultrasound Image Segmentation Network](https://arxiv.org/abs/2210.13012), **Fenghe Tang**, Lingtao Wang, Chunping Ning, Min Xian, Jianrui Ding<sup>$\ast$</sup>.  [**[code]**](https://github.com/FengheTan9/CMU-Net)  ![GitHub Repo stars](https://img.shields.io/github/stars/FengheTan9/CMU-Net)


### AI4S 🧐

- ![citations](https://img.shields.io/badge/Nat Comm.-2025-white) [Deep generalizable prediction of RNA secondary structure via base pair motif energy](https://www.nature.com/articles/s41467-025-60048-1), Heqin Zhu, **Fenghe Tang**, Quan Quan, Ke Chen, Peng Xiong<sup>$\ast$</sup>, S. Kevin Zhou<sup>$\ast$</sup>. *Nature Communications (Impact factor=15.7)* [**[code]**](https://github.com/heqin-zhu/BPfold) ![GitHub Repo stars](https://img.shields.io/github/stars/heqin-zhu/BPfold)



# 🏅 Honors and Awards
- **Outstanding Graduate Reward**, Anhui Province, *2026*
- **Outstanding Graduate Reward**, University of Science and Technology of China, *2026*
- **National Scholarship for Postgraduates**, Chinese Ministry of Education, *2025*
- **MICCAI 2025 outstanding reviewer award ([Honorable Mentions](https://conferences.miccai.org/2025/en/MICCAI-2025-OUTSTANDING-REVIEWER-AWARDS.html))**, *MICCAI Society, 2025*
- **Suzhou Industrial Park Scholarship**, University of Science and Technology of China, 2024
- **Outstanding Master's Theses**, Harbin Institute of Technology, *2023*
- **National Scholarship for Postgraduates**, Chinese Ministry of Education, *2023*
- **Outstanding Graduate Reward**, Harbin Institute of Technology, *2023*
- **Excellent Developer of MindSpore**, HUAWEI, *2022*
- **Outstanding Graduate Reward**, Shandong Province, *2021*
- **The Grand Prize of CANN**, HUAWEI, *2021*

# 📖 Educations
- *2023.09 -  (now)*, Ph.D in Electronic Information, School of BME, [University of Science and Technology of China](https://en.ustc.edu.cn/). 
- *2021.09 - 2023.06*, Master of Computer Technology, School of Computer Science and Technology, [Harbin Institute of Technology](http://encs.hit.edu.cn/). 
- *2017.09 - 2021.06*, Bachelor of Software Engineering, School of Computer Science and Technology, [Harbin Institute of Technology](http://encs.hit.edu.cn/). 

# 💬 Professional Services

*Conference Reviewers:*

- The IEEE/CVF Conference on Computer Vision and Pattern Recognition (*CVPR*), 2025-2026
- Neural Information Processing Systems (*NeurIPS*), 2026
- ACM International Conference on Multimedia (*ACM MM*), 2025-2026
- European Conference on Computer Vision (*ECCV*), 2026
- International Conference on Medical Image Computing and Computer-Assisted Intervention (*MICCAI*), 2024-2026
- *SIGGRAPH Asia*, 2026
- British Machine Vision Conference (*BMVC*), 2026
- International Symposium on Biomedical Imaging (*ISBI*), 2026

*Journal Reviewers:*

- *IEEE Transactions on Pattern Analysis and Machine Intelligence* (*TPAMI*)
- *Medical Image Analysis* (*MedIA*)
- *Information Fusion* (*INFFUS*)
- *IEEE Journal of Biomedical and Health Informatics* (*JBHI*)
- *Expert Systems With Applications* (*ESWA*)
- *Knowledge-based Systems* (*KBS*)
- *Engineering Applications of Artificial Intelligence* (*EAAI*)
- Neurocomputing
- *Computerized Medical Imaging and Graphics* (*CMIG*)

*Teaching Assistant:*

- 2024 Fall, USTC, Medical Image Computing (*BMED6208P.01_152261*)

Talks:

- MICS Webinar [(*20250916*)](https://mp.weixin.qq.com/s/PDTai2kPjiHPma7Frnth6Q)

# 💻 Internships
- *2025.11 - (now)*, Alibaba DAMO Academy
- *2021.04 - 2022.04*, HUAWEI, Ascend,  [Mindspore developer](https://github.com/mindspore-ai/mindspore).

# 🙌 Developed contribution

- Benchmarks of Medical Image Segmentation [**[code]**](https://github.com/FengheTan9/Medical-Image-Segmentation-Benchmarks)  ![GitHub Repo stars](https://img.shields.io/github/stars/FengheTan9/Medical-Image-Segmentation-Benchmarks)
- Contribute [SPPNet (Kaiming He .et al-TPAMI 2015)](https://gitee.com/mindspore/models/tree/master/research/cv/SPPNet) on [MindSpore Official Model Zoo](https://gitee.com/mindspore)  [**[code]**](https://gitee.com/mindspore/models/tree/master/research/cv/SPPNet)



<div style="max-width:300px; width:100%; margin-left: 0; text-align: left;">
  <script type="text/javascript" id="clustrmaps" 
    src="//clustrmaps.com/map_v2.js?d=jaOYIPr0TvknXrE-gi6cz5uHkp6qI9mtwrj_B6wtt10&cl=ffffff&w=a">
  </script>
</div>
