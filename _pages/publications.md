---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<ol>
  <li>
    <Strong>Xiao Han</Strong>, Dingxuan Zhou, Guojiang Shen, Xiangjie Kong, Yulong Zhao,
    Deep Trajectory Recovery Approach of Offline Vehicles in the Internet of Vehicles,
    <em>IEEE Transactions on Vehicular Technology</em>.
    <a target="_blank" rel="noopener" href="https://ieeexplore.ieee.org/document/10586793">[PDF]</a>
  </li>
  <li>
    <Strong>Xiao Han</Strong>, Chen Zhu, Xiao Hu, Chuan Qin, Xiangyu Zhao, and Hengshu Zhu,
    Adapting Job Recommendations to User Preference Drift with Behavioral-Semantic Fusion Learning,
    <em>The 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD’24), Research Track</em>.
    <a target="_blank" rel="noopener" href="https://arxiv.org/pdf/2407.00082">[PDF]</a>
  </li>
  <li>
    <Strong>Xiao Han</Strong>, Xiangyu Zhao, Liang Zhang, and Wanyu Wang,
    Mitigating action hysteresis in traffic signal control with traffic predictive reinforcement learning,
    <em>The 29th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD’23), Research Track</em>.
    <a target="_blank" rel="noopener" href="https://dl.acm.org/doi/abs/10.1145/3580305.3599528">[PDF]</a>
  </li>
  <li>
    <Strong>Xiao Han</Strong>, Guojiang Shen, Xi Yang, and Xiangjie Kong,
    Congestion Recognition for Hybrid Urban Road System via Digraph Convolutional Network,
    <em>Transportation Research Part C: Emerging Technologies</em>.
    <a target="_blank" rel="noopener" href="https://www.researchgate.net/profile/Xiangjie-Kong-2/publication/347696366_Congestion_recognition_for_hybrid_urban_road_systems_via_digraph_convolutional_network/links/617cef433c987366c30419d2/Congestion-recognition-for-hybrid-urban-road-systems-via-digraph-convolutional-network.pdf">[PDF]</a>
  </li>
</ol>
