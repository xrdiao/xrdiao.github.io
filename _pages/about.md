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

<div class='homepage-hero'>
  <h1 class='homepage-hero__focus'>Humanoid Robotics · Reinforcement Learning · Whole-Body Control</h1>
  <p class='homepage-hero__intro'>I received my M.S. in Electronic Information Engineering from SUSTech in 2026.</p>
  <p class='homepage-hero__intro'>I work on learning-based whole-body control for humanoid robots, particularly contact-rich interaction and task-conditioned behaviors, with broader interests in behavior foundation models and sim-to-real deployment.</p>
  <p class='homepage-hero__intro'>My previous research spans contact-rich manipulation, learning-based robot navigation, and motion planning.</p>
  <p class='homepage-hero__interests'><span>Research interests:</span> Humanoid Robot Learning · Contact-Rich Interaction · Behavior Foundation Models · Motion Planning · Sim-to-Real</p>
  <div class='homepage-stats' aria-label='Research statistics'>
    <div class='homepage-stat'>
      <strong id='publication_count'>—</strong>
      <span>Publications</span>
    </div>
    <a class='homepage-stat' href='https://scholar.google.com/citations?user=kX-y4IoAAAAJ'>
      <strong id='total_cit' aria-live='polite'>—</strong>
      <span>Citations</span>
    </a>
    <div class='homepage-stat'>
      <strong>1</strong>
      <span>Best Paper Award</span>
    </div>
  </div>
</div>

<!-- <a href='https://scholar.google.com/citations?user=kX-y4IoAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. -->


# 🔥 News
- *2026.08*: 🎉 LSTP-Nav was accepted by IEEE Transactions on Automation Science and Engineering ([paper](https://doi.org/10.1109/TASE.2026.3725345)).
- *2026*: 🎉 Socially Aware Robot Crowd Navigation via Online Uncertainty-Driven Risk Adaptation was published in IEEE Transactions on Systems, Man, and Cybernetics: Systems ([paper](https://doi.org/10.1109/TSMC.2026.3720408)).
- *2024*: 🎉 Graph neural network-based method for robot path planning was published in Biomimetic Intelligence and Robotics and received the BIRob Best Paper Award ([official announcement](https://sucro.sdu.edu.cn/zyqk/qkxw/8.htm), [award](https://mp.weixin.qq.com/s/IoKwl7eMIs89X9MaRSwwnw), [paper](https://doi.org/10.1016/j.birob.2024.100147), [code](https://github.com/xrdiao/GNN-based-method-for-robot-path-planning)).
- *2023.09*: 🎉🎉 Join the rπ Club.

# 💼 Experience
- *2026.04 - 2026.06* · Robotics Algorithm Intern, [Ruiwei Technology (Xiamen Ruiwei Information Technology Co., Ltd.)](https://www.worldrobotconference.com/expo/company/786.html). Developed backpack-grasping algorithms for the airport luggage-transfer robot project; the system was demonstrated at the [2026 World Robot Conference](https://www.worldrobotconference.com/).

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/flip_bunny.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Simultaneous Contact Selection and Planning for Contact-Rich Manipulation with Cascaded Optimization

Zhe Zhang\*, **Xingrong Diao**\*, Haoxiang Liang, Han Yang, Bi-Ke Zhu, Dandan Zhang, Jiankun Wang

[**Project**](https://sites.google.com/view/scsp-robot/) <strong><span class='show_paper_citations' data='kX-y4IoAAAAJ:UeHWp8X0CEIC'></span></strong>
- A cascaded optimization framework jointly handles contact selection and contact planning for contact-rich manipulation. It enables efficient contact reasoning and trajectory generation for objects with complex geometries.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TASE 2026</div><img src='images/LSTP.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LSTP-Nav: Lightweight Spatiotemporal Policy for Map-free Multi-agent Navigation with LiDAR](https://doi.org/10.1109/TASE.2026.3725345)

**Xingrong Diao**, Zhirui Sun, Jianwei Peng, Bi-Ke Zhu, Baozhi Jia, Jiankun Wang

[**Project**](https://sites.google.com/view/lstp-net/) <strong><span class='show_paper_citations' data='kX-y4IoAAAAJ:u-x6o8ySG0sC'></span></strong>
- LSTP-Nav combines a lightweight GRU policy with attention and a novel HS reward for map-free multi-agent navigation using LiDAR. It reports higher success and lower collision rates while maintaining real-time performance above 40 Hz on CPU-only platforms.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TSMC: Systems 2026</div><img src='images/social.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Socially Aware Robot Crowd Navigation via Online Uncertainty-Driven Risk Adaptation](https://doi.org/10.1109/TSMC.2026.3720408)

Zhirui Sun, **Xingrong Diao**, Yao Wang, Bi-Ke Zhu, Wenjun Xu, and Jiankun Wang

[**Project**](https://sites.google.com/view/lr-mpc/) <strong><span class='show_paper_citations' data='kX-y4IoAAAAJ:9yKSN-GCB0IC'></span></strong>

- LR-MPC combines a probabilistic ensemble neural network with model predictive control to adapt navigation risk in crowded environments. It learns risk offline and uses uncertainty-aware waypoint evaluation online to balance efficiency, safety, and social compliance.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Biomimetic Intelligence and Robotics 2024 · BIRob Best Paper Award</div><img src='images/GNN-based.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Graph neural network-based method for robot path planning](https://www.sciencedirect.com/science/article/pii/S2667379724000056)

**Xingrong Diao**, Wenzheng Chi, Jiankun Wang

[**Project**](https://github.com/xrdiao/GNN-based-method-for-robot-path-planning) <strong><span class='show_paper_citations' data='kX-y4IoAAAAJ:u5HHmVD_uO8C'></span></strong>

- The project provides training and evaluation code with a PyBullet simulator for graph neural network-guided sampling-based path planning. Achieved 62× faster planning with a 98% success rate in simulation on a 7-DoF robot arm, and significantly reduced collision checks and planning time in real-world tests on a 6-DoF robot arm.
</div>
</div>

# 🎖 Honors and Awards
- *2025.10* National Scholarship (China), a competitive scholarship awarded to outstanding master's students.
- *2023.10* SUSTech Graduate Academic Scholarship, Special Prize.
- *2022.07* MATE ROV World Championship. Served as a core member of the Glaucus team, achieving 2nd place globally in the online division and 1st place in the mainland China division.

# 🤝 Academic Service
<span class='anchor' id='academic-service'></span>
- Journal Reviewer: IEEE Transactions on Automation Science and Engineering (T-ASE).
- Journal Reviewer: Biomimetic Intelligence and Robotics.
- Conference Reviewer: IEEE International Conference on Robotics and Automation (ICRA).

# 📖 Education
<span class='anchor' id='-educations'></span>
- *2023.09 - 2026.07*, Southern University of Science and Technology (SUSTech), M.S., Department of Electrical and Electronic Engineering<br>
  Research focus: Robot Navigation and Manipulation
- *2019.09 - 2023.06*, Southern University of Science and Technology (SUSTech), B.E., Department of Mechanical and Energy Engineering<br>
  Key courses: Robot Modeling, CAD, Data Structures, and Algorithm Analysis
