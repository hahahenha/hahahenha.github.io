---
permalink: /
title: "Welcome to Xiao Han’s homepage"
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

<br>

Biography
======
I'm going to be an associate professor at [CSSC Lab](http://www.cssclab.cn/en) from Zhejiang University of Technology.
Before that, I was a postdoctoral research fellow at [AML Lab](https://aml-cityu.github.io/) from [City University of Hong Kong](https://www.cityu.edu.hk) supervised by Prof. [Xiangyu Zhao](https://zhaoxyai.github.io/).
I obtained the PhD degree in data science from [City University of Hong Kong](https://www.cityu.edu.hk) supervised by Prof. [Xiangyu Zhao](https://zhaoxyai.github.io/) and Prof. [Ding-Xuan Zhou](https://www.sydney.edu.au/science/about/our-people/academic-staff/dingxuan-zhou.html). 
I obtained the BSc and MSc degrees in computer science at [CSSC Lab](https://www.cssclab.cn/) from [Zhejiang University of Technology (ZJUT)](https://www.zjut.edu.cn) supervised by Prof. [Guojiang Shen](https://homepage.zjut.edu.cn//sgj/) and Prof. [Xiangjie Kong](http://www.cssclab.cn/xjkong/).

My research interests include Large Language Models, Learning Theory, City Computing, and Recommender Systems.
If you are interested in collaborating with me or want to have a chat, always feel free to contact me through <a href="mailto:hahahenha@gmail.com">hahahenha@gmail.com</a>

# News

<style>
  .scrollable {
    max-height: 150px; /* 设置最大高度 */
    overflow-y: scroll; /* 设置垂直滚动条 */
  }
</style>

<div class="scrollable">

 <ul>
    <li><strong>[2025.06]</strong>: One article is published on BOC Connect app (中銀商聚). </li>
  </ul>

  
 <ul>
    <li><strong>[2025.05]</strong>: Two papers have been accepted by KDD 2025.</li>
  </ul>

  
 <ul>
    <li><strong>[2025.04]</strong>: One paper has been accepted by IJCAI 2025.</li>
  </ul>
  
 <ul>
    <li><strong>[2024.12]</strong>: One paper has been accepted by AAAI 2025.</li>
  </ul>
  
 <ul>
    <li><strong>[2024.12]</strong>: One paper has been accepted by WWW 2025 tutorial.</li>
  </ul>
  
  <ul>
    <li><strong>[2024.07]</strong>: One paper has been accepted by IEEE Transactions on Vehicular Technology.</li>
  </ul>
  
  <ul>
    <li><strong>[2024.06]</strong>: One paper has been accepted by KDD 2024, research track.</li>
  </ul>
  
  <ul>
    <li><strong>[2023.05]</strong>: One paper has been accepted by KDD 2023, research track.</li>
  </ul>
</div>

# Selected Publications

<ol>
  <li>
  <Strong>Xiao Han</Strong>, Chen Zhu, Xiangyu Zhao, and Hengshu Zhu,
    Swarm Intelligence in Geo-Localization: A Multi-Agent Large Vision-Language Model Collaborative Framework,
    <em>Thirty-first ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD'25), Research Track</em>.
    <a target="_blank" rel="noopener" href="https://arxiv.org/abs/2408.11312">[PDF]</a>
  </li>
  <li>
  <Strong>Xiao Han</Strong>, Zijian Zhang, Xiangyu Zhao, Guojiang Shen, Xiangjie Kong, Xuetao Wei, Liqiang Nie, Jieping Ye, and Yuanshao Zhu,
    GARLIC: GPT-Augmented Reinforcement Learning with Intelligent Control for Vehicle Dispatching,
    <em>Thirty-Nine AAAI Conference on Artificial Intelligence (AAAI'25)</em>.
    <a target="_blank" rel="noopener" href="https://arxiv.org/abs/2408.10286">[PDF]</a>
  </li>
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

# Projects

<div>
  <ul>
    <li>
                            <div class="circle"></div>
                            <h2>Signal Timing: "City Brain" Project in Xiaoshan District, Hangzhou, Zhejiang Province</h2>
                            <p>Deploy adaptive-signal-control algorithm for all intersections with signal control in Xiaoshan District。</p>
                            <img src="../img/project-1.1.JPG" height="340px" width="540px">
                            <p>The comparison between before (left) and after (right) deployment of the algorithm is as follows:</p>
                            <img src="../img/project-1.2.JPG" height="200px" width="320px">
                            <img src="../img/project-1.3.JPG" height="200px" width="200px">
                        </li>
                        <li>
                            <div class="circle"></div>
                            <h2>Special Vehicles First System</h2>
                            <p>The project aims to open a emergency channel for special vehicles (e.g. ambulances).</p>
                            <img src="../img/project-2.1.JPG" height="304px" width="540px">
                            <p>When vehicles are going to pass through the intersection, the signal lights lock the green light in advance. It will release queued vehicles and ensure that the target vehicle does not stop at intersection and pass safely.</p>
                            <img src="../img/project-2.2.JPG" height="304px" width="540px">
                            <p>When the vehicle passes by the intersection, the signal lights release the green light lock as soon as possible to avoid traffic jams in other directions</p>
                            <img src="../img/project-2.3.JPG" height="304px" width="540px">
                        </li>
                        <li>
                            <div class="circle"></div>
                            <h2>The Display System in Hangzhou Transportation Administration of Zhejiang Province</h2>
                            <p>A comprehensive display system of data collected by various detectors in Hangzhou.</p>
                            <img src="../img/project-3.1.JPG" height="101px" width="180px">
                            <img src="../img/project-3.2.JPG" height="101px" width="180px">
                            <img src="../img/project-3.3.JPG" height="101px" width="180px">
                            <img src="../img/project-3.4.JPG" height="101px" width="180px">
                            <img src="../img/project-3.5.JPG" height="101px" width="180px">
                            <img src="../img/project-3.6.JPG" height="101px" width="180px">
                        </li>
                        <li>
                            <div class="circle"></div>
                            <h2>Imitation of Unix file system
                                <a href="https://github.com/hahahenha/UnixFilesystem">
                                    <i nclass="icon-link"></i>Source Code</a>
                            </h2>
                            <p>A file system that simulates the underlying storage of Unix systems with basic file operations.</p>
                        </li>
                         <li>
                            <div class="circle"></div>
                            <h2>Tea——A Web Design Project
                            	<a href="https://www.hahahenha.net/static/tea">
                                    <i nclass="icon-link"></i>Go to</a>
                            </h2>
                            <p>Design and complete a beautiful front-end website.</p>
                        </li>
                        <li>
                            <div class="circle"></div>
                            <h2> OA System </h2>
                            <p>It is written in .NET language and integrates modules such as login, hierarchical notification, personal attendance, schedule, online meeting, workflow design and management, work plan, mail system, asset management, electronic seal management, contract record, system operation log, etc. It has greatly promoted the management of leaders at all levels, coordinated exchange of information between various departments, and the safe, stable and reliable transmission of information inside and outside the department, which facilitates the realization of distributed office and mobile office for all employees.</p>
                        </li>
                        <li>
                            <div class="circle"></div>
                            <h2> Indoor Positioning APP </h2>
                            <p>The location of the target is accurately located through the signal strength of multiple wifi and Bluetooth beacons distributed indoors.</p>
                            <iframe width="560" height="315" src="https://www.hahahenha.net/static/CV/video/project-5.mp4" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                        </li>
                        <li>
                            <div class="circle"></div>
                            <h2> Traffic Data-fusion System </h2>
                            <p>Combined with the distributed platform Spark, distributed file system HDFS, SpringBoot framework and D3.js front-end visual library are written and completed.</p>
                            <img src="../img/project-4.JPG" height="304px" width="540px">
                        </li>
                        <li>
                            <div class="circle"></div>
                            <h2> Signal Timing Project of Jiujiang City, Jiangxi Province </h2>
                            <p>Timing the evening peak signal for the main road of Jiujiang City.</p>
                        </li>
  </ul>
</div>

# Honors and Awards

<div>
  <ul>
    <li>
      <strong>[2021.06]</strong>: 
      Outstanding Graduate, Granted by: Zhejiang Provincial Education Department, China
      </li>
    <li>
      <strong>[2019.12]</strong>: 
      National Scholarship, Granted by: Ministry of Education, China
      </li>
  </ul>
</div>

# Internships & Exchange

<div>
  <ul>
    <li>
      <strong>[2023.11-2024.07]</strong>: 
      Research Intern, Career Science Lab in BOSS Zhipin. Leader: <a target="_blank" rel="noopener" href="https://www.zhuhengshu.com/">Hengshu Zhu</a>, Chen Zhu.
      </li>
    <li>
      <strong>[2021.09-2024.12]</strong>: 
      Researcher, Lab for AI-Powered Fintech (Hong Kong).
      </li>
    <li>
      <strong>[2020.09-2020.12]</strong>: 
      Visiting Student, City University of Hong Kong. Supervisor: <a target="_blank" rel="noopener" href="https://scholars.cityu.edu.hk/en/persons/kwai-sang-chin">Kwai-Sang Chin</a>.
      </li>
    <li>
      <strong>[2020.09-2020.12]</strong>: 
      Algorithm Engineer, Zhejiang Supcon Information Technology Co., Ltd. Leader: Junjie Zhou.
      </li>
  </ul>
</div>

# Teaching Experience

<div>
  <ul>
    <li><strong>[2023 Spring, 2023 Fall, 2024 Spring]</strong>: Teaching Assistant of <strong>Deep Learning</strong> at the City University of Hong Kong.</li>
    
    <li><strong>[2024 Fall]</strong>: Teaching Assistant of <strong>Advanced Statistics</strong> at the City University of Hong Kong.</li>

    <li><strong>[2020 Fall]</strong>: Teaching Assistant of <strong>Intelligent Transportation Systems</strong> at the Zhejiang University of Technology.</li>
  </ul>
</div>

# Services

<div>
  <ul>
    <li>
      I am a reviewer for IEEE TITS, IEEE TBD, IJCAI, KDD, etc.
      </li>
  </ul>
</div>
