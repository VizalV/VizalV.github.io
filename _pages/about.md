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

I am a Machine Learning Research Engineer at [Salesforce AI Research](https://www.salesforceairesearch.com/) / [Rutgers University](https://www.rutgers.edu/), where I completed my M.S. in Computer Science. I build the systems my own research runs on: the training pipelines, evaluation frameworks, and inference servers behind my results are ones I built, cutting training token usage up to 10x and judge overhead 2.7x while lifting accuracy up to 8%.

My research interests include LLM post-training, reward modeling, and the reasoning and evaluation of multi-agent systems. I am first author of an ICML 2026 paper on process verification for multi-agent systems, and a co-author of a NeurIPS 2026 submission on reward modeling for multi-agent orchestration. You can find my papers on <a href='https://scholar.google.com/citations?user=sZfwZwcAAAAJ'>Google Scholar</a> <a href='https://scholar.google.com/citations?user=sZfwZwcAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


# 🔥 News
- *2026.06*: &nbsp;📄 [Reward Modeling for Multi-Agent Orchestration](https://arxiv.org/abs/2606.13598) is on arXiv and under review at NeurIPS 2026.
- *2026.05*: &nbsp;🎉🎉 [MAS-ProVe](https://openreview.net/forum?id=UoM3G7nKr0) is accepted to **ICML 2026**!
- *2026.05*: &nbsp;🎓 Completed my M.S. in Computer Science at Rutgers University.
- *2025.06*: &nbsp;Joined Salesforce AI Research / Rutgers University as a Machine Learning Research Engineer.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MAS-ProVe: Understanding the Process Verification of Multi-Agent Systems](https://openreview.net/forum?id=UoM3G7nKr0)

**Vishal Venkataramani**, H. Shi, Z. Ke, A. Xu, X. He, Y. Zhou, S. Yavuz, H. Wang, S. Joty

[**Paper**](https://openreview.net/forum?id=UoM3G7nKr0) \| [**Code**](https://github.com/Wang-ML-Lab/MAS-ProVe)
- Benchmarks generative judges against specialized process and outcome reward models across six multi-agent architectures on AIME and GAIA.
- Finds generative judges stronger in most settings, with verification valuable primarily as variance reduction.
</div>
</div>

- [Reward Modeling for Multi-Agent Orchestration](https://arxiv.org/abs/2606.13598), K. Y. Tsang, Z. Zhao, **Vishal Venkataramani**, H. Shi, Z. Ke, S. Yavuz, S. Joty, H. Wang, **NeurIPS 2026 (under review)**

# 🎖 Honors and Awards
- 2x Excellent Teaching Assistant Award, Rutgers University.
- Merit Scholarship, SSN College of Engineering.

# 📖 Educations
- *2024.09 - 2026.05*, M.S. in Computer Science, Rutgers University. GPA 3.95/4.0.
- *2020.09 - 2024.05*, B.E. in Computer Science, SSN College of Engineering, Anna University. GPA 9.18/10.

# 💻 Experience
- *2025.06 - now*, Machine Learning Research Engineer, [Salesforce AI Research](https://www.salesforceairesearch.com/) / [Rutgers University](https://www.rutgers.edu/). LLM post-training, reward modeling, and evaluation of multi-agent systems.
- *2024.01 - 2024.06*, Research Intern (Computer Vision), [IIIT-Hyderabad](https://www.iiit.ac.in/), India. Zero-shot GroundingDINO labeling cut annotation effort 40%; fine-tuned YOLOv8 to 60 ms per-frame inference on an NVIDIA Jetson Nano.

# 🚀 Projects
- *2026*, **Poké-Copilot**. A real-time strategy copilot spanning a Chrome extension, a FastAPI websocket backend, a Bayesian predictor sidecar, and a self-hosted vLLM server, streaming analysis in 130-1200 ms per turn.
- *2026*, **[FineSurE-Ext](https://github.com/VizalV/FineSurE-Ext)**. Extends an ACL'24 factuality-evaluation framework to any backend through centralized model routing across Qwen, Llama, and GPT-4.
- *2025*, **LLM Curriculum, Rutgers CS439**. An open-sourced fine-tuning and agentic-workflow module with annotated notebooks and the OpenAI Agents SDK, delivered to 200+ students.
