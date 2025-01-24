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

Hi, thanks for stopping by my page. I am from [Macau](https://en.wikipedia.org/wiki/Macau) and my name is Hou-Wan Long (龍浩雲). I am currently a third year student at The Chinese University of Hong Kong (CUHK), majoring in Risk Management Science (STAT+CS+FIN, has little thing to do with Management!!). My research interests include Computational Social Science, AI for Finance and Decentralized Mechanism. I am looking for PhD position for Fall, 2026. You can find my [CV](images/resume.pdf) here.

<ul>
  <li><strong>Core Course:</strong> Probability I&II (A), Stochastic Processes (A), Data Structure (A), Java Programming (A), Calculus I&II (A-), Financial Management (A), Credit Risk Management (A-).</li>
  <li><strong>Skill:</strong> Pandas, Pytorch, Selenium.</li>
  <li><strong>Language:</strong> English (fluent), Cantonese (native), Mandarin (native).</li>
</ul>

# 📖 Educations
- *2022.09 - 2026.05 (expected)*, B.Sc. in Risk Management Science, The Chinese University of Hong Kong, Hong Kong. 
- *2025.01 - 2025.05 (present)*, Exchange Program, Washington University in St. Louis, USA.
- *2025.09 - 2026.01 (upcoming)*, Exchange Program, University of Waterloo, Canada. 

# 🔥 News
- *2025.01*: &nbsp;🎉🎉 My paper "Bridging Culture and Finance: A Multimodal Analysis of Memecoins in the Web3 Ecosystem" is accepted by ACM Internation World Wide Web Conference 2025 (WWW'25) short paper track. 
- *2024.12*: &nbsp;🎉🎉 My work with [Decentralized Computing Lab, University of Washington, Tacoma](https://sites.uw.edu/weicaics/) "A Multidimensional Contract Design for Smart Contract-as-a-Service" is accepted by IEEE Transaction on Computational Social Systems.
- *2024.11*: &nbsp;🎉🎉 I receive the "Students are future" Scholarship by Kyoto University and present my research poster "Transfer Learning in Financial Time Series with Gramian Angular Field" at The Pacific Rim International Conference on Artificial Intelligence 2024 (PRICAI).
- *2024.07*: &nbsp;🎉🎉 My paper "Token Fungibility Duality: Technical and Graphical Analysis on 404 Standards" is accepted by IEEE International Conference on Blockchain 2024 (acceptance rate=18.9%).
- *2024.01*: &nbsp;🎉🎉 My work with [Faculty of Science and Technology, University of Macau](https://www.fst.um.edu.mo/) "Minimizing block incentive volatility through Verkle tree-based dynamic transaction storage" is accepted by Decision Support System.
- *2023.10*: &nbsp;🎉🎉 My paper "Dynamic Mining Interval to Improve Blockchain Throughput" is accepted by IEEE International Conference on Big Data 2023 (acceptance rate=17.4%).
  
# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM Internation World Wide Web Conference 2025</div><img src='images/coin_meme.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Bridging Culture and Finance: A Multimodal Analysis of
Memecoins in the Web3 Ecosystem](https://arxiv.org/pdf/2412.04913)

**Hou-Wan Long**, Nga-Man Wong, Wei Cai

**Introduction**
- This paper introduces the Coin-Meme dataset and a multimodal framework to analyze memecoins, exploring their cultural themes, community interactions, and financial behaviors within the Web3 ecosystem.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE Transaction on Computational Social Systems</div><img src='images/SaaS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Multidimensional Contract Design for Smart Contract-as-a-Service](https://ieeexplore.ieee.org/abstract/document/10839568)

Jinghan Sun, **Hou-Wan Long**, Hong Kong, Zhixuan Fang, Abdulmotaleb El Saddik, Wei Cai

**Introduction**
- This paper proposes a smart contract-as-a-service (SCaaS) paradigm to enhance efficiency, security, and developer engagement in Web3 by leveraging blockchain-based reputation filters, incentive mechanisms, and differentiated strategies for developers.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE International Conference on Blockchain 2024</div><img src='images/404.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Token Fungibility Duality: Technical and Graphical Analysis on 404 Standards](https://ieeexplore.ieee.org/abstract/document/10664313)

**Hou-Wan Long**, Yain-Whar Si

**Introduction**
- This paper analyzes the ERC-404 and DN-404 blockchain standards, which combine fungible and non-fungible token features, highlighting ERC-404's challenges like high costs and congestion, DN-404's improvements in efficiency, and revealing power-law distributions in token activities.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Decision Support Systems</div><img src='images/verkle.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Minimizing block incentive volatility through Verkle tree-based dynamic transaction storage](https://www.sciencedirect.com/science/article/pii/S0167923624000137)

Xiongfei Zhao, Gerui Zhang, **Hou-Wan Long**, Yain-Whar Si

**Introduction**
- The abstract introduces a Dynamic Transaction Storage (DTS) strategy using Verkle trees and optimization algorithms to stabilize block incentives in consortium blockchains, reducing volatility and improving security by prioritizing time-based transaction incorporation and minimizing bandwidth consumption.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE Internation Conference on Big Data 2023</div><img src='images/bigdata.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic Mining Interval to Improve Blockchain Throughput](https://ieeexplore.ieee.org/abstract/document/10386281)

**Hou-Wan Long**, Xiongfei Zhao, Yain-Whar Si

**Introduction**
- This paper proposes a Dynamic Mining Interval (DMI) mechanism combined with Dynamic Transaction Storage (DTS) to enhance Blockchain transaction throughput and address challenges like fluctuating transaction activities, deviant mining threats, and reduced system efficiency caused by Merkle tree leaf node utilization in DTS.
</div>
</div>

# 🎖 Honors and Awards
- *2024.11* "Students are future" Scholarship by Kyoto University.
- *2024.07* Dean’s List by Department of Statistics, The Chinese University of Hong Kong.
- *2023.12* Research Studentship by Department of Statistics, The Chinese University of Hong Kong.
- *2023.11* Student Travel Award by Institute of Electrical and Electronics Engineers (IEEE).
- *2023.05* Reaching Out Award by New Asis College, The Chinese University of Hong Kong.


# 💻 Industrial_Internships
- *2025.05 - 2025.09 (upcoming)*, [Singapore Institute of Manufacturing Technology-A*STAR](https://www.a-star.edu.sg/simtech), Singapore.
- *2024.07 - 2024.09*, [CITIC aiBank Corporation Limited](https://www.group.citic/en/Diversified_Portfolio/Finance/Bank/), Beijing, China.
