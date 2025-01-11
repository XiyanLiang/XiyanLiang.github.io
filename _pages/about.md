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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/weight_matrix.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Art and Science of Quantizing Large-Scale Models: A Comprehensive Overview](https://arxiv.org/pdf/2409.11650)

Yanshu Wang, Tong Yang, **Xiyan Liang**, Guoan Wang, Hanning Lu, Xu Zhe, Yaoming Li, Li Weitao

[**Project**]([https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=l5OllR0AAAAJ&citation_for_view=l5OllR0AAAAJ:u5HHmVD_uO8C)) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- This paper provides a comprehensive overview of the principles, challenges, and methodologies associated with quantizing large-scale neural network models. As neural networks have evolved towards larger and more complex architectures to address increasingly sophisticated tasks, the computational and energy costs have escalated significantly. We explore the necessity and impact of model size growth, highlighting the performance benefits as well as the computational challenges and environmental considerations. The core focus is on model quantization as a fundamental approach to mitigate these challenges by reducing model size and improving efficiency without substantially compromising accuracy. We delve into various quantization techniques, including both post-training quantization (PTQ) and quantization-aware training (QAT), and analyze several state-of-the-art algorithms such as LLM-QAT, PEQA(L4Q), ZeroQuant, SmoothQuant, and others. Through comparative analysis, we examine how these methods address issues like outliers, importance weighting, and activation quantization, ultimately contributing to more sustainable and accessible deployment of large-scale models. 
</div>
</div>

# 💻 Academic Practice

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> Undergraduate Innovative Research Programs at Nankai University</div><img src='images/预期成果.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

BioSonicGuard: Avian Vocal Recognition using Convolutional Neural Networks

**Xiyan Liang**, Qianghui Guo, Yuanzhi Shao, Xingyuan Qing, Yiyang Liu, Jiahe Guo

[**Project**](Nankai University - Joint Research Center for Intelligent Ecological Mathematics and Smart Nature Conservation)

-	Carried out the research on identifying birds' vocals with a machine learning-based approach for individual recognition to extract features from the bird's vocalization spectra based on convolutional neural networks (CNN). Expect to implement a two-tiered CNN model to precisely monitor bird populations and assess and protect the health and diversity of ecosystems.
-	Successfully applied for **software copyright** for the developed bird vocal recognition system.
-	The project was showcased at **the China International Fair for Trade in Services 2024** in collaboration with Deep Nature Technology Company, and received the silver award of “The 11th Tianjin Youth Entrepreneurship Competition” as well as the silver award of the 2024 "Challenge Cup" Bank of China Tianjin University Student Entrepreneurship Plan Competition.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> MCM</div><img src='images/the Mind Map of Our Work.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Tennis Momentum Analysis and Prediction Modelling

Chenyang Jia, **Xiyan Liang**, Jiashuo Liu

[**Project**](COMAP Mathematical Contest in Modeling)

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
- *2025.07 - 2025.10*, [Matics]([https://globalink.mitacs.ca/#/]), Canada.
