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

I am a Postdoctoral Research Fellow at the Department of Electronic Engineering, Tsinghua University. Before that, I received my Ph.D. in Computer Science from Chongqing University in 2024.

My research interests include Spatiotemporal Data Mining and LLM Agents. I have published over 10 papers in top-tier conferences and journals with total <a href='https://scholar.google.com/citations?user=cSrV8q4AAAAJ'>google scholar citations <strong><span id='total_cit'>100+</span></strong></a>

<div style="display:flex; flex-wrap:wrap; align-items:flex-start; margin-top:1rem; gap:1rem;">

  <!-- 左边文字 -->
  <div style="flex:1; min-width:250px; font-size:0.95rem; line-height:1.6;">
    <p><strong>Office Address:</strong><br>
    Room 10-202, ROHM Building,<br>
    30 Shuangqing Road, Haidian District,<br>
    Beijing 100084, China</p>
  </div>

  <!-- 右边地图 -->
  <div style="flex:1; min-width:300px; height:250px; border:1px solid #ddd; border-radius:6px; overflow:hidden;">
    <div id="mapid" style="height:100%; width:100%;"></div>
  </div>
</div>

<!-- Leaflet CSS & JS -->
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css"/>
<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>

<script>
  var map = L.map('mapid').setView([40.00431, 116.32999], 11); // 深圳坐标
  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    attribution: '© OpenStreetMap contributors'
  }).addTo(map);

  // 添加标记
  L.marker([40.00431, 116.32999]).addTo(map)
    .bindPopup('ROHM Building')
    .openPopup();
</script>

# 🔥 News

# 📝 Publications 
1. Yuwei Du, Jie Feng, **Jie Zhao**, Jian Yuan, Yong Li, [TrajAgent: An LLM-based Agent Framework for Automated Trajectory Modeling via Collaboration of Large and Small Models](https://arxiv.org/abs/2410.20445), *NeurIPS*, 2025.
2. **Jie Zhao**, Chao Chen, Wanyi Zhang, Mingyu Deng, Huayan Pu, Jun Luo, [SE-GCL: A Semantic-Enhanced Graph Contrastive Learning Framework for Road Network Embedding](https://dl.acm.org/doi/abs/10.1145/3757921), *ACM Transactions on Knowledge Discovery from Data (TKDD)*, 2025.
3. **Jie Zhao**, Chao Chen, Yuanshao Zhu, Mingyu Deng, Yuxuan Liang, [UniTR: A Unified Framework for Joint Representation Learning of Trajectories and Road Networks](https://ojs.aaai.org/index.php/AAAI/article/view/33457), *AAAI*, 2025.
4. Jie Feng, Yuwei Du, **Jie Zhao**, Yong Li, [AgentMove: A Large Language Model based Agentic Framework for Zero-shot Next Location Prediction](https://aclanthology.org/2025.naacl-long.61/), *NAACL*, 2025.
5. Mingyu Deng, Chao Chen, Wanyi Zhang, **Jie Zhao**, Wei Yang, Suiming Guo, Huayan Pu, Jun Luo, [HyperRegion: Integrating Graph and Hypergraph Contrastive Learning for Region Embeddings](https://ieeexplore.ieee.org/abstract/document/10791310/), IEEE Transactions on Mobile Computing (TMC), 2024.
6. Mingyu Deng, Wanyi Zhang, **Jie Zhao**, Zhu Wang, Mingliang Zhou, Jun Luo, Chao Chen, [A Novel Framework for Joint Learning of City Region Partition and Representation](https://dl.acm.org/doi/abs/10.1145/3652857), *ACM Transactions on Multimedia Computing, Communications and Applications (TOMM)*, 2024.
7. **Jie Zhao**, Chao Chen, Wanyi Zhang, Ruiyuan Li, Fuqiang Gu, Songtao Guo, Jun Luo, Yu Zheng, [Coupling Makes Better: An Intertwined Neural Network for Taxi and Ridesourcing Demand Co-Prediction](https://ieeexplore.ieee.org/abstract/document/10265747), *IEEE Transactions on Intelligent Transportation Systems (T-ITS)*, 2024.
8. **Jie Zhao**, Chao Chen, Chengwu Liao, Hongyu Huang, Jie Ma, Huayan Pu, Jun Luo, Tao Zhu, Shilong Wang, [2F-TP: Learning Flexible Spatiotemporal Dependency for Flexible Traffic Prediction](https://ieeexplore.ieee.org/abstract/document/9703274), *IEEE Transactions on Intelligent Transportation Systems (T-ITS)*, 2023.
9. **Jie Zhao**, Chao Chen, Linli Jiang, Chengwu Liao, Kaiqiang An, Yuanjie Li, Guoping Liu, Xiang Wen, Runbo Hu, Hua Chai, [L2RR: Towards a More Diversified Navigation Service with Learning to Rank Routes Framework](https://ieeexplore.ieee.org/abstract/document/10422614/), *IEEE 26th International Conference on Intelligent Transportation Systems (ITSC)*, 2023.
10. **Jie Zhao**, Chao Chen, Hongyu Huang, Chaocan Xiang, [Unifying Uber and Taxi Data via Deep Models for Taxi Passenger Demand Prediction](https://link.springer.com/article/10.1007/s00779-020-01426-y), *Personal and Ubiquitous Computing (PUC)*, 2023.
11. Yi Xie, Yun Xiong, Jiawei Zhang, Chao Chen, Yao Zhang, **Jie Zhao**, Yizhu Jiao, Jinjing Zhao, Yangyong Zhu, [Temporal Super-Resolution Traffic Flow Forecasting via Continuous-Time Network Dynamics](https://link.springer.com/article/10.1007/s10115-023-01887-6), *Knowledge and Information Systems (KAIS)*, 2023.
12. Xuefeng Xie, **<u>Jie Zhao</u>**, Chao Chen, Lin Wang, [AF-TCP: Traffic Congestion Prediction at Arbitrary Road Segment and Flexible Future Time](https://link.springer.com/chapter/10.1007/978-3-030-95391-1_11), *International Conference on Algorithms and Architectures for Parallel Processing (ICA3PP)*, 2021.

# Experience
## Work
- *2024.11 - 2026.11*, Postdoctoral Research Fellow, Department of Electronic Engineering, Tsinghua University, Beijing, China. In cooperation with Prof. Yong LI.
- *2024.06 - 2024.09*, Research Assistant, The Hong Kong University of Science and Technology, Guangzhou, China. In cooperation with Prof. Yuxuan LIANG.

## Education
- *2018.09 - 2024.06*, Ph.D. in Computer Science, College of Computer Science, Chongqing University, Chongqing, China. Supervised by Prof. Chao CHEN.
