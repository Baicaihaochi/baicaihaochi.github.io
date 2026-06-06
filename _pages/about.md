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

- 🧪 <strong class="author-highlight">Shuo Cai</strong>, Yanggan Gu, Zihao Wang, Yuanyi Wang, Yibo Yan, Wenjun Wang, Yuhang Liu, Guanghao Zhu, Sirui Huang, Ming Li, Hongxia Yang. <em>From Parameters to Behaviors: A Survey of Model Fusion for Large Language Models.</em> In Preprints, 2026. 🔗[[Preprint]](https://www.preprints.org/manuscript/202605.2007) 💻[[Code]](https://github.com/Baicaihaochi/Awesome-Model-Fusion-Survey)<br>Contribution: Defines model fusion for LLMs and organizes the literature across parameter-, representation-, and behavior-level fusion. It provides a structured taxonomy, compares representative methods, and highlights evaluation settings, applications, challenges, and future directions.

- 🧪 <strong class="author-highlight">Yanggan Gu</strong>, <strong class="author-highlight">Shuo Cai (Co-1st)</strong>, Zihao Wang, Wenjun Wang, Yuanyi Wang, Pengkai Wang, Sirui Huang, Su Lu, Jianmin Wu, Hongxia Yang. <em>FeatCal: Feature Calibration for Post-Merging Models.</em> In arXiv 2026. 🔗[[Paper]](https://arxiv.org/abs/2605.13030) 💻[[Code]](https://github.com/egangu/featcal)<br>Contribution: Identifies feature drift as a key cause of performance degradation after model merging. It proposes layer-wise closed-form feature calibration using small calibration sets to repair merged models without expensive retraining.

- 🧪 Wenjun Wang, Yanggan Gu, <strong class="author-highlight">Shuo Cai (Co-1st)</strong>, Yuanyi Wang, Pengkai Wang, Jianmin Wu, Hongxia Yang. <em>E-PMQ: Expert-Guided Post-Merge Quantization with Merged-Weight Anchoring.</em> In arXiv 2026. 🔗[[Paper]](https://arxiv.org/abs/2605.16882) 💻[[Code]](https://github.com/wwjzhy/E-PMQ)<br>Contribution: Studies post-merge quantization, where quantization is applied after model merging rather than to individual source models. It introduces expert-guided targets and merged-weight anchoring to stabilize low-bit merged models and reduce quantization-induced capability loss.

- 🧪 Wenjun Wang, <strong class="author-highlight">Shuo Cai (Co-1st)</strong>, Congkai Xie, Mingfa Feng, Yiming Zhang, Zhen Li, Kejing Yang, Ming Li, Jiannong Cao, Hongxia Yang. <em>InfiR2: A Comprehensive FP8 Training Recipe for Reasoning-Enhanced Language Models.</em> In arXiv 2025. 🔗[[Paper]](https://arxiv.org/abs/2509.22536)<br>Contribution: Builds an end-to-end FP8 training recipe for reasoning-enhanced language models. It combines continual pre-training and supervised fine-tuning to improve training efficiency while preserving reasoning performance.

- 🧪 <strong class="author-highlight">Shuo Cai</strong>, Su Lu, Qi Zhou, Kejing Yang, Zhijie Sang, Congkai Xie, Hongxia Yang. <em>InfiAlign: A Scalable and Sample-Efficient Framework for Aligning LLMs to Enhance Reasoning Capabilities.</em> In arXiv 2025. 🔗[[PDF]](https://arxiv.org/pdf/2508.05496) 💻[[Code]](https://github.com/InfiXAI/InfiAlign)<br>Contribution: Proposes a scalable alignment framework that selects high-quality reasoning data through multidimensional criteria such as diversity, difficulty, and quality. It combines SFT and DPO to improve LLM reasoning while using substantially less training data.

- 🧪 Congkai Xie, <strong class="author-highlight">Shuo Cai (Co-1st)</strong>, Wenjun Wang, Pengxiang Li, Zhijie Sang, Kejing Yang, Yiming Zhang, Zhen Li, Guanghao Zhu, Zeyu Liu, Yang Yu, Yuhang Liu, Su Lu, Baoyi He, Qi Zhou, Xiaotian Han, Jianbo Yuan, Shengyu Zhang, Fei Wu, Hongxia Yang. <em>InfiR: Crafting Effective Small Language Models and Multimodal Small Language Models in Reasoning.</em> In arXiv 2025. 🔗[[PDF]](https://arxiv.org/pdf/2502.11573)<br>Contribution: Develops a low-cost training pipeline for small language models and multimodal small language models with strong reasoning ability. The work targets efficient deployment while maintaining competitive performance on reasoning tasks.

# 📖 Education
- *2025.09 - present*, Master of Philosophy, Department of Computing, The Hong Kong Polytechnic University.
- *2021.09 - 2025.06*, Undergraduate, Intelligent Science and Technology, School of Automation Science and Engineering, South China University of Technology.

# 💻 Internship
- *2025.06 - 2025.09*, Research Intern, [Infix.ai](https://infix-ai.com/), Shenzhen.
