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

Hi! I am a third-year Ph.D. student of [AIoT Lab](https://aiot.ie.cuhk.edu.hk/), The Chinese University of Hong Kong ([CUHK](https://www.cuhk.edu.hk/english/index.html)), supervised by Prof. [Guoliang Xing](https://staff.ie.cuhk.edu.hk/~glxing/) and Prof. [Zhenyu Yan](https://yanzhenyu.com/). Prior to this, I received my Bachelor’s degree and Master's degree from Northwestern Polytechnical University ([NWPU](https://en.nwpu.edu.cn/)) and Nanjing University ([NJU](https://www.nju.edu.cn/en/)), respectively.

My current research interest mainly lies in LLMs and large foundational models, and their applications in mobile systems such as AR/VR, health, and assistive systems.

<span class='anchor' id='news'></span>

# 🔥 News
- *2025.01*: &nbsp; Our paper SocialMind has been accepted to [IMWUT 2025](https://www.ubicomp.org/ubicomp-iswc-2025/).
- *2025.01*: &nbsp; Our paper TaskSense is conditionally accepted to [SenSys 2025](https://sensys.acm.org/2025).
- *2024.11*: &nbsp; Our paper Soar has won Best Artifact Award Runner-up at [MobiCom 2024](https://www.sigmobile.org/mobicom/2024/).
- *2024.09*: &nbsp; Our paper DrHouse has been accepted to [IMWUT 2024](https://www.ubicomp.org/ubicomp-iswc-2025/).
- *2024.03*: &nbsp; Our paper VIAssist has been accepted to [FMSys 2024](https://fmsys24.github.io/).
- *2023.11*: &nbsp; Our paper Soar is conditionally accepted by [MobiCom 2024](https://www.sigmobile.org/mobicom/2024/).
- *2023.09*: &nbsp; Our paper EdgeFM has been accepted to [SenSys 2023](https://sensys.acm.org/2023).


<span class='anchor' id='publications'></span>
# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IMWUT/UbiComp 2025</div><img src='images/SocialMind.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

**SocialMind: LLM-based Proactive AR Social Assistive System with Human-like Perception for In-situ Live Interaction**

**<u>Bufang Yang</u>**, 
Yunqi Guo, 
Lilin Xu, 
Zhenyu Yan<sup>†</sup>
Hongkai Chen, 
Guoliang Xing, 
Xiaofan Jiang

Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (**IMWUT/UbiComp 2025**)

[[**Paper**](https://arxiv.org/pdf/2412.04036)]

We introduce *SocialMind*, an LLM-based proactive AR social assistive system that provides users with in-situ social assistance in live social interactions.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IMWUT/UbiComp 2025</div><img src='images/DrHouse.jpeg' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

**DrHouse: An LLM-empowered Diagnostic Reasoning System through Harnessing Outcomes from Sensor Data and Expert Knowledge**

**<u>Bufang Yang</u>**, 
Siyang Jiang, 
Lilin Xu, 
Kaiwei Liu, Hai Li, 
Guoliang Xing, 
Hongkai Chen, 
Xiaofan Jiang, 
Zhenyu Yan<sup>†</sup>

Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (**IMWUT/UbiComp 2025**)

[[**Paper**](https://dl.acm.org/doi/pdf/10.1145/3699765)]

We introduce *DrHouse*, an LLM-based diagnostic reasoning system that can leverage the sensor data on smart devices and the up-to-date expert knowledge for reliable multi-turn diagnosis.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SenSys 2023</div><img src='images/EdgeFM.jpeg' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

**EdgeFM: Leveraging Foundation Model for Open-set Learning on the Edge**

**<u>Bufang Yang</u>**, 
Lixing He, 
Neiwen Ling, 
Zhenyu Yan<sup>†</sup>, 
Guoliang Xing, 
Xian Shuai, 
Xiaozhe Ren, 
Xin Jiang

The 21th ACM Conference on Embedded Networked Sensor Systems, (**SenSys 2023**)

[[**Paper**](https://dl.acm.org/doi/pdf/10.1145/3625687.3625793)]

We introduce *EdgeFM*, a novel edge-cloud collaborative system with foundation models that enable open-set learning, simultaneously achieving both generalizability and efficiency for IoT applications.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SenSys 2025</div><img src='images/TaskSense.jpeg' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

**TaskSense: A Translation-like Approach for Tasking Heterogeneous Sensor Systems with LLMs**

Kaiwei Liu,
**<u>Bufang Yang</u>**, 
Lilin Xu,
Yunqi Guo,
Guoliang Xing, 
Xian Shuai, 
Xiaozhe Ren, 
Xin Jiang,
Zhenyu Yan<sup>†</sup> 

The 23rd ACM Conference on Embedded Networked Sensor Systems, (**SenSys 2025**)

[[**Paper**]()]

We introduce *TaskSense*, a novel system that coordinates multiple sensor systems in response to users' complex queries.

</div>
</div>

# 📝 Other Publications
- **VIAssist: Adapting Multi-modal Large Language Models for Users with Visual Impairments**

  **<u>Bufang Yang</u>**, Lixing He, Kaiwei Liu, Zhenyu Yan.

  *IEEE International Workshop on Foundation Models for Cyber-Physical Systems & Internet of Things, (**FMSys 2024**)*.

- **BrainZ-BP: A non-invasive Cuff-less Blood Pressure Estimation Approach Leveraging Brain Bio-impedance and Electrocardiogram**

  **<u>Bufang Yang</u>**, Le Liu, Wenxuan Wu, Mengliang Zhou, Hongxing Liu, Xinbao Ning. 

  *IEEE Transactions on Instrumentation and Measurement, (**TIM 2023**)*.

- **A Novel Sleep Stage Contextual Refinement Algorithm Leveraging Conditional Random Fields**

  **<u>Bufang Yang</u>**, Wenxuan Wu, Yitian Liu, Hongxing Liu. 

  *IEEE Transactions on Instrumentation and Measurement, (**TIM 2022**)*.

- **A single-channel EEG based automatic sleep stage classification method leveraging deep one-dimensional convolutional neural network and hidden Markov model**

  **<u>Bufang Yang</u>**, Xilin Zhu, Yitian Liu, Hongxing Liu. 

  *Biomedical Signal Processing and Control, (**BSPC 2021**)*.
  
- **Soar: Design and Deployment of A Smart Roadside Infrastructure System for Autonomous Driving**

  Shuyao Shi, Neiwen Ling, Zhehao Jiang, Xuan Huang, Yuze He, Xiaoguang Zhao, **<u>Bufang Yang</u>**, Chen Bian, Jingfei Xia, Zhenyu Yan, Raymond Yeung, Guoliang Xing. Soar: Design and Deployment of A Smart Roadside Infrastructure System for Autonomous Driving.

  *The 30th Annual International Conference On Mobile Computing And Networking, (**MobiCom 2024**)*

<span class='anchor' id='selected-awards'></span>
# Selected Awards
- Reaching Out Award, The Chinese University of Hong Kong, 2024
- Postgraduate Scholarship, The Chinese University of Hong Kong, 2022-2026
- National Scholarship for Postgraduates, Ministry of Education of China, 2021 and 2020
- Outstanding Graduate of Nanjing University, 2022

# Teaching Assistant
- IEMS5726A/IERG4320: Data Science in Practice, 2023 Fall, 2025 Spring, CUHK
- IEMS5727B: Internet of Things and Smart Applications, 2025 Spring, CUHK
- IERG3840: Web Application Development Project, 2022 Spring, 2023 Spring, CUHK
- IERG3080: Information and Software Engineering Practice, 2022 Fall, CUHK



