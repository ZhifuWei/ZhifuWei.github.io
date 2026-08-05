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

I am an undergraduate student in Computer Science and Technology at [Northeastern University](https://www.neu.edu.cn/), advised by Prof. [Guibing Guo](https://guibingguo.github.io/). My research interests lie at the intersection of **large language models (LLMs)**, **AI agents**, and **recommender systems** — in particular, how LLMs can strengthen the representation of sparse (tail) items in sequential recommendation, and how multimodal agents can safely operate in real-world clinical workflows.

I am also collaborating with Prof. [Lequan Yu](https://yu-lab.github.io/) at The University of Hong Kong on benchmarking safety-aware computer-use agents in clinical workflows.

# 🔥 News
- *2026.01*: &nbsp;🎉 Our paper on tail-item sequential recommendation (**FAERec**) was accepted by **SIGIR 2026** as an oral presentation.
- *2026.01*: &nbsp;🎉 Received a full travel scholarship to attend the **AAAI-26 Undergraduate Consortium**.
- *2025.11*: &nbsp;🎉 Our paper on long-tail data augmentation (**TADA**) was accepted by **WWW 2026**.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 2026 (Oral)</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fusion and Alignment Enhancement with Large Language Models for Tail-item Sequential Recommendation](https://arxiv.org/abs/2604.03688)

**Zhifu Wei**, Yizhou Dang, Guibing Guo, Chuang Zhao, Zhu Sun

[**arXiv**](https://arxiv.org/abs/2604.03688)
- Proposed **FAERec** with dimension-wise adaptive gating to dynamically fuse collaborative ID embeddings with LLM-derived semantic representations, strengthening representations of tail items with sparse interaction histories.
- Developed dual-level alignment: item-level contrastive learning plus a feature-level Barlow Twins objective for structural consistency between embedding spaces.
- Designed a curriculum-learning strategy with cosine-annealed loss weights for progressive alignment.
- Achieved average gains of **86.64% in Hit@10** and **87.72% in NDCG@10** for tail-item recommendation with SASRec as the backbone.
</div>
</div>

- [TADA: Tail-Aware Data Augmentation for Long-Tail Sequential Recommendation](https://arxiv.org/abs/2601.10933), Yizhou Dang, **Zhifu Wei**, Minhan Huang, Lianbo Ma, Jianzhe Zhao, Guibing Guo, Xingwei Wang, **WWW 2026**
- A Realistic Benchmark for Multi-Interface Safety-Aware Computer-Use Agents in Clinical Workflows, Yushi Feng, **Zhifu Wei**, Ziyi He, Pui Hang Leung, Peixiang Huang, Yunhai Wang, Weifa Yang, Lequan Yu, *Manuscript in preparation*

# 🎖 Honors and Awards
- *2026.01*: &nbsp;Full Travel Scholarship, AAAI-26 Undergraduate Consortium (AAAI-UC)
- *2025.12*: &nbsp;National Encouragement Scholarship
- *2025.11*: &nbsp;First Prize (Liaoning Province), China Undergraduate Mathematical Contest in Modeling (CUMCM)
- *2025.05*: &nbsp;Honorable Mention, Mathematical Contest in Modeling (MCM)

# 📖 Educations
- *2023.09 - 2027.06 (now)*, B.E. in Computer Science and Technology, Northeastern University. GPA: 4.13/5.00 (top 9%, 20/213). CET-6: 516.

# 💼 Research Experience
- *2025.11 - 2026.01*, Research Assistant, advised by Prof. Guibing Guo, Northeastern University
  - **LLM-Enhanced Tail-Item Sequential Recommendation (FAERec)** — proposed adaptive gating for ID/semantic fusion, dual-level alignment, and curriculum learning; improved tail-item Hit@10 by 86.64% and NDCG@10 by 87.72%.
- *2025.08 - 2025.10*, Research Assistant, advised by Prof. Guibing Guo, Northeastern University
  - **Data Augmentation for Long-Tail Recommendation (TADA)** — designed lightweight linear item-item similarity, tail-aware T-Substitute/T-Insert operators, and cross-sequence mixup; improved Hit@10 by 30.4% (tail users) and 51.5% (tail items) on three Amazon datasets.
- *2026.02 - 2026.05*, Research Assistant, advised by Prof. Lequan Yu, The University of Hong Kong
  - **Computer-Use Agents in Clinical Workflows (OS-MedWorld)** — built a resettable clinical sandbox (OpenEMR, Orthanc, QuPath, 3D Slicer) with GUI/MCP/API/CLI interfaces; designed 180 clinically grounded tasks with executable evaluators; benchmarked frontier VLM agents on risk recognition and long-horizon execution.

# 💬 Invited Talks
- *2026.01*, Presented research at the AAAI-26 Undergraduate Consortium (supported by full travel scholarship).

# 🛠 Skills
- **Programming:** Python, C/C++, PyTorch, NumPy
- **Research & Engineering Tools:** Linux, Docker, Git, Overleaf
