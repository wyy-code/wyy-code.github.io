---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

# 👋 About Me

I am a Ph.D. student at The Hong Kong Polytechnic University (PolyU), advised by [Prof. Hongxia Yang](https://www4.comp.polyu.edu.hk/~hongxyang/).

My research centers on **model fusion**: combining trained models from different domains, architectures, or datasets into a single stronger model that aggregates complementary knowledge and improves performance, generalization, and efficiency. More broadly, I am interested in large language models, multimodal learning, and knowledge graphs.

Before joining PolyU, I received my B.S. from the College of Science at Beijing University of Posts and Telecommunications (BUPT), and was recommended for postgraduate study at the State Key Laboratory of Networking and Switching Technology, BUPT.

I am also a research intern at [InfiX-AI](https://infix-ai.com/). Our models and resources are available on [Hugging Face](https://huggingface.co/InfiX-ai).

# 🔥 News

- **May 2026** — Our paper *Model Merging Scaling Laws in Large Language Models* was accepted to ICML 2026.
- **2025** — Two papers on LLM fusion were accepted to NeurIPS 2025.
- **2025** — Our model InfiGFusion-14B was released on Hugging Face and received 4K+ stars.
- **2024** — Our paper on multi-modal entity alignment was selected as a Best Paper Candidate at ICMR 2024.

# 📝 Publications

<style>
:root {
  --pub-ink: #1f2937;
  --pub-muted: #5f6b7a;
  --pub-border: #e6eaf2;
  --pub-card: #ffffff;
  --pub-card-soft: #f8fbff;
  --pub-blue: #2f6fdf;
  --pub-blue-soft: #eaf2ff;
  --pub-gold: #9a6700;
  --pub-gold-soft: #fff6d7;
  --pub-red: #a33a3a;
  --pub-red-soft: #fff0f0;
}

.pub-nav {
  display: inline-flex;
  align-items: center;
  gap: 0.42rem;
  margin: 0.25rem 0 1.35rem 0;
  padding: 0.36rem 0.62rem;
  border: 1px solid var(--pub-border);
  border-radius: 999px;
  background: #fbfcff;
  color: var(--pub-muted);
  font-size: 0.88rem;
}

.pub-nav a {
  color: var(--pub-blue);
  font-weight: 700;
  text-decoration: none;
}

.pub-year {
  display: flex;
  align-items: center;
  gap: 0.65rem;
  margin-top: 1.85rem;
  margin-bottom: 0.85rem;
  color: var(--pub-ink);
  font-size: 1.38rem;
  letter-spacing: -0.01em;
}

.pub-year::after {
  content: "";
  height: 1px;
  flex: 1;
  background: linear-gradient(90deg, var(--pub-border), rgba(230, 234, 242, 0));
}

.pub-card {
  position: relative;
  margin: 0.82rem 0 1rem 0;
  padding: 0.9rem 1rem 0.86rem 1rem;
  border: 1px solid var(--pub-border);
  border-left: 4px solid #cfe0ff;
  border-radius: 14px;
  background: var(--pub-card);
  box-shadow: 0 8px 22px rgba(28, 44, 74, 0.045);
  line-height: 1.48;
  transition: transform 0.16s ease, box-shadow 0.16s ease, border-color 0.16s ease;
}

.pub-card:hover {
  transform: translateY(-1px);
  border-color: #d7e2f5;
  box-shadow: 0 12px 28px rgba(28, 44, 74, 0.075);
}

.pub-card.featured {
  border-left-color: var(--pub-blue);
  background: linear-gradient(180deg, var(--pub-card-soft), #ffffff 74%);
}

.pub-topline {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 0.38rem;
  margin-bottom: 0.34rem;
}

.pub-venue,
.pub-badge {
  display: inline-flex;
  align-items: center;
  border-radius: 999px;
  font-size: 0.72rem;
  font-weight: 760;
  letter-spacing: 0.01em;
  line-height: 1;
  padding: 0.34rem 0.52rem;
  white-space: nowrap;
}

.pub-venue {
  background: var(--pub-blue-soft);
  color: #1f4e8c;
}

.pub-venue.preprint {
  background: var(--pub-red-soft);
  color: var(--pub-red);
}

.pub-badge {
  background: #f3f5f8;
  color: #536070;
}

.pub-badge.highlight {
  background: var(--pub-gold-soft);
  color: var(--pub-gold);
}

.pub-title-row {
  display: flex;
  align-items: baseline;
  justify-content: space-between;
  gap: 0.8rem;
}

.pub-title {
  color: var(--pub-ink);
  font-size: 1.02rem;
  font-weight: 760;
  letter-spacing: -0.006em;
  text-decoration: none;
}

.pub-title:hover {
  color: var(--pub-blue);
  text-decoration: none;
}

.pub-authors {
  margin-top: 0.3rem;
  color: var(--pub-muted);
  font-size: 0.91rem;
}

.pub-authors strong {
  color: var(--pub-ink);
  font-weight: 760;
}

.pub-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.42rem;
  margin-top: 0.54rem;
}

.pub-links a {
  display: inline-flex;
  align-items: center;
  padding: 0.28rem 0.54rem;
  border: 1px solid var(--pub-border);
  border-radius: 999px;
  background: #fff;
  color: #315f9f;
  font-size: 0.78rem;
  font-weight: 720;
  text-decoration: none;
}

.pub-links a:hover {
  border-color: #bcd0f5;
  background: #f7fbff;
  text-decoration: none;
}

@media (max-width: 640px) {
  .pub-nav {
    display: flex;
    flex-wrap: wrap;
    border-radius: 12px;
  }

  .pub-card {
    padding: 0.82rem 0.86rem;
    border-radius: 12px;
  }

  .pub-title-row {
    display: block;
  }
}
</style>

<div class="pub-nav">
  <span>Years</span>
  <a href="#pub-2026">2026</a>
  <span>·</span>
  <a href="#pub-2025">2025</a>
  <span>·</span>
  <a href="#pub-2024">2024</a>
</div>

<h2 id="pub-2026" class="pub-year">2026</h2>

<div class="pub-card featured">
  <div class="pub-topline">
    <span class="pub-venue">ICML 2026</span>
    <span class="pub-badge highlight">Representative</span>
  </div>
  <div class="pub-title-row">
    <a class="pub-title" href="https://arxiv.org/pdf/2509.24244">Model Merging Scaling Laws in Large Language Models</a>
  </div>
  <div class="pub-authors">
    <strong>Yuanyi Wang</strong>, Yanggan Gu, Yiming Zhang, Qi Zhou, Zhaoyi Yan, Congkai Xie, Xinyao Wang, Jianbo Yuan, Hongxia Yang
  </div>
  <div class="pub-links">
    <a href="https://arxiv.org/pdf/2509.24244">Paper</a>
    <a href="https://github.com/InfiXAI/Merging-Scaling-Law">Code</a>
    <a href="https://huggingface.co/collections/InfiX-ai/scaling-law">Repo</a>
  </div>
</div>

<div class="pub-card">
  <div class="pub-topline">
    <span class="pub-venue">ICML 2026 Workshop</span>
  </div>
  <div class="pub-title-row">
    <a class="pub-title" href="https://arxiv.org/abs/2605.29489">Access Sets Matter: Budgeting Expert Reads for Scalable Weight-Space Model Merging</a>
  </div>
  <div class="pub-authors">
    <strong>Yuanyi Wang</strong>, Yanggan Gu, Su Lu, Yifan Yang, Zhaoyi Yan, Congkai Xie, Jianmin Wu, Hongxia Yang
  </div>
  <div class="pub-links">
    <a href="https://arxiv.org/abs/2605.29489">Paper</a>
    <a href="https://github.com/wyy-code/mergepipe">Code</a>
  </div>
</div>

<div class="pub-card featured">
  <div class="pub-topline">
    <span class="pub-venue preprint">arXiv</span>
    <span class="pub-badge highlight">Representative</span>
  </div>
  <div class="pub-title-row">
    <a class="pub-title" href="https://arxiv.org/abs/2605.26844">Not All Disagreement Is Learnable: Token Teachability in On-Policy Distillation</a>
  </div>
  <div class="pub-authors">
    <strong>Yuanyi Wang</strong>, Su Lu, Yanggan Gu, Pengkai Wang, Yifan Yang, Zhaoyi Yan, Congkai Xie, Jianmin Wu, Hongxia Yang
  </div>
  <div class="pub-links">
    <a href="https://arxiv.org/abs/2605.26844">Paper</a>
    <a href="https://github.com/wyy-code/TA-OPD">Code</a>
  </div>
</div>

<div class="pub-card featured">
  <div class="pub-topline">
    <span class="pub-venue preprint">arXiv</span>
    <span class="pub-badge highlight">Representative</span>
  </div>
  <div class="pub-title-row">
    <a class="pub-title" href="https://huggingface.co/papers/2605.09608">Geometry Conflict: Explaining and Controlling Forgetting in LLM Continual Post-Training</a>
  </div>
  <div class="pub-authors">
    <strong>Yuanyi Wang</strong>, Yifan Yang, Su Lu, Yanggan Gu, Pengkai Wang, Wenjun Wang, Zhaoyi Yan, Congkai Xie, Jianmin Wu, Jialun Cao, Shing-Chi Cheung, Hongxia Yang
  </div>
  <div class="pub-links">
    <a href="https://huggingface.co/papers/2605.09608">Paper</a>
    <a href="https://github.com/wyy-code/GCWM">Code</a>
  </div>
</div>

<div class="pub-card">
  <div class="pub-topline">
    <span class="pub-venue preprint">arXiv</span>
  </div>
  <div class="pub-title-row">
    <a class="pub-title" href="https://arxiv.org/pdf/2602.13273">MergePipe: A Budget-Aware Parameter Management System for Scalable LLM Merging</a>
  </div>
  <div class="pub-authors">
    <strong>Yuanyi Wang</strong>, Yanggan Gu, Zihao Wang, Kunxi Li, Yifan Yang, Zhaoyi Yan, Congkai Xie, Jianmin Wu, Hongxia Yang
  </div>
  <div class="pub-links">
    <a href="https://arxiv.org/pdf/2602.13273">Paper</a>
    <a href="https://github.com/wyy-code/mergepipe">Code</a>
  </div>
</div>

<div class="pub-card">
  <div class="pub-topline">
    <span class="pub-venue preprint">arXiv</span>
  </div>
  <div class="pub-title-row">
    <a class="pub-title" href="https://huggingface.co/papers/2605.13030">FeatCal: Feature Calibration for Post-Merging Models</a>
  </div>
  <div class="pub-authors">
    Yanggan Gu, Shuo Cai, Zihao Wang, Wenjun Wang, <strong>Yuanyi Wang</strong>, Pengkai Wang, Sirui Huang, Su Lu, Jianmin Wu, Hongxia Yang
  </div>
  <div class="pub-links">
    <a href="https://huggingface.co/papers/2605.13030">Paper</a>
    <a href="https://github.com/egangu/featcal">Code</a>
  </div>
</div>

<div class="pub-card">
  <div class="pub-topline">
    <span class="pub-venue preprint">arXiv</span>
  </div>
  <div class="pub-title-row">
    <a class="pub-title" href="https://arxiv.org/abs/2605.16882">E-PMQ: Expert-Guided Post-Merge Quantization with Merged-Weight Anchoring</a>
  </div>
  <div class="pub-authors">
    Wenjun Wang, Yanggan Gu, Shuo Cai, <strong>Yuanyi Wang</strong>, Pengkai Wang, Jianmin Wu, Hongxia Yang
  </div>
  <div class="pub-links">
    <a href="https://arxiv.org/abs/2605.16882">Paper</a>
    <a href="https://github.com/wwjzhy/E-PMQ">Code</a>
  </div>
</div>

<div class="pub-card">
  <div class="pub-topline">
    <span class="pub-venue preprint">arXiv</span>
    <span class="pub-badge">Co-first author</span>
  </div>
  <div class="pub-title-row">
    <a class="pub-title" href="https://arxiv.org/abs/2605.14546">Discovering Physical Directions in Weight Space: Composing Neural PDE Experts</a>
  </div>
  <div class="pub-authors">
    Pengkai Wang, Pengwei Liu, <strong>Yuanyi Wang</strong>, Guanyu Chen, Xingyu Ren, Xiaolong Li, Zhongkai Hao, Yuting Kong, Qixin Zhang, Dong Ni
  </div>
  <div class="pub-links">
    <a href="https://arxiv.org/abs/2605.14546">Paper</a>
  </div>
</div>

<h2 id="pub-2025" class="pub-year">2025</h2>

<div class="pub-card featured">
  <div class="pub-topline">
    <span class="pub-venue">NeurIPS 2025</span>
    <span class="pub-badge highlight">Representative</span>
  </div>
  <div class="pub-title-row">
    <a class="pub-title" href="https://arxiv.org/pdf/2505.13893">InfiGFusion: Graph-on-Logits Distillation via Efficient Gromov-Wasserstein for Model Fusion</a>
  </div>
  <div class="pub-authors">
    <strong>Yuanyi Wang</strong>, Zhaoyi Yan, Yiming Zhang, Qi Zhou, Yanggan Gu, Fei Wu, Hongxia Yang
  </div>
  <div class="pub-links">
    <a href="https://arxiv.org/pdf/2505.13893">Paper</a>
    <a href="https://huggingface.co/InfiX-ai/InfiGFusion-14B">Model</a>
  </div>
</div>

<div class="pub-card">
  <div class="pub-topline">
    <span class="pub-venue">NeurIPS 2025</span>
  </div>
  <div class="pub-title-row">
    <a class="pub-title" href="https://arxiv.org/pdf/2505.13878">InfiFPO: Implicit Model Fusion via Preference Optimization in Large Language Models</a>
  </div>
  <div class="pub-authors">
    Yanggan Gu, <strong>Yuanyi Wang</strong>, Zhaoyi Yan, Yiming Zhang, Qi Zhou, Fei Wu, Hongxia Yang
  </div>
  <div class="pub-links">
    <a href="https://arxiv.org/pdf/2505.13878">Paper</a>
    <a href="https://huggingface.co/InfiX-ai/InfiFPO-14B">Model</a>
  </div>
</div>

<div class="pub-card featured">
  <div class="pub-topline">
    <span class="pub-venue">NAACL 2025</span>
    <span class="pub-badge highlight">Representative</span>
  </div>
  <div class="pub-title-row">
    <a class="pub-title" href="https://arxiv.org/pdf/2401.12798">Rethinking Smoothness for Fast and Adaptable Entity Alignment Decoding</a>
  </div>
  <div class="pub-authors">
    <strong>Yuanyi Wang</strong>, Han Li, Haifeng Sun, Lei Zhang, Bo He, Wei Tang, Tianhao Yan, Qi Qi, Jingyu Wang
  </div>
  <div class="pub-links">
    <a href="https://arxiv.org/pdf/2401.12798">Paper</a>
    <a href="https://github.com/wyy-code/TFP">Code</a>
  </div>
</div>

<div class="pub-card">
  <div class="pub-topline">
    <span class="pub-venue">Nexus 2025</span>
  </div>
  <div class="pub-title-row">
    <a class="pub-title" href="https://www.cell.com/nexus/pdf/S2950-1601(25)00049-X.pdf">Democratizing AI Through Model Fusion: A Comprehensive Review and Future Directions</a>
  </div>
  <div class="pub-authors">
    Qi Zhou, Yiming Zhang, Yanggan Gu, <strong>Yuanyi Wang</strong>, Zhijie Sang, Zhaoyi Yan, Zhen Li, Shengyu Zhang, Fei Wu, Hongxia Yang
  </div>
  <div class="pub-links">
    <a href="https://www.cell.com/nexus/pdf/S2950-1601(25)00049-X.pdf">Paper</a>
  </div>
</div>

<div class="pub-card">
  <div class="pub-topline">
    <span class="pub-venue">TKDD</span>
  </div>
  <div class="pub-title-row">
    <a class="pub-title" href="https://arxiv.org/pdf/2402.03025">Understanding and Guiding Weakly Supervised Entity Alignment with Potential Isomorphism Propagation</a>
  </div>
  <div class="pub-authors">
    Haifeng Sun, <strong>Yuanyi Wang</strong>, Wei Tang, et al.
  </div>
  <div class="pub-links">
    <a href="https://arxiv.org/pdf/2402.03025">Paper</a>
    <a href="https://github.com/wyy-code/PipEA">Code</a>
  </div>
</div>

<h2 id="pub-2024" class="pub-year">2024</h2>

<div class="pub-card featured">
  <div class="pub-topline">
    <span class="pub-venue">ICDE 2024</span>
    <span class="pub-badge highlight">Representative</span>
  </div>
  <div class="pub-title-row">
    <a class="pub-title" href="https://arxiv.org/pdf/2401.17859">Towards Semantic Consistency: Dirichlet Energy Driven Robust Multi-Modal Entity Alignment</a>
  </div>
  <div class="pub-authors">
    <strong>Yuanyi Wang</strong>, Haifeng Sun, Jiabo Wang, Jingyu Wang, Wei Tang, Qi Qi, Shaoling Sun, Jianxin Liao
  </div>
  <div class="pub-links">
    <a href="https://arxiv.org/pdf/2401.17859">Paper</a>
    <a href="https://github.com/wyy-code/DESAlign">Code</a>
  </div>
</div>

<div class="pub-card">
  <div class="pub-topline">
    <span class="pub-venue">ICDM 2024</span>
  </div>
  <div class="pub-title-row">
    <a class="pub-title" href="https://arxiv.org/pdf/2410.08877">Interdependency Matters: Graph Alignment for Multivariate Time Series Anomaly Detection</a>
  </div>
  <div class="pub-authors">
    <strong>Yuanyi Wang</strong>, Haifeng Sun, Chengsen Wang, Mengde Zhu, Jingyu Wang, Wei Tang, Qi Qi, Zirui Zhuang, Jianxin Liao
  </div>
  <div class="pub-links">
    <a href="https://arxiv.org/pdf/2410.08877">Paper</a>
    <a href="https://github.com/wyy-code/MADGA">Code</a>
  </div>
</div>

<div class="pub-card featured">
  <div class="pub-topline">
    <span class="pub-venue">ICMR 2024</span>
    <span class="pub-badge highlight">Best Paper Candidate</span>
  </div>
  <div class="pub-title-row">
    <a class="pub-title" href="https://dl.acm.org/doi/10.1145/3652583.3658085">Multi-modal Entity Alignment via Position-enhanced Multi-label Propagation</a>
  </div>
  <div class="pub-authors">
    Wei Tang, <strong>Yuanyi Wang</strong>
  </div>
  <div class="pub-links">
    <a href="https://dl.acm.org/doi/10.1145/3652583.3658085">Paper</a>
    <a href="https://github.com/OceanTangWei/PMMEA">Code</a>
  </div>
</div>

<div class="pub-card">
  <div class="pub-topline">
    <span class="pub-venue">ICSE 2024</span>
  </div>
  <div class="pub-title-row">
    <a class="pub-title" href="https://dl.acm.org/doi/abs/10.1145/3639476.3639773">LogExpert: Log-based Recommended Resolutions Generation using Large Language Model</a>
  </div>
  <div class="pub-authors">
    Jiabo Wang, Guojun Chu, Jingyu Wang, Haifeng Sun, Qi Qi, <strong>Yuanyi Wang</strong>, Ji Qi, Jianxin Liao
  </div>
  <div class="pub-links">
    <a href="https://dl.acm.org/doi/abs/10.1145/3639476.3639773">Paper</a>
  </div>
</div>

# 🔬 Academic Service

- **Conference reviewer:** ICLR, NeurIPS, ICML, WWW, ACL
- **Journal reviewer:** SoftwareX, IEEE TNNLS

# 🎖 Honors and Awards

- **Jun. 2025** — Outstanding Thesis Award, Top 1%
- **Jun. 2025** — Outstanding Postgraduate of Beijing, Top 1%
- **Nov. 2024** — National Scholarship, Top 1%
- **Oct. 2024** — Outstanding Postgraduate, Top 5%
- **Sep. 2022** — Outstanding Graduate of Beijing, Top 5%
- **Dec. 2021** — Star of Youth Studies, awarded to 10 BUPT students each year
- **Sep. 2019 – Sep. 2021** — National Encouragement Scholarship, three times, Top 3%

# 📖 Education

- **Sep. 2025 – Present** — Ph.D., The Hong Kong Polytechnic University, Hong Kong
- **Sep. 2022 – Jun. 2025** — Postgraduate, State Key Laboratory of Networking and Switching Technology, BUPT, Beijing
- **Sep. 2018 – Jun. 2022** — B.S., Beijing University of Posts and Telecommunications, Beijing
- **Sep. 2015 – Jun. 2018** — Xi'an Tie Yi High School, Shaanxi


# 💻 Internships

- **Mar. 2025 – Present** — InfiX-AI, Guangdong, China
- **Nov. 2023 – Jan. 2025** — Huawei 2012 Lab, Guangdong, China

<!--
# 📟 Media & Reports

- [《他们，是闪闪发光的北邮人！》](https://mp.weixin.qq.com/s/-HP2uHssKdjbumYHcZyEMA)  
  Official WeChat account of BUPT, with 11,000+ visits.
- [《卓越风采录||学子说·王源毅：科研实践齐头并进》](https://mp.weixin.qq.com/s/jP7twFA9oUHcyJekh_SbHg)  
  Official WeChat account of the Graduate College for Engineers, BUPT, with 1,000+ visits.
- [《2020-2021学年北京邮电大学 “青学之星”评选候选人介绍第一弹》](https://mp.weixin.qq.com/s/XUarXNwU8Hq31W65nEm_ew)  
  Official WeChat account of the Student Affairs Office, BUPT, with 2,000+ visits.
- [《榜样在身边·“校十佳青学之星”获得者——王源毅》](https://mp.weixin.qq.com/s/JG6i1HwPSD--Xgmn9vrOgQ)  
  Official WeChat account of the College of Science, BUPT.
-->

# 🏃 Outside Research

I was a member of BUPT's varsity team and ranked 5th in the Beijing amateur division for hammer throw. I also enjoy basketball, table tennis, badminton, and strength training.
