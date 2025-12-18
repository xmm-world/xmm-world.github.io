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

I am a computer science researcher with primary interests in **language agents**, **reinforcement learning**, and **computer-use agents**.  
My current research focuses on building **robust, controllable, and interpretable agent systems** that can interact with complex environments such as web interfaces and real-world software tools.

I am particularly interested in **preference optimization**, **agent alignment and security**, and **scalable training strategies** for large language model–based agents, with an emphasis on **practical deployment and evaluation**.

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
- *2025.03*: &nbsp;Started a new research project on **computer-use agents and agent security**.
- *2024.10*: &nbsp;Our work on **preference optimization for language agents** was accepted by a top-tier NLP/ML venue.
- *2024.07*: &nbsp;Joined a collaborative project on **black-box red-teaming of web agents**.

---

## 📝 Publications 

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Under Review</div>
      <img src='images/500x300.png' alt="paper" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

**Hierarchical Preference Optimization for Multi-Turn Language Agents**

Author A*, Author B*, **Xu Minmin**

- Proposes a preference-based optimization framework for multi-turn agent interactions.
- Demonstrates improved robustness and reduced compounding errors in long-horizon agent trajectories.

</div>
</div>

- **Controllable Black-Box Attacks on Web Agents**, Author A, **Xu Minmin**, *In preparation*

---

## 🎖 Honors and Awards
- *2025*: USTC Fellowship (Level A)  
- *2024*: Outstanding Student Scholarship  
- *2023*: Outstanding Student Scholarship  

---

## 📖 Education
- *2021 – 2025*, B.Eng. in Computer Science and Technology, **University of Science and Technology of China**.
- *2024 – Present*, Visiting / Collaborative Research, focus on language agents and reinforcement learning.

---

## 💬 Talks & Presentations
- *2024*, Poster presentation on **preference optimization for language agents**, NLP/ML workshop.
- *2023*, Seminar talk on **reinforcement learning for LLM-based agents**.

---

## 💻 Research Experience
- *2025 – Present*, Research Assistant, **Language Agent Research Group**  
  Focus on computer-use agents and agent alignment.
- *2024*, Research Assistant, **Secure Learning Lab (collaborative project)**  
  Focus on LLM agent security and robustness.
