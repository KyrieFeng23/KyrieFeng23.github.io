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

I am currently a Ph.D. student under the advisory of Prof. [Defu Lian](http://staff.ustc.edu.cn/~liandefu/) and Prof. [Kai Zheng](https://zheng-kai.com/) in School of Computer Science and Engineering, [University of Electronic Science and Technology of China(UESTC)](https://www.uestc.edu.cn/). I got my B.S. degree from the University of Electronic Science and Technology of China in 2018. My research interests include data mining and recommender systems.





<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 
1. **Jin Chen**, Defu Lian, Yucheng Li, Baoyun Wang, Kai Zheng, Enhong Chen. Cache-Augmented Inbatch Importance Resampling for Training Recommender Retriever. The 36th Conference on Neural Information Processing Systems, accepted. (**NeurIPS 2022**)
1. Shuncheng Liu, Xu Chen, Yan Zhao, **Jin Chen**, Rui Zhou and Kai Zheng*. Efficient Learning with Pseudo Labels for Query Cost Estimation. The 30th ACM International Conference on Information & Knowledge Management, accepted. (**CIKM 2022**)
1. **Jin Chen**, Guanyu Ye, Yan Zhao, Shuncheng Liu, Liwei Deng, Xu Chen, Rui Zhou and Kai Zheng*. Efficient Join Order Selection Learning with Graph-based Representation. The 28th ACM SIGKDD Conference on Knowledge Discovery and Date Mining, accepted. (**KDD 2022**)
2. Rui Fan, **Jin Chen**, Jin Zhang, Defu Lian* and Enhong Chen. Improving Implicit Alternating Least Squares with Ring-based Regularization. Proceedings of the 45th International ACM SIGIR Conference on Research and Development in Information Retrieval. (**SIGIR 2022**) 
4. **Jin Chen**, Defu Lian * , Binbin Jin, Kai Zheng * and Enhong Chen. Learning Recommenders for Implicit Feedback with Importance Resampling. Proceedings of the ACM Web Conference 2022. (**WWW 2022**)
5. **Jin Chen**, Defu Lian*, Binbin Jin, Xu Huang, Kai Zheng and Enhong Chen. Fast Variational AutoEncoder with Inverted Multi-Index for Collaborative Filtering. Proceedings of the ACM Web Conference 2022. (**WWW 2022**)
6. Gangwei Jiang, Hao Wang, **Jin Chen**, Haoyu Wang, Defu Lian* and Enhong Chen. xLightFM: Extremely Memory-Efficient Factorization Machine. Proceedings of the 44th International ACM SIGIR Conference on Research and Development in Information Retrieval. (**SIGIR 2021**)
7. **Jin Chen**, Ju Xu, Gangwei Jiang, Tiezheng Ge, Zhiqiang Zhang, Defu Lian* and Kai Zheng. Automated Creative Optimization for E-Commerce Advertising. Proceedings of the Web Conference 2021. (**WWW 2021**)
8. Defu Lian, **Jin Chen**, Kai Zheng * , Enhong Chen *  and Xiaofang Zhou. Ranking-based Implicit Regularization for One-Class Collaborative Filtering. IEEE Transactions on Knowledge and Data Engineering, 2021. (**TKDE**)
9. **Jin Chen**, Tiezheng Ge, Gangwei Jiang, Zhiqiang Zhang, Defu Lian* and Kai Zheng. Efficient Optimal Selection for Composited Advertising Creatives with Tree Structure. Proceedings of the AAAI Conference on Artificial Intelligence. 2021. (**AAAI 2021**)
10. **Jin Chen**, Defu Lian* and Kai Zheng. Collaborative filtering with ranking-based priors on unknown ratings. IEEE Intelligent Systems, 2020, 35(5): 38-49.
11. **Jin Chen**, Defu Lian* and Kai Zheng. Improving one-class collaborative filtering via ranking-based implicit regularizer. Proceedings of the AAAI Conference on Artificial Intelligence. 2019. (**AAAI 2019**)

&emsp; &emsp; &emsp; &emsp; **Note**: * indicates the corresponding author

# 📖 Educations

- *2014.09 - 2018.06*, School of Computer Science and Engineering, University of Electronic Science and Technology of China, Bachelor. 
- *2020.09 - 2024.06 (expected)*, School of Computer Science and Engineering, University of Electronic Science and Technology of China, Ph.D. student.
  - Master from 2018 and Successive Postgraduate and Doctoral Program from 2020

# 💻 Internships

- *2019.10 - 2020.10*, Alimama, Alibab Group, Beijing, China.
  - Online Advertising Creative Optimization
  - Mentor: [Tiezheng Ge](https://scholar.google.com/citations?user=db5ZTlMAAAAJ&hl=en)

# 🎖 Honors and Awards

- UESTC Academic Newcomer Award, 2022
- First-class People's Scholarship (2019, 2021)
- Alibaba’s Excellent Research Intern, 2020
- AAAI 2019 Travel Award

# ⏳ Professional Services

#### Program Committee Members
- Sub-Reviewer, WWW 2022
- PC member, AAAI 2022, AAAI 2021, AAAI 2023
- PC member, IJCAI 2022
- PC member, CIKM 2022
- PC member, ECML-PKDD 2022

#### Journal Invited Reviewer
- ACM Transactions on Information Systems (TOIS)

<!-- # 📆 Research Experience

#### Ranking-based Implicit Regularization for One-class collaborative filtering
+ Propose a ranking-based regularizer for one-class collaborative filtering by hypothesizing that users’ preference scores for uninteracted items should not deviate a lot from each other.
+ The research has been accepted by AAAI 2019, TKDE 2021.

#### Advertising Creative Optimization <font size="3">(Alibaba Innovative Research, Alimama Group) </font>
+ Lead and accomplish the research of online advertising creative optimization.
+ Deploy the algorithm in the production environment and increase CTR by 5%.
+ The research has been accepted by AAAI 2021, WWW 2021.

#### Dynamic Negative Sampling for Recommender Systems
+ Propose a dynamic sampler via inverted multi-index. The research has been accepted by WWW 2022.
+ Design an importance resampling based sampler. The research has been accepted by WWW 2022.
+ Propose a Cache-Augmented Inbatch Importance Resampling for training recommender retrievers. The research has been submitted to NeurIPS 2022.

#### Join Order Selection for Database Optimizer <font size="3"> (Huawei Cloud Database Innovation Lab) </font>
+ Lead and accomplish the research of RL-based Join Order Selection.
+ The research has been accepted by KDD 2022. -->
