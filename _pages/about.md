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

Shuo Cai (蔡硕) is a Master of Philosophy student in the Department of Computing at The Hong Kong Polytechnic University (PolyU), supervised by Prof. Hongxia Yang. His research interests currently focus on model fusion and agentic tool use for Large Language Models (LLMs).



# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/InfiAlign.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

InfiAlign: A Scalable and Sample-Efficient Framework for Aligning LLMs to Enhance Reasoning Capabilities

<strong class="author-highlight">Shuo Cai</strong>, Su Lu, Qi Zhou, Kejing Yang, Zhijie Sang, Congkai Xie, Hongxia Yang

[**PDF**](https://arxiv.org/pdf/2508.05496) 

- This paper introduces InfiAlign, a scalable and sample-efficient post-training framework that enhances the reasoning capabilities of large language models while sharply reducing data and computational costs. Combining supervised fine-tuning (SFT) with Direct Preference Optimization (DPO), InfiAlign employs an automated data selection pipeline that curates high-quality alignment data from diverse open-source reasoning corpora using multi-dimensional metrics for diversity, difficulty, and quality. Applied to the Qwen2.5-Math-7B-Base model, it achieves performance on par with or surpassing leading distilled baselines such as R1-Distill-Qwen-7B, while using only 12% of their training data, showcasing that principled alignment strategies can deliver state-of-the-art results without prohibitive resource demands.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/Infir.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

InfiR: Crafting Effective Small Language Models and Multimodal Small Language Models in Reasoning

Congkai Xie, <strong class="author-highlight">Shuo Cai (Co-1st)</strong>, Wenjun Wang, Pengxiang Li, Zhijie Sang, Kejing Yang, Yiming Zhang, Zhen Li, Guanghao Zhu, Zeyu Liu, Yang Yu, Yuhang Liu, Su Lu, Baoyi He, Qi Zhou, Xiaotian Han, Jianbo Yuan, Shengyu Zhang, Fei Wu, Hongxia Yang

[**PDF**](https://arxiv.org/pdf/2502.11573) 

- This paper explores the development of efficient Small Language Models (SLMs) and Multimodal Small Language Models (MSLMs) that maintain strong reasoning abilities. It introduces an innovative training pipeline designed to enhance reasoning skills while enabling easy deployment on edge devices. The proposed approach achieves SoTA performance while keeping development costs low. InfR aims to improve AI systems by strengthening reasoning capabilities, lowering adoption barriers, and addressing privacy concerns through compact model sizes.

</div>
</div>

- 🧪 <strong class="author-highlight">Shuo Cai</strong>, Yanggan Gu, Zihao Wang, Yuanyi Wang, Yibo Yan, Wenjun Wang, Yuhang Liu, Guanghao Zhu, Sirui Huang, Ming Li, Hongxia Yang. <em>From Parameters to Behaviors: A Survey of Model Fusion for Large Language Models.</em> In Preprints, 2026. 🔗[[Preprint]](https://www.preprints.org/manuscript/202605.2007)

- 🧪 <strong class="author-highlight">Yanggan Gu</strong>, <strong class="author-highlight">Shuo Cai (Co-1st)</strong>, Zihao Wang, Wenjun Wang, Yuanyi Wang, Pengkai Wang, Sirui Huang, Su Lu, Jianmin Wu, Hongxia Yang. <em>FeatCal: Feature Calibration for Post-Merging Models.</em> In arXiv 2026. 🔗[[Paper]](https://arxiv.org/abs/2605.13030) 💻[[Code]](https://github.com/egangu/featcal)

- 🧪 Wenjun Wang, <strong class="author-highlight">Yanggan Gu (Co-1st)</strong>, <strong class="author-highlight">Shuo Cai (Co-1st)</strong>, Yuanyi Wang, Pengkai Wang, Jianmin Wu, Hongxia Yang. <em>E-PMQ: Expert-Guided Post-Merge Quantization with Merged-Weight Anchoring.</em> In arXiv 2026. 🔗[[Paper]](https://arxiv.org/abs/2605.16882) 💻[[Code]](https://github.com/wwjzhy/E-PMQ)

- 🧪 Wenjun Wang, <strong class="author-highlight">Shuo Cai (Co-1st)</strong>, Congkai Xie, Mingfa Feng, Yiming Zhang, Zhen Li, Kejing Yang, Ming Li, Jiannong Cao, Hongxia Yang. <em>InfiR2: A Comprehensive FP8 Training Recipe for Reasoning-Enhanced Language Models.</em> In arXiv 2025 (withdrawn). 🔗[[Paper]](https://arxiv.org/abs/2509.22536)

# 📖 Education
- *2025.09 - present*, Master of Philosophy, Department of Computing, The Hong Kong Polytechnic University.
- *2021.09 - 2025.06*, Undergraduate, Intelligent Science and Technology, School of Automation Science and Engineering, South China University of Technology.

# 💻 Internship
- *2025.06 - 2025.09*, Research Intern, [Infix.ai](https://infix-ai.com/), Shenzhen.
