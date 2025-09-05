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

Xiaolu Li received the B.Eng. degree in Computer Science and Technology from University of Science and Technology of China (USTC) in 2016, and the Ph.D. degree in Computer Science and Engineering from the Chinese University of Hong Kong (CUHK) in 2020. She was a postdoctoral researcher at the Chinese University of Hong Kong (CUHK) in 2020-2021. She is now a lecturer of the Department of Computer Science at Huazhong University of Science and Technology (HUST). Her research interests are in building reliable storage systems.

I'm looking for self-motivated students who are interested in distributed storage systems, coding theory including erasure codes and error correction codes, LSM Tree-based KV store, and hardware accelerator such as FPGA. If you are interested in these topics, please feel free to contact me.

We also welcome undergraduate students (year-2 or year-3) who are looking for research internship opportunities. If you want to get your hands dirty, please feel free to contact me. 

# 🔥 News
- *2025.09*: &nbsp;🎉🎉 One paper get accepted in ASP-DAC'26. 
- *2025.08*: &nbsp;🎉🎉 One paper get accepted in APSys'25. 
- *2025.06*: &nbsp;🎉🎉 One paper get accepted in FAST'26.
- *2025.03*: &nbsp;🎉🎉 One paper get accepted in TPDS'25.
- *2024.11*: &nbsp;🎉🎉 Invited to serve as a TPC member for FAST'26.
- *2024.06*: &nbsp;🎉🎉 Invited to give a talk on "parallel repair of MSR-coded storage" at Shandong University.
- *2024.06*: &nbsp;🎉🎉 Invited to serve as a TPC member for FAST'25.
- *2024.06*: &nbsp;🎉🎉 One paper get accepted in SRDS'24.
- *2023.12*: &nbsp;🎉🎉 One paper get accepted in FAST'24.
- *2022.12*: &nbsp;🎉🎉 One paper get accepted in TC'23. 
- *2022.12*: &nbsp;🎉🎉 One paper get accepted in InfoCom'23. 
- *2022.12*: &nbsp;🎉🎉 One paper get accepted in FAST'23. 
- *2022.02*: &nbsp;🎉🎉 One paper get accepted in TPDS'22. 

# 📝 Publications 

<!--div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div-->

**Conference**

- [LESS is More for I/O-Efficient Repairs in Erasure-Coded Storage](). Keyun Cheng, Guodong, Li, **Xiaolu Li**, Sihuang Hu, and Patrick P. C. Lee. FAST 2026 (CCF-A).
- [MASS: A Masking-aware Search Framework for Reliable QC-LDPC Code Construction in SSDs](). **Xiaolu Li**, Dingxin Wang, Zhengyao Ding, Jinye Wu, Qingnan Hu, Patrick P. C. Lee, Yuchong Hu, and Dan Feng. ASP-DAC 2026 (CCF-C).
- [HyperGen: Optimizing Generative Inference with Long Prompts for Resource-Constrainted Systems](). Lingwen Gong, Kaixin Liu, **Xiaolu Li**, Shujie Han, Patrick P. C. Lee, Yuchong Hu, and Dan Feng. APSys 2025 (workshop).
- [Harmonizing Repair and Maintenance in LRC-Coded Storage](). Keyun Cheng, Si Wu, **Xiaolu Li**, and Patrick P. C. Lee. SRDS 2024 (CCF-B).
- [ELECT: Enabling Erasure Coding Tiering for LSM-tree-based Storage](https://www.usenix.org/conference/fast24/presentation/ren). Yanjing Ren, Yuanming Ren, **Xiaolu Li**, Yuchong Hu, Jingwei Li, and Patrick P. C. Lee. USENIX FAST 2024 (CCF-A).
- [ParaRC: Embracing Sub-Packetization for Repair Parallelization in MSR-Coded Storage](https://www.usenix.org/conference/fast23/presentation/li-xiaolu). **Xiaolu Li**, Keyun Cheng, Kaicheng Tang, Patrick P. C. Lee, Yuchong Hu, Dan Feng, Jie Li, Ting-Yi Wu. USENIX FAST 2023 (CCF-A).
- [Balancing Repair Bandwidth and Sub-Packetization in Erasure-Coded Storage via Elastic Transformation](files/infocom23et.pdf). Kaicheng Tang, Keyun Cheng, Helen H. W. Chan, **Xiaolu Li**, Patrick P. C. Lee, Yuchong Hu, Jie Li, and Ting-Yi Wu. IEEE InfoCom 2023 (CCF-A).
- [Optimal Rack-Coordinated Updates in Erasure-Coded Data Centers](files/infocom21rackcu.pdf). Guowen Gong, Zhirong Shen, Suzhen Wu, **Xiaolu Li**, and Patrick P. C. Lee. IEEE InfoCom 2021 (CCF-A).
- [Fast Predictive Repair in Erasure-Coded Storage](files/dsn19fastpr.pdf). Zhirong Shen, **Xiaolu Li**, and Patrick P. C. Lee. IEEE/IFIP DSN 2019 (CCF-B).
- [OpenEC: Toward Unified and Configurable Erasure Coding Management in Distributed Storage Systems](https://www.usenix.org/conference/fast19/presentation/li). **Xiaolu Li**, Runhui Li, Patrick P. C. Lee, and Yuchong Hu. USENIX FAST 2019 (CCF-A).
- [Repair Pipelining for Erasure-Coded Storage](https://www.usenix.org/conference/atc17/technical-sessions/presentation/li-runhui). Runhui Li, **Xiaolu Li**, Patrick P. C. Lee, and Qun Huang. USENIX ATC 2017. (CCF-A).

**Journal**

- [Toward Load-Balanced Redundancy Transitioning for Erasure-Coded Storage](https://ieeexplore.ieee.org/document/10909584). Keyun Cheng, Huancheng Puyang, **Xiaolu Li**, Patrick P. C. Lee, Yuchong Hu, Jie Li, and Ting-Yi Wu. IEEE TPDS 2025 (CCF-A).
- [Optimal Rack-Coordinated Updates in Erasure-Coded Data Centers: Design and Analysis](files/tc23rackcu.pdf). Guowen Gong, Zhirong Shen, Liang Chen, Suzhen Wu, **Xiaolu Li**, Patrick P. C. Lee, Zhiguo Wan, and Jiwu Shu. IEEE TC 2023 (CCF-A).
- [Fast Proactive Repair in Erasure-Coded Storage: Analysis, Design, and Implementation](files/tpds22fastpr.pdf). **Xiaolu Li**, Keyun Cheng, Zhirong Shen, and Patrick P. C. Lee. IEEE TPDS 2022 (CCF-A).
- [Repair Pipelining for Erasure-Coded Storage: Algorithms and Evaluation](files/tos21rp.pdf). **Xiaolu Li**, Zuoru Yang, Jinhong Li, Runhui Li, Patrick P. C. Lee, Qun Huang, and Yuchong Hu. ACM TOS 2021 (CCF-A).
- [Optimal Repair Layering for Erasure-Coded Data Centers: From Theory to Practice.](files/tos17doubler.pdf). Yuchong Hu, **Xiaolu Li**, Mi Zhang, Patrick P. C. Lee, Xiaoyang Zhang, Pan Zhou, and Dan Feng. ACM TOS 2017 (CCF-A).

# 📖 Teaching
- *Spring*, 操作系统课程设计
- *Fall*, 操作系统原理
- *Fall*, 分布式存储系统设计与实践

# 🧑 Student
- Kaixin Liu, master 2025-now
- Zhengyu Liu, master 2025-now
- Lingwen Gong, master 2025-now
- Lei Wu, master 2023-2024, PhD 2024-now, Co-supervise with Prof. Yuchong Hu
- Mengjie He, master 2024-now
- Zongzhen, Yang, master 2024-now
- Qiwen Tan, master 2024-now
- Zhengyao Ding, master 2023-now, Co-supervise with Prof. Dan Feng
- Junlong Zhang, master 2023-now, Co-supervise with Prof. Dan Feng
- Dingxin Wang, master 2023-now
- Xuan Liu, master 2023-now

# 🧑 Alumni
- Han Yuan, master 2022-2025, Co-supervise with Prof. Dan Feng, first employment Jinshan (Wuhan)

# 🎉 Activities
- *PC Member* for FAST'26, FAST'25, ICA3PP'24, ICA3PP'23
- *AEC Member* for OSDI'22, ATC'22, FAST'24
- *Journal Reviewer* for TOS, and TON.

# 🎖 Honors
<!-- - *2023.03* PC for ICA3PP'23
- *2022.05* AEC for OSDI'22 and ATC'22 -->

# 💬 Invited Talks
<!-- - *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.--> 
- *2024.06*, Invited to give a talk on "parallel repair of MSR-coded storage" in Shandong University
