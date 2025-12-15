---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a final-year undergraduate student majoring in Software Engineering at the **Beijing Institute of Technology (BIT)**. I am an incoming Ph.D. student at the **Shenzhen International Graduate School, Tsinghua University**(THU SIGS), starting in 2026, advised by [Prof. Xiaozhi Wang](https://bakser.github.io/).

My research interests broadly lie in Trustworthy AI and Reinforcement Learning. Specifically, I focus on:
*   **LLM Safety & Alignment:** Building efficient and safe AI systems based on Large Language Models.
*   **Reinforcement Learning:** Exploring efficient RL methods for LLMs based on verifiable rewards(**RLVR**).

I have been fortunate to gain extensive research experience during my undergraduate studies. I was a research intern at the **State Key Laboratory of AI Safety, Institute of Computing Technology, Chinese Academy of Sciences (ICT, CAS)**, advised by [Prof. Shengyu Zhu](https://zhushyu.github.io/). During this internship, I proposed *Speculative Safety-Aware Decoding (SSD)*, a novel decoding-time defense mechanism, which was accepted to the **EMNLP 2025 Main Conference** as a **first-author** paper ([Paper PDF](/files/EMNLP2025_SSD.pdf)).

Before focusing on Safety-Aware Decoding, I researched defensive mechanisms in Federated Learning advised by [Prof. Jinyan Liu](https://cs.bit.edu.cn/szdw/jsml2/rjznyrjgcyjs2/680a2f55144449cfba0b807317c3cea3.htm), with one paper currently under review. I also worked on LLM Evaluation with [Prof. Yang Song](https://people.uncw.edu/songy/) (UNCW), where we developed evaluation metrics for RAG-based chatbots, leading to a co-first author paper accepted by ICBAIE 2024.

Beyond research, I am a competitive programmer with a strong interest in algorithms. I have won the **Silver Medal** in the **ACM-ICPC Regional Contest** and the Silver Medal in the CCPC National Invitational Contest. 

***

### 📄 Vita
You can find my detailed **Curriculum Vitae** [here](/files/resume.pdf).

### 🧾 Selected Publications
{% assign pubs = site.publications | sort: 'date' | reverse %}
{% if pubs and pubs.size > 0 %}
{% for post in pubs limit:3 %}
- **{{ post.title }}**, *{{ post.venue }}* ({{ post.date | date: "%Y" }})  
  {% if post.paperurl %}[PDF]({{ post.paperurl }}){% endif %}{% if post.paperurl and post.link %} · {% endif %}{% if post.link %}[Project / Code]({{ post.link }}){% endif %}
{% endfor %}
{% else %}
No publications listed yet. Please check back later.
{% endif %}

### 💻 Code & Projects
My [GitHub](https://github.com/k-k1w-w1x-x) contains source code for my research projects and coursework. 
*   **[Speculative Safety-Aware Decoding](https://github.com/k-k1w-w1x-x/Speculative-Safety-Aware-Decoding):** Official implementation of my EMNLP 2025 paper.
*   **[Improved A3C with Bandit Models](https://github.com/k-k1w-w1x-x/RL-A3C):** A course project for *Reinforcement Learning* at BIT (received full marks), exploring strategy improvements for A3C.
*   *Note: Some interesting repositories are currently private as I am organizing documentation and cleaning up the codebases.*

### 📝 Blogs
I maintain a [personal blog](https://www.cnblogs.com/WXk-k) (in Chinese) where I document my learning journey in algorithms, competitive programming, and system design.

### ✉️ Contact
If you are interested in my research or would like to request paper preprints, please feel free to email me at [wangxk0223@gmail.com](mailto:wangxk0223@gmail.com).