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

# 👋 Hi there~

I’m a PhD student at The Hong Kong Polytechnic University (PolyU), advised by [Prof. Hongxia Yang](https://www4.comp.polyu.edu.hk/~hongxyang/). 

My research focuses on **Model Fusion**—combining multiple trained models from different domains, architectures, or datasets into a single, stronger model to aggregate complementary knowledge and improve performance, generalization, and efficiency. Broadly, I’m interested in LLMs, multimodal learning, and knowledge graphs.

I graduated with my B.S. from the College of Science, Beijing University of Posts and Telecommunications (BUPT). Then I was recommended to the State Key Laboratory of Networking and Switching Technology at BUPT.
<!--
, where I am completing my M.S. in Prof. [Jianxin Liao](https://baike.baidu.com/item/%E5%BB%96%E5%BB%BA%E6%96%B0/8469604)'s group. I was honored to work closely with Prof. Haifeng Sun (BUPT), Prof. Jingyu Wang (BUPT), Dr. Wei Tang (Huawei), and Dr. Yulong Cai (Huawei).
-->

Welcome to visit our website at [InfiX-AI](https://infix-ai.com/) and workspace at [Huggingface](https://huggingface.co/InfiX-ai).

<!--
I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

# 🔥 News
- **Now I join Prof. Hongxia Yang's group at the Hong Kong Polytechnic University (PolyU) as a PhD candidate.**
- *2025.09*: &nbsp;🎉🎉 Our two papers about *LLM Fusion* have been accepted by NeurIPS 2025.
- *2025.08*: &nbsp;🎉🎉 Our model InfiGFusion-14B has been released on Huggingface and get 4k stars!
- *2025.06*: Our paper about "Weakly Supervised Entity Alignment" was accepted by TKDD.
- Our paper about "Multi-modal Entity Alignment" was selected as Best Paper Candidate in ICMR 2024.


# 📝 Publications 

<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>
[Static Badge](https://img.shields.io/badge/arXiv-red)
-->

- ![Static Badge](https://img.shields.io/badge/Nexus%202025-blue) [Democratizing AI Through Model Fusion: A Comprehensive Review and Future Directions](https://www.cell.com/nexus/pdf/S2950-1601(25)00049-X.pdf) |  <br>
Qi Zhou, Yiming Zhang, Yanggan Gu, **Yuanyi Wang**, Zhijie Sang, Zhaoyi Yan, Zhen Li, Shengyu Zhang, Fei Wu, Hongxia Yang
- ![Static Badge](https://img.shields.io/badge/arXiv-red) [Model Merging Scaling Laws in Large Language Models](https://arxiv.org/pdf/2509.24244) | [**Repo**](https://arxiv.org/pdf/2509.24244)  <br>
**Yuanyi Wang**, Yanggan Gu, Yiming Zhang, Qi Zhou, Zhaoyi Yan, Congkai Xie, Xinyao Wang, Jianbo Yuan, Hongxia Yang
- ![Static Badge](https://img.shields.io/badge/NeurIPS%202025-blue) [InfiGFusion: Graph-on-Logits Distillation via Efficient Gromov-Wasserstein for Model Fusion](https://arxiv.org/pdf/2505.13893) | [**Model**](https://huggingface.co/InfiX-ai/InfiGFusion-14B) <br>
**Yuanyi Wang**, Zhaoyi Yan, Yiming Zhang, Qi Zhou, Yanggan Gu, Fei Wu, Hongxia Yang 
- ![Static Badge](https://img.shields.io/badge/NeurIPS%202025-blue) [InfiFPO: Implicit Model Fusion via Preference Optimization in Large Language Models](https://arxiv.org/pdf/2505.13878) | [**Model**](https://huggingface.co/InfiX-ai/InfiFPO-14B) <br>
Yanggan Gu, Zhaoyi Yan, **Yuanyi Wang**, Yiming Zhang, Qi Zhou, Fei Wu, Hongxia Yang 
- ![Static Badge](https://img.shields.io/badge/NAACL%202025-blue) [Rethinking Smoothness for Fast and Adaptable Entity Alignment Decoding](https://arxiv.org/pdf/2401.12798) | [**Code**](https://github.com/wyy-code/TFP) <br>
**Yuanyi Wang**, Han Li, Haifeng Sun, Lei Zhang, Bo He, Wei Tang, Tianhao Yan, Qi Qi, Jingyu Wang
- ![Static Badge](https://img.shields.io/badge/ICDE%202024-blue) [Towards semantic consistency: Dirichlet energy driven robust multi-modal entity alignment](https://arxiv.org/pdf/2401.17859) | [**Code**](https://github.com/wyy-code/DESAlign)<br>
**Yuanyi Wang**, Haifeng Sun, Jiabo Wang, Jingyu Wang, Wei Tang, Qi Qi, Shaoling Sun, Jianxin Liao 

- ![Static Badge](https://img.shields.io/badge/ICDM%202024-blue) [Interdependency Matters: Graph Alignment for Multivariate Time Series Anomaly Detection](https://arxiv.org/pdf/2410.08877) | [**Code**](https://github.com/wyy-code/MADGA)<br>
**Yuanyi Wang**, Haifeng Sun, Chengsen Wang, Mengde Zhu, Jingyu Wang, Wei Tang, Qi Qi, Zirui Zhuang, Jianxin Liao
- ![Static Badge](https://img.shields.io/badge/ICMR%202024-Best%20Paper%20Candidate-blue) [Multi-modal Entity Alignment via Position-enhanced Multi-label Propagation](https://dl.acm.org/doi/10.1145/3652583.3658085)  | [**Code**](https://github.com/OceanTangWei/PMMEA)<br>
Wei Tang, **Yuanyi Wang**
- ![Static Badge](https://img.shields.io/badge/ICSE%202024-blue) [LogExpert: Log-based Recommended Resolutions Generation using Large Language Model](https://dl.acm.org/doi/abs/10.1145/3639476.3639773)<br>
Jiabo Wang, Guojun Chu, Jingyu Wang, Haifeng Sun, Qi Qi, **Yuanyi Wang**, Ji Qi, Jianxin Liao
- ![Static Badge](https://img.shields.io/badge/ACM%20Transactions%20on%20Knowledge%20Discovery%20from%20Data-blue) [Understanding and Guiding Weakly Supervised Entity Alignment with Potential Isomorphism Propagation](https://arxiv.org/pdf/2402.03025) |  [**Code**](https://github.com/wyy-code/PipEA)<br>
**Yuanyi Wang**, Wei Tang, Haifeng Sun, et al


<!--
# 🔬 Research Experience

#### AI-assisted Automatic Construction of Device Parameter Database
- *2012 Lab, Huawei, Guangdong, China*
- **Objective:** Automatically parsing computation device manuals, extracting the device parameters, constructing the parameter database
- **Solution:** Pre-training for document layout analysis, Unified tabular structure recognition, LLM for text understanding

#### Automatic Anomalous Logs Resolution Recommendation
- *BUPT & China Mobile (Suzhou) Software Technology Co., Ltd, Beijing, China*
- **Objective:** Automatically parsing anomalous logs, generating recommended resolutions for anomalous logs
- **Solution:** Log parsing and summarization, Constructing log-based structural database, LLM for generating resolutions with RAG

#### Real-time Time-series Anomaly Detection and Location for ATE
- *2012 Lab, Huawei, Guangdong, China*
- **Objective:** Fast anomaly detection for multivariate time series data, Automatically analyzing oscillogram
- **Solution:** A novel framework for multivariate time series anomaly detection, Lightweight object segmentation, detection, and indicator analysis for oscillogram
-->

# 🔬 Academic Service
- Conference: Reviewer for the WWW, ACL
- Journal: Reviewer for the SoftwareX, IEEE TNNLS


# 🎖 Honors and Awards
- *2025.06* Outstanding Thesis Award (Top 1%)
- *2025.06* Outstanding Postgraduate of Beijing (Top 1%)
- *2024.11* National Scholarship (Top 1%)
- *2024.10* Outstanding Postgraduate (Top 5%)
- *2022.09* Outstanding Graduate of Beijing (Top 5%)
- *2021.12* Star of Youth Studies (10 students in BUPT each year)
- *2019.09 ~ 2021.09* National Encouragement Scholarship, Three times (Top 3%)

# 📖 Educations
- *2022.09 - 2025.06*, Postgraduate, State Key Laboratory of Networking and Switching Technology, BUPT, Beijing. 
- *2018.09 - 2022.06*, Undergraduate, Beijing University of Posts and Telecommunications (BUPT), Beijing.
- *2015.09 - 2018.06*, Xi'an Tie Yi High School, Shaanxi.


# 💬 Invited Talks
- *2024.11*, AI-assisted Waveform Anomaly Detection, Huawei internal talk, Shenzhen.
- *2024.10*, AI-assisted Automatic Testing Equipments, Graduate College for Engineers, BUPT


# 💻 Internships
- *2025.3 - 2025.8*, InfiX-ai, Guangdong, China.
<!--
- *2023.11 - 2025.1*, Huawei, 2012 Lab, Guangdong, China.
-->

# 📟 Reports
- [《他们，是闪闪发光的北邮人！》](https://mp.weixin.qq.com/s/-HP2uHssKdjbumYHcZyEMA)<br>
The Wechat official account of BUPT, with more than 11,000 visits.
- [《卓越风采录||学子说·王源毅：科研实践齐头并进》](https://mp.weixin.qq.com/s/jP7twFA9oUHcyJekh_SbHg)<br>
The Wechat official account of the Graduate College for Engineers, BUPT, with more than 1,000 visits
- [《2020-2021学年北京邮电大学 “青学之星”评选候选人介绍第一弹》](https://mp.weixin.qq.com/s/XUarXNwU8Hq31W65nEm_ew)<br>
The Wechat official account of the Student Affairs Office, BUPT, with more than 2,000 visits
- [《榜样在身边·“校十佳青学之星”获得者——王源毅》](https://mp.weixin.qq.com/s/JG6i1HwPSD--Xgmn9vrOgQ)<br>
The Wechat official account of the College of Science, BUPT

# 🏃 Hobbies
I used to be a member of BUPT’s varsity team and once *ranked 5th* in the amateur division for hammer throw in Beijing (首都高校田径联赛乙组链球第五). Beyond that, I enjoy playing basketball, table tennis, badminton, and muscle building — in fact, I’m passionate about most kinds of sports. These activities not only help me stay healthy and energized, but also bring me a sense of freedom that comes from pushing physical limits and embracing the joy of movement.
