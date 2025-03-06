---
permalink: /
title: "About Me"
excerpt: "About Me"
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

# 🎓 About Me

I am a fourth year PhD student from [Department of Information Science and Electronic Engineering](http://www.isee.zju.edu.cn/), [Zhejiang University](https://www.zju.edu.cn), supervised by [Prof. Bing Hu](https://person.zju.edu.cn/hubing). I received my BE degree from [Department of Computer Science and Engineering](http://www.cse.neu.edu.cn), [Northeastern University](http://www.neu.edu.cn) in 2021. Currently, I am a visiting researcher in [5G/6GIC](https://www.surrey.ac.uk/institute-communication-systems/5g-6g-innovation-centre) of [ICS](https://www.surrey.ac.uk/institute-communication-systems) at [University of Surrey](https://www.surrey.ac.uk/), supervised by [Prof. Rahim Tafazolli](https://www.surrey.ac.uk/people/rahim-tafazolli) (FREng, FIEEE), [Prof. Pei Xiao](https://www.surrey.ac.uk/people/pei-xiao) and [Dr. Mahdi Boloursaz Mashhadi](https://www.surrey.ac.uk/people/mahdi-boloursaz-mashhadi), and sponsored by China Scholarship Council (CSC).

<!-- 
My research interests include Distributed Machine Learning System, LLM Distributed Training/Inference and Federated/Split Learning. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

# 🚀 Research Interests
- Distributed Machine Learning System 
- LLM Distributed Training/Inference
- Federated/Split Learning 

# 📝 Publications 
## 2025
- **Y. Q. Gao**, Z. Zhang, B. Hu, M. B. Mashhadi, A. L. Jin and P. Xiao, “NetPlacer+: Model Parallelism based on Load Balance in Distributed Deep Learning,” *IEEE Transactions on Emerging Topics in Computational Intelligence*, , Accepted on Feb. 25, 2025. (<span style="color:red;">SCI Q1</span>)
- **Y. Q. Gao**, B. Hu, M. B. Mashhadi, W. Wang, M. Bennis, “[PipeSFL: A Fine-Grained Parallelization Framework for Split Federated Learning on Heterogeneous Clients](https://ieeexplore.ieee.org/document/10740645),” *IEEE Transactions on Mobile Computing*, vol. 24, no. 3, pp. 1774-1791, 2025. (<span style="color:red;">CCF A, SCI Q1</span>)
- **Y. Q. Gao**, B. Hu, M. B. Mashhadi, W. Wang, R. Tafazolli, and M. Debbah, “[A Dynamic Sliding Window based Tensor Communication Scheduling Framework for Distributed Deep Learning](https://ieeexplore.ieee.org/document/10816583)," *IEEE Transactions on Network Science and Engineering*, vol. 12, no. 2, pp. 1080-1095, 2025. (<span style="color:red;">SCI Q1</span>)

## 2024
- D. Yang, **Y. Q. Gao**, B. Hu, A. L. Jin, W. Wang, and Y. You, “[GWPF: Communication-Efficient Federated Learning with Gradient-Wise Parameter Freezing](https://www.sciencedirect.com/science/article/pii/S1389128624007187),” *Elsevier Computer Networks*, vol. 255, no. 110886, 2024. (<span style="color:red;">CCF B, SCI Q1</span>)
- M. H. Chang, H. J. Lv, **Y. Q. Gao**, B. Hu, W. Wang, and Z. Yang, “[DGS: An Efficient Delay-Guaranteed Scheduling Framework for Wireless Deterministic Networking](https://ieeexplore.ieee.org/document/10669629),” *IEEE Transactions on Network and Service Management*, vol. 21, no. 6, pp. 6582-6596, 2024. (<span style="color:red;">CCF C, SCI Q1</span>)
- **Y. Q. Gao**, B. Hu, M. B. Mashhadi, A. L. Jin, P. Xiao, and C. M. Wu, “[US-Byte: An Efficient Communication Framework for Scheduling Unequal-sized Tensor Blocks in Distributed Deep Learning](https://ieeexplore.ieee.org/abstract/document/10314018),” *IEEE Transactions on Parallel and Distributed Systems*, Vol. 35, Issue. 1, pp. 123-139, 2024. (<span style="color:red;">CCF A, SCI Q1</span>)

## 2023
- **Y. Q. Gao**, Z. C. Zhang, B. Hu, A. L. Jin, and C. M. Wu, “[OF-WFBP: A Near-optimal Communication Mechanism for Tensor Fusion in Distributed Deep Learning](https://www.sciencedirect.com/science/article/pii/S0167819123000595),” *Elsevier Parallel Computing*, Vol. 118, No.103053, pp. 1-13, 2023. (<span style="color:red;">CCF B</span>)

## 2020
- **Y. Q. Gao**, F. Luan, J. Q. Pan, X. Li, and Y. D. He, “[FPGA-Based Implementation of Stochastic Configuration Networks for Regression Prediction](https://www.mdpi.com/1424-8220/20/15/4191),” MDPI SENSORS, vol. 20, no. 15, pp. 4191-4204, 2020. (<span style="color:red;">SCI Q1</span>)
- J. Q. Pan, F. Luan, **Y. Q. Gao** and Y. J. Wei, “[FPGA-Based Implementation of Stochastic Configuration Network for Robotic Grasping Recognition](https://ieeexplore.ieee.org/document/9152009),” IEEE ACCESS, vol. 8, pp. 139966-139973, 2020. (<span style="color:red;">SCI Q1</span>)

<!--  
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
-->

# 🎖 Honors and Awards
- *2024.10* Zhejiang University Outstanding Graduate Student
- *2024.07* Public Study Abroad approved by China Scholarship Council (CSC) 
- *2022.10* Zhejiang University Triple A Graduate Student (3%)
- *2022.10* Zhejiang University Outstanding Graduate Student
- *2022.10* Zhejiang University New PhD Student Scholarship 
- *2021.06* Outstanding Graduate of Liaoning Province (1%)
- *2021.06* Outstanding Thesis of Northeastern University (1%)
- *2020.11* National Second Prize of Intel Embedded System Invitation Competition
- *2020.10* Postgraduate Recommendation to Zhejiang University 
- *2020.10* China National Scholarship (1%) 
- *2020.10* Northeastern University Outstanding Student (1%) 
- *2019.10* Huawei Scholarship
- *2019.06* Second Prize of Liaoning Province of China Electronic Design Competition
- *2019.03* H Prize of the United States Mathematical Modelling Competition 
- *2018.10* China National Scholarship (1%) 
- *2018.10* Northeastern University Outstanding Student (1%)
- *2018.06* First Prize of Liaoning Province Electronic Design Competition 

# 📖 Educations
- *2024.11 - now*, Visiting Researcher University of Surrey, Institute for Communication Systems, 5G/6G Innovation Centre  
- *2021.09 - now*, Ph.D. Zhejiang University, Department of Information Science and Electronic Engineering 
- *2017.09 - 2021.06*, B.S. Northeastern University, Department of Computer Science and Engineering 

# 🌍 Visitor Map

[![Visitor Map](https://www.clustrmaps.com/map_v2.png?d=avSSlIJR_7VyW55BGOF0bo7dC6Wb8nn9t6CGEsF2E6o&cl=ffffff)](https://clustrmaps.com/site/1c4q0)
<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=avSSlIJR_7VyW55BGOF0bo7dC6Wb8nn9t6CGEsF2E6o&cl=ffffff&w=a"></script>

<!-- 
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->
