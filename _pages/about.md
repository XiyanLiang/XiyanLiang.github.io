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

I am an undergraduate student in the School of Mathematical Sciences at Nankai University (Class of 2022), majoring in Mathematical Sciences. My research interests lie in discrete structures, large-scale model quantization, data stream algorithms, and machine learning applications. I have participated in projects such as PSSketch and avian vocal recognition, gaining a solid foundation and practical experience. I humbly look forward to learning and collaborating with others in related fields.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=l5OllR0AAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=l5OllR0AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).-->


<!--# 🔥 News
- *2022.09*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

# 📖 Educational Background
- *2022.09 - 2026.07 (expected)*, Nankai University, Mathematical Sciences.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGKDD</div><img src='images/overall.pdf' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PSSketch: Finding Persistent and Sparse Flow with High Accuracy and Efficiency](https://ui.adsabs.harvard.edu/abs/2025arXiv250504892W/abstract)

Jiayao Wang, Qilong Shi, **Xiyan Liang**, Han Wang, Wenjun Li, Ziling Wei, Weizhe Zhang, Shuhui Chen

**Abstract**
<!--[**Project**]([https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=l5OllR0AAAAJ&citation_for_view=l5OllR0AAAAJ:u5HHmVD_uO8C]) <strong><span class='show_paper_citations' data='l5OllR0AAAAJ:u5HHmVD_uO8C'></span></strong>-->

- Finding persistent sparse (PS) flow is critical to early warning of many threats. Previous works have predominantly focused on either heavy or persistent flows, with limited attention given to PS flows. Although some recent studies pay attention to PS flows, they struggle to establish an objective criterion due to insufficient data-driven observations, resulting in reduced accuracy. In this paper, we define a new criterion "anomaly boundary" to distinguish PS flows from regular flows. Specifically, a flow whose persistence exceeds a threshold will be protected, while a protected flow with a density lower than a threshold is reported as a PS flow. We then introduce PSSketch, a high-precision layered sketch to find PS flows. PSSketch employs variable-length bitwise counters, where the first layer tracks the frequency and persistence of all flows, and the second layer protects potential PS flows and records overflow counts from the first layer. Some optimizations have also been implemented to reduce memory consumption further and improve accuracy. The experiments show that PSSketch reduces memory consumption by an order of magnitude compared to the strawman solution combined with existing work. Compared with SOTA solutions for finding PS flows, it outperforms up to 2.94x in F1 score and reduces ARE by 1-2 orders of magnitude. Meanwhile, PSSketch achieves a higher throughput than these solutions.

</div>
</div>

# 💻 Academic Practice

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> Undergraduate Innovative Research Programs at Nankai University</div><img src='images/预期成果 Medium.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

BioSonicGuard: Avian Vocal Recognition using Convolutional Neural Networks

**Xiyan Liang**, Qianghui Guo, Yuanzhi Shao, Xingyuan Qing, Yiyang Liu, Jiahe Guo

**Project** | Nankai University - Joint Research Center for Intelligent Ecological Mathematics and Smart Nature Conservation

-	Carried out the research on identifying birds' vocals with a machine learning-based approach for individual recognition to extract features from the bird's vocalization spectra based on convolutional neural networks (CNN). Expect to implement a two-tiered CNN model to precisely monitor bird populations and assess and protect the health and diversity of ecosystems.
-	Successfully applied for **software copyright** for the developed bird vocal recognition system.
-	The project was showcased at **the China International Fair for Trade in Services 2024** in collaboration with Deep Nature Technology Company, and received the silver award of “The 11th Tianjin Youth Entrepreneurship Competition” as well as the silver award of the 2024 "Challenge Cup" Bank of China Tianjin University Student Entrepreneurship Plan Competition.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> MCM</div><img src='images/the Mind Map of Our Work.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Tennis Momentum Analysis and Prediction Modelling

Chenyang Jia, **Xiyan Liang**, Jiashuo Liu

**Project** | COMAP Mathematical Contest in Modeling

-	Defined "momentum" in tennis games to enhance player preparation and match advice based on the established models, including the Momentum Definition and Visualization (MDV) Model, Randomness Test Model, and Turning Point Prediction (TPP) Model.
-	Analyzed the accuracy of the TPP model, achieving up to 65% accuracy and robustness against interference, and validated model universality through testing with other match data.
-	Formulated the Momentum Scoring Rule by scientifically quantified momentum to portray players' performance based on data analysis in the MDV Model; quantified turning points using momentum scores in the TTP Model.

</div>
</div>

<!--- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**-->

# 🎖 Honors and Awards
- *2023.10* Excellent Student Cadre at University Level, NKU
- *2023.10* Student Service Scholarship at University Level, NKU
- *2023.10* Cultural and Athletic Scholarship at University Level, NKU
- *2024.05* Meritorious Winner, COMAP Mathematical Contest in Modeling, MCM
- *2024.08* 2024 "Challenge Cup" Bank of China Tianjin University Student Entrepreneurship Plan Competition, Tianjin
- *2024.08* The 11th Tianjin Youth Entrepreneurship Competition, Tianjin
- *2024.10* Innovation Scholarship at University Level, NKU
 

<!---# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)-->

# 💻 Internships
- *2024.01 - 2024.02*, [Global Education, Academics and Research Skills Program (GEARS), NCSU]([https://gti.ncsu.edu])
- *2025.07 - 2025.10*, [Mitacs]([https://globalink.mitacs.ca/#/]), Canada.
