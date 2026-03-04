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

Hello 👋, I'm Hongrui Jia (贾泓睿). I'm a second-year Master's student at Peking University, advised by Prof. Shikun Zhang and Prof. Wei Ye. My primary research interests lie in building reliable multimodal reasoning systems. I have published several papers at top-tier international AI conferences and journals with total   <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=google scholar citations"></a>). If you're interested in collaboration, feel free to reach out to me at jiahongrui@stu.pku.edu.cn.

# 📚 Educations
- *2024.09 - 2027.06*, MS, Software Engineering, Peking University.
- *2020.09 - 2024.06*, BS, Software Engineering, South China University of Technology. 

# 🔬 Research Interests

**Building reliable multimodal reasoning systems.**

My research focuses on improving the reliability of multimodal reasoning in large multimodal models and agents. My work investigates three closely connected directions: diagnosing failure modes in multimodal reasoning, enforcing reasoning processes grounded in reliable evidence, and enabling targeted capability improvement through diagnostic feedback. Together, these efforts aim to advance multimodal AI systems that can reason reliably in complex, open-world environments.

**Diagnosing Failure Modes in Multimodal Reasoning**

A key step toward reliable multimodal reasoning is understanding how and why models fail. Multimodal systems often exhibit hallucinations, reasoning drift, and failures in tool interaction, which can lead to unreliable reasoning outcomes. My work develops systematic evaluation frameworks and benchmarks to reveal these hidden weaknesses and to better understand the limits of current multimodal reasoning systems.

**Related works:** Hal-Eval (ACM MM 2024), OSWorld-MCP (ICLR 2026)

**Grounded Multimodal Reasoning**

Reliable reasoning requires that reasoning processes remain grounded in multimodal evidence rather than drifting toward purely textual patterns. My work studies mechanisms that strengthen the interaction between perception and reasoning, including improved multimodal representations and training strategies that encourage models to attend to visual evidence during reasoning.

**Related works:** MaVEn (NeurIPS 2024), SymDPO (CVPR 2025), Decoupled Reasoning and Perception

**Capability Improvement through Diagnostic Feedback**

Beyond diagnosing and correcting failures, I study how diagnostic insights can guide targeted model improvement. By linking failure analysis with data generation and training strategies, this line of work explores how multimodal reasoning systems can be iteratively improved to address their weaknesses and continually expand their reasoning capabilities.

**Related works:** Diagnostic-driven Progressive Evolution (DPE)

<!-- My research focuses on advancing trustworthy and capable Multimodal Large Language Models (MLLMs) through rigorous evaluation, targeted alignment, and diagnostic-driven training paradigms, with a commitment to building reliable, open-source multimodal intelligence systems.

This work follows a progressive research pipeline: systematically identifying critical failure modes in MLLM reasoning, comprehensively exploring the boundaries of multimodal reasoning capabilities.

**Systematic Evaluation of Critical Weaknesses in Reasoning.** The reliability of MLLM reasoning is constrained by fundamental bottlenecks: cognitive drift induced by hallucinations and structural deficiencies in tool-calling capabilities. Hallucinations not only introduce factual errors but also trigger cascading deviations throughout reasoning chains; insufficient tool invocation abilities fundamentally limit models' capacity for deep interaction with external knowledge sources and execution environments. How can we construct fine-grained evaluation frameworks to quantify these latent deficiencies? How might we establish comprehensive benchmarks covering visual consistency, tool coordination, and decision reliability?

Related Works: Hal-Eval (ACM MM 2024), OSWorld-MCP (ICLR 2026).

**Precision Enhancement and Dynamic Evolution of Reasoning Capabilities.** How can we compel models to genuinely "see" rather than merely "read" visual evidence during complex reasoning? How do we transcend the limitations of single-image understanding to achieve information integration and relational reasoning across multiple images? Within extended reasoning chains, what mechanisms can anchor visual grounding to prevent logical drift? Most critically, how can we translate diagnostic insights into real-time adjustments of data generation and training strategies, enabling continuous, targeted capability evolution?

Related Works: SymDPO (CVPR 2025), MaVEn (NeurIPS 2024), Decoupled Reasoning and Perception (Preprint), DPE (Preprint). -->


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/osworld-mcp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OSWORLD-MCP: BENCHMARKING MCP TOOL INVOCATION IN COMPUTER-USE AGENTS](https://arxiv.org/pdf/2510.24563)

**Hongrui Jia**, Jitong Liao, Xi Zhang, Haiyang Xu, Tianbao Xie, Chaoya Jiang, Ming Yan, Si Liu, Wei Ye, Fei Huang

[**Project**](https://osworld-mcp.github.io/) 
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2025.10* National Scholarship. 
- *2021.10* National Scholarship. 

<!-- #  💻 Internships
- *2025.06 - 2025.12*, Alibaba, Tongyi Group, Beijing.
- *2026.01 - Now*, JINGDONG, Hangzhou. -->
