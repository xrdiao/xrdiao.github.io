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

I am a Master’s student in Electronic Information Engineering at SUSTech working on embodied intelligence and robotics. My research focuses on planning and control for autonomous robots, with an emphasis on navigation, manipulation, and learning-based decision making. I am interested in translating models and algorithms into efficient, reliable systems that can operate in complex real-world environments.

My current work spans graph-based motion planning, map-free multi-agent navigation with LiDAR and lightweight reinforcement learning, socially aware crowd navigation with uncertainty-aware risk adaptation, and contact-rich manipulation. Across these topics, I study how learning, uncertainty estimation, and optimization can be combined to improve robot safety, efficiency, and generalization. My citation statistics are updated automatically from Google Scholar below, with a current snapshot of <span id='total_cit'>48</span> total citations.

<!-- <a href='https://scholar.google.com/citations?user=kX-y4IoAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. -->


# 🔥 News
- *2026.08*: 🎉 LSTP-Nav was accepted by IEEE Transactions on Automation Science and Engineering ([paper](https://doi.org/10.1109/TASE.2026.3725345)).
- *2026*: 🎉 Socially Aware Robot Crowd Navigation via Online Uncertainty-Driven Risk Adaptation was published in IEEE Transactions on Systems, Man, and Cybernetics: Systems ([paper](https://doi.org/10.1109/TSMC.2026.3720408)).
- *2024*: 🎉 Graph neural network-based method for robot path planning was published in Biomimetic Intelligence and Robotics ([paper](https://doi.org/10.1016/j.birob.2024.100147), [code](https://github.com/xrdiao/GNN-based-method-for-robot-path-planning)).
- *2023.09*: 🎉🎉 Join the rπ Club.

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/flip_bunny.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Simultaneous Contact Selection and Planning for Contact-Rich Manipulation with Cascaded Optimization

Zhe Zhang\*, **Xingrong Diao**\*, Haoxiang Liang, Han Yang, Bi-Ke Zhu, Dandan Zhang, Jiankun Wang

[**Project**](https://sites.google.com/view/scsp-robot/) <strong><span class='show_paper_citations' data='kX-y4IoAAAAJ:UeHWp8X0CEIC'></span></strong>
- This project developed a cascaded optimization framework for contact-rich manipulation, including contact selection and contact planning modules, to enable efficient contact reasoning and trajectory generation for complex object geometries.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TASE 2026</div><img src='images/LSTP.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LSTP-Nav: Lightweight Spatiotemporal Policy for Map-free Multi-agent Navigation with LiDAR](https://doi.org/10.1109/TASE.2026.3725345)

**Xingrong Diao**, Zhirui Sun, Jianwei Peng, Bi-Ke Zhu, Baozhi Jia, Jiankun Wang

[**Project**](https://sites.google.com/view/lstp-net/) <strong><span class='show_paper_citations' data='kX-y4IoAAAAJ:u-x6o8ySG0sC'></span></strong>
- This project proposed LSTP-Nav, which uses a lightweight GRU-based policy with attention mechanisms and a novel HS reward for map-free multi-agent navigation using LiDAR, achieving a 9.58% higher success rate and 12.30% lower collision rate while maintaining real-time performance over 40 Hz on CPU-only platforms.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TSMC: Systems 2026</div><img src='images/social.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Socially Aware Robot Crowd Navigation via Online Uncertainty-Driven Risk Adaptation](https://doi.org/10.1109/TSMC.2026.3720408)

Zhirui Sun, **Xingrong Diao**, Yao Wang, Bi-Ke Zhu, Wenjun Xu, and Jiankun Wang

[**Project**](https://sites.google.com/view/lr-mpc/) <strong><span class='show_paper_citations' data='kX-y4IoAAAAJ:9yKSN-GCB0IC'></span></strong>

- This paper proposes Learning-Risk Model Predictive Control (LR-MPC), a novel algorithm for socially aware robot navigation in crowded environments. LR-MPC integrates a Probabilistic Ensemble Neural Network (PENN) with Model Predictive Control (MPC) to balance efficiency, safety, and social compliance. Two-Phase Framework: 1. Offline phase: A PENN model is trained on heuristic risk data from HR-MPC to predict navigation risks. 2. Online phase: Candidate waypoints are sampled using a Multi-RRT global planner, evaluated by PENN for risk, and filtered via epistemic and aleatoric uncertainty.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Biomimetic Intelligence and Robotics 2024</div><img src='images/GNN-based.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Graph neural network-based method for robot path planning](https://www.sciencedirect.com/science/article/pii/S2667379724000056)

**Xingrong Diao**, Wenzheng Chi, Jiankun Wang

[**Project**](https://github.com/xrdiao/GNN-based-method-for-robot-path-planning) <strong><span class='show_paper_citations' data='kX-y4IoAAAAJ:u5HHmVD_uO8C'></span></strong>

- The accompanying [implementation](https://github.com/xrdiao/GNN-based-method-for-robot-path-planning) includes training and evaluation code with a PyBullet simulator. The method reduces collision checks to 0.49% of PRM and 1.74% of RRT* in 7D environments, achieving a 62× speedup in planning time (0.193s vs. PRM's 12.02s) while maintaining a 98% success rate, though with slightly higher path costs. In 6D real-world tests, it cuts collision checks by 99.7% and planning time by 98.6% compared to baselines.
</div>
</div>

# 🎖 Honors and Awards
- *2025.10* National Scholarship. The highest honor for a master's student.
- *2023.10* SUSTech Graduate Academic Scholarship, Special Prize.
- *2022.07* MATE ROV World Championship. Global runner-up in the online division and champion of the mainland China division as a core member of the Glaucus team.

# 📖 Educations
- *2023.06 - 2026.01 (now)*, Southern University of Science and Technology (SUSTech), M.S., Department of Electrical and Electronic Engineering  
  Research focus: Robot Navigation and Manipulation
- *2019.09 - 2023.06*, Southern University of Science and Technology (SUSTech), B.E., Department of Mechanical and Energy Engineering  
  Key courses: Robot Modeling, CAD, Data Structures, and Algorithm Analysis

