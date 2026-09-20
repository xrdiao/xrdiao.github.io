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

I previously studied Electronic Information Engineering at SUSTech and work on robot learning and control. My current research focuses on reinforcement learning for humanoid whole-body control and contact-rich interaction, with interests in behavior foundation models, task-conditioned motion control, and sim-to-real deployment.

My previous research spans contact-rich manipulation, learning-based robot navigation, and motion planning.

# 🔬 Research
<span class='anchor' id='research'></span>

**Research interests:** Humanoid Robot Learning · Reinforcement Learning · Whole-Body Control · Contact-Rich Interaction · Motion Planning · Sim-to-Real

**Links:** [Email](mailto:12332163@mail.sustech.edu.cn) · [Google Scholar](https://scholar.google.com/citations?user=kX-y4IoAAAAJ) · [GitHub](https://github.com/xrdiao) · [DBLP](https://dblp.org/pid/358/2705.html) · [ORCID](https://orcid.org/0009-0001-9070-7450)
<small>Google Scholar citations: <span id='total_cit' aria-live='polite'>48</span></small>

<!-- <a href='https://scholar.google.com/citations?user=kX-y4IoAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. -->


# 🔥 News
- *2026.08*: 🎉 LSTP-Nav was accepted by IEEE Transactions on Automation Science and Engineering ([paper](https://doi.org/10.1109/TASE.2026.3725345)).
- *2026*: 🎉 Socially Aware Robot Crowd Navigation via Online Uncertainty-Driven Risk Adaptation was published in IEEE Transactions on Systems, Man, and Cybernetics: Systems ([paper](https://doi.org/10.1109/TSMC.2026.3720408)).
- *2024*: 🎉 Graph neural network-based method for robot path planning was published in Biomimetic Intelligence and Robotics and received the BIRob Best Paper Award ([official announcement](https://sucro.sdu.edu.cn/zyqk/qkxw/8.htm), [award photo](https://mp.weixin.qq.com/s/IoKwl7eMIs89X9MaRSwwnw), [paper](https://doi.org/10.1016/j.birob.2024.100147), [code](https://github.com/xrdiao/GNN-based-method-for-robot-path-planning)).
- *2023.09*: 🎉🎉 Join the rπ Club.

# 💼 Experience
- *2026.04 - 2026.06* · Robotics Algorithm Intern, [Ruiwei Technology (Xiamen Ruiwei Information Technology Co., Ltd.)](https://www.worldrobotconference.com/expo/company/786.html). Developed backpack-grasping algorithms for the airport luggage-transfer robot project; the system was demonstrated at the 2026 World Robot Conference.

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/flip_bunny.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Simultaneous Contact Selection and Planning for Contact-Rich Manipulation with Cascaded Optimization

Zhe Zhang\*, **Xingrong Diao**\*, Haoxiang Liang, Han Yang, Bi-Ke Zhu, Dandan Zhang, Jiankun Wang

[**Project**](https://sites.google.com/view/scsp-robot/) <strong><span class='show_paper_citations' data='kX-y4IoAAAAJ:UeHWp8X0CEIC'></span></strong>
- TL;DR: Cascaded optimization for contact selection and motion planning in contact-rich manipulation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TASE 2026</div><img src='images/LSTP.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LSTP-Nav: Lightweight Spatiotemporal Policy for Map-free Multi-agent Navigation with LiDAR](https://doi.org/10.1109/TASE.2026.3725345)

**Xingrong Diao**, Zhirui Sun, Jianwei Peng, Bi-Ke Zhu, Baozhi Jia, Jiankun Wang

[**Project**](https://sites.google.com/view/lstp-net/) <strong><span class='show_paper_citations' data='kX-y4IoAAAAJ:u-x6o8ySG0sC'></span></strong>
- TL;DR: Lightweight LiDAR-based policy for real-time map-free multi-agent navigation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TSMC: Systems 2026</div><img src='images/social.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Socially Aware Robot Crowd Navigation via Online Uncertainty-Driven Risk Adaptation](https://doi.org/10.1109/TSMC.2026.3720408)

Zhirui Sun, **Xingrong Diao**, Yao Wang, Bi-Ke Zhu, Wenjun Xu, and Jiankun Wang

[**Project**](https://sites.google.com/view/lr-mpc/) <strong><span class='show_paper_citations' data='kX-y4IoAAAAJ:9yKSN-GCB0IC'></span></strong>

- TL;DR: Uncertainty-aware risk adaptation with learning-based MPC for socially aware robot crowd navigation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Biomimetic Intelligence and Robotics 2024 · BIRob Best Paper Award</div><img src='images/GNN-based.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Graph neural network-based method for robot path planning](https://www.sciencedirect.com/science/article/pii/S2667379724000056)

**Xingrong Diao**, Wenzheng Chi, Jiankun Wang

[**Project**](https://github.com/xrdiao/GNN-based-method-for-robot-path-planning) <strong><span class='show_paper_citations' data='kX-y4IoAAAAJ:u5HHmVD_uO8C'></span></strong>

- TL;DR: Graph neural network guidance for sampling-based robot path planning with fewer collision checks.
</div>
</div>

# 🎖 Honors and Awards
- *2025.10* National Scholarship. The highest honor for a master's student.
- *2023.10* SUSTech Graduate Academic Scholarship, Special Prize.
- *2022.07* MATE ROV World Championship. Global runner-up in the online division and champion of the mainland China division as a core member of the Glaucus team.

# 📖 Education
<span class='anchor' id='-educations'></span>
- *2023.09 - 2026.07*, Southern University of Science and Technology (SUSTech), M.S., Department of Electrical and Electronic Engineering<br>
  Research focus: Robot Navigation and Manipulation
- *2019.09 - 2023.06*, Southern University of Science and Technology (SUSTech), B.E., Department of Mechanical and Energy Engineering<br>
  Key courses: Robot Modeling, CAD, Data Structures, and Algorithm Analysis

