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

I am a Master’s student in Electronic Information Engineering at SUSTech with a solid foundation in robotics and AI. My research focuses on path planning and multi-agent navigation. Having won national scholarships and robotics competition prizes, I am passionate about staying current with robotics and AI advancements, participating in hackathons, and engaging in interdisciplinary collaborations to develop innovative solutions to real-world automation challenges.

My research interest includes robot navigation and manipulation, reinforcement learning, and contact dynamics. I have published more than 3 papers at the top international conferences with total <a href='https://scholar.google.com/citations?user=kX-y4IoAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


# 🔥 News
- *2025.10*: &nbsp;🎉🎉 Join the xxx Club. 

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv 2024</div><img src='images/LSTP.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LSTP-Nav: Lightweight Spatiotemporal Policy for Map-free Multi-agent Navigation with LiDAR](https://arxiv.org/pdf/2408.16370)

**Xingrong Diao**, Zhirui Sun, Jianwei Peng, Bi'ke Zhu, Jiankun Wang

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This project proposed LSTP-Nav, which uses a lightweight GRU-based policy with attention mechanisms and a novel HS reward for map-free multi-agent navigation using LiDAR, achieving a 9.58% higher success rate and 12.30% lower collision rate while maintaining real-time performance over 40 Hz on CPU-only platforms.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv 2024</div><img src='images/social.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Socially Aware Robot Crowd Navigation via Online Uncertainty-Driven Risk Adaptation](https://arxiv.org/pdf/2506.14305)

Zhirui Sun, **Xingrong Diao**, Yao Wang, Bi-Ke Zhu, and Jiankun Wang,

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This paper proposes Learning-Risk Model Predictive Control (LR-MPC), a novel algorithm for socially aware robot navigation in crowded environments. LR-MPC integrates a Probabilistic Ensemble Neural Network (PENN) with Model Predictive Control (MPC) to balance efficiency, safety, and social compliance. Two-Phase Framework: 1. Offline phase: A PENN model is trained on heuristic risk data from HR-MPC to predict navigation risks. 2. Online phase: Candidate waypoints are sampled using a Multi-RRT global planner, evaluated by PENN for risk, and filtered via epistemic and aleatoric uncertainty.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Biomimetic Intelligence and Robotics 2024</div><img src='images/GNN-based.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Graph neural network-based method for robot path planning](https://www.sciencedirect.com/science/article/pii/S2667379724000056)

**Xingrong Diao**, Wenzheng Chi, Jiankun Wang

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- The proposed GNN-based path planning method reduces collision checks to 0.49% of PRM and 1.74% of RRT* in 7D environments, achieving a 62× speedup in planning time (0.193s vs. PRM's 12.02s) while maintaining a 98% success rate, though with slightly higher path costs. In 6D real-world tests, it cuts collision checks by 99.7% and planning time by 98.6% compared to baselines.
</div>
</div>

# 🎖 Honors and Awards
- *2025.10* National Scholarship. The highest honor for a master's student.
- *2022.07* Mate International Underwater Robot Competition. Second Prize in the Global Division, First Prize in the China Division. 

# 📖 Educations
- *2023.06 - 2026.01 (now)*, Southern University of Science and Technology (SUSTech), M.S., Department of Electrical and Electronic Engineering  
  Research focus: Robot Navigation and Manipulation
- *2019.09 - 2023.06*, Southern University of Science and Technology (SUSTech), B.E., Department of Mechanical and Energy Engineering  
  Key courses: Robot Modeling, CAD, Data Structures, and Algorithm Analysis

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
