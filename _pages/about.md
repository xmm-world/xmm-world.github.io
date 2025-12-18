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

I am an undergraduate researcher in **Computer Science** at the **University of Science and Technology of China (USTC)**.  
My research interests focus on **language agents**, **reinforcement learning**, and **computer-use agents**, with an emphasis on **multi-turn decision-making**, **agent robustness**, and **security**.

My recent work studies **preference optimization for language agents** and **black-box red-teaming of web-based agents**, aiming to improve the reliability and controllability of large language model–based agent systems in complex environments.

I am currently involved in research collaborations on **computer-use agents**, **LLM agent security**, and **reinforcement learning for language agents**.

My Google Scholar profile is available here:  
<a href='https://scholar.google.com/citations?user=YOUR_GOOGLE_SCHOLAR_ID'>
<strong><span id='total_cit'>Google Scholar</span></strong>
</a>
&nbsp;
<a href='https://scholar.google.com/citations?user=YOUR_GOOGLE_SCHOLAR_ID'>
<img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">
</a>

---

## 🔥 News
- *2025.04*: Started research on **computer-use agents** at XLANG Lab, HKU.
- *2024.12*: Completed a research project on **LLM agent security** with Secure Learning Lab (UIUC & UChicago).
- *2024.10*: Our work on **direct multi-turn preference optimization for language agents** was accepted to **EMNLP 2024 (Main Conference)**.

---

## 📝 Publications 

**Direct Multi-Turn Preference Optimization for Language Agents**  
Li Haoran*, **Xu Minmin***, Zhou Yichen, Chen Zixuan, Gao Wenhao  
*EMNLP 2024 (Main Conference)*  
[[PDF]](https://aclanthology.org/2024.emnlp-main.138.pdf) · [[Code]](https://github.com/swt-user/DMPO)

**AdvAgent: Controllable Blackbox Red-teaming on Web Agents**  
Sun Jiacheng, Liu Yutong, He Ziming, Peng Zeyu, Tang Lingbo, **Xu Minmin**, Qiu Han, Luo Bo  
*ICML 2025*  
[[Project Page]](https://ai-secure.github.io/AdvAgent/) · [[PDF]](https://arxiv.org/pdf/2410.17401) · [[Code]](https://github.com/AI-secure/AdvAgent)

---

## 🎖 Honors and Awards
- *2025*: USTC Fellowship (Level A)  
- *2024*: Outstanding Student Scholarship, USTC  
- *2023*: Outstanding Student Scholarship, USTC  
- *2022*: Outstanding Student Scholarship, USTC  

---

## 📖 Education
- *2021 – 2025*, **B.Eng. in Computer Science and Technology**,  
  University of Science and Technology of China (USTC).

---

## 💻 Research Experience
- *2025 – Present*, Research Assistant, **XLANG Lab, The University of Hong Kong**  
  Research on **computer-use agents**.
- *2024*, Research Assistant, **Secure Learning Lab (UIUC & UChicago)**  
  Research on **LLM agent security and robustness**.
- *2023 – 2024*, Research Assistant, **Lab for Data Science, USTC**  
  Research on **reinforcement learning and language agents**.
