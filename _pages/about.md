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

# About me

Lei Yang is a fourth year Ph.D. student at <a href="http://www.svm.tsinghua.edu.cn/">School of Vehicle and Mobility</a>, <a href="https://www.tsinghua.edu.cn/">Tsinghua University</a>, supervised by Prof. <a href="https://www.tsinghua.edu.cn/info/1166/93890.htm">Jun Li</a>. He received his M.S. degree from <a href="https://buaa.edu.cn/">Beihang University</a> in 2018, supervised by Prof. <a href="http://www.me.buaa.edu.cn/info/1071/2301.htm">Qiang Zhan</a>. He has worked at DAMO Academy, Alibaba Group as a research intern supervised by Prof. <a href="https://www.yukaicheng.cn/"> Kaicheng Yu</a> and Prof. <a href="https://kunyuan827.github.io/"> Kun Yuan</a> from 2022.05 to 2023.06. Before the PhD career, he has also joined Autonomous Driving Laboratory, JD.COM as a full-time algorithm engineer supervised by Dr. <a href="https://scholar.google.com.hk/citations?user=_SXu32gAAAAJ&hl=zh-CN&oi=ao/"> Xinyu Xu</a> from 2018.06 to 2020.07.

My research spans the tasks of 3D object detection, 3D multi-object tracking, occupancy prediction and semi-supervised learning, all aimed at achieving accurate and robust perception for Level 5 autonomous driving.

<b>Fields:</b> Computer Vision, Autonomous Driving, Vehicle-Infrastructure Cooperation <br />
<b>Topics:</b> Vision-centric Perception, 3D Object Detection, Multi-modal Fusion, Semi-supervised Learning

<span class='anchor' id='news'></span>

# News
- *2023.09*: One paper is accepted by <b>TITS 2023!</b>
- *2023.08*: One paper is accepted by <b>TCSVT 2023!</b>
- *2023.07*: One paper is accepted by <b>ICCV 2023!</b>
- *2023.06*: One paper is accepted by <b>TITS 2023!</b>
- *2023.04*: One paper is accepted by <b>TCSVT 2023!</b>
- *2023.03*: One paper is accepted by <b>CVPR 2023!</b>
- *2023.03*: One paper is accepted by <b>KBS 2023!</b>

<span class='anchor' id='publications'></span>

# Publications 

[//]: # (----------- CVPR 2023 -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/CVPR23_BEVHeight.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b> BEVHeight: A Robust Framework for Vision-based Roadside 3D Object Detection </b>

[//]: # (<strong><span class='show_paper_citations' data='ElujT6oAAAAJ:hqOjcs7Dif8C'></span></strong>)
<u><b>Lei Yang</b></u>, Kaicheng Yu, Tao Tang, Jun Li, Kun Yuan, Li Wang, Xinyu Zhang, Peng Chen.

<i>IEEE Conference on Computer Vision and Pattern Recognition (<b>CVPR</b>), 2023</i>

<a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Yang_BEVHeight_A_Robust_Framework_for_Vision-Based_Roadside_3D_Object_Detection_CVPR_2023_paper.pdf">[Paper]</a> <a href="https://github.com/ADLab-AutoDrive/BEVHeight">[Code]</a> <a href="https://mp.weixin.qq.com/s/dLzZOEFfjBmLQ2iv041oxw">[Blog]</a> <a href="https://scholar.googleusercontent.com/scholar.bib?q=info:2luZ8BuEgN8J:scholar.google.com/&output=citation&scisdr=Cm1glQeJEPG9riE6yO8:AGlGAw8AAAAAZIA80O9jVSfqal3uL4vf2p2Rm_c&scisig=AGlGAw8AAAAAZIA80DDZ1XCX-OXEz6g4SqICmj8&scisf=4&ct=citation&cd=-1&hl=zh-CN">[BibTex]</a> 

</div>
</div>

[//]: # (----------- TCSVT 2023 -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2023</div><img src='images/TCSVT_Mix-Teaching.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b> Mix-Teaching: A simple, unified and effective semi-supervised learning framework for monocular 3d object detection </b>

[//]: # (<strong><span class='show_paper_citations' data='ElujT6oAAAAJ:hqOjcs7Dif8C'></span></strong>)
<u><b>Lei Yang</b></u>, Xinyu Zhang, Jun Li, Li Wang, Minghan Zhu, Chuang Zhang, Huaping Liu.

<i>IEEE Transactions on Circuits and Systems for Video Technology (<b>TCSVT</b>), 2023</i>

<a href="https://ieeexplore.ieee.org/abstract/document/10108965/">[Paper]</a> <a href="https://github.com/yanglei18/Mix-Teaching">[Code]</a> <a href="https://mp.weixin.qq.com/s/Gy54IfC_sm_FYonNh-GjiA">[Blog]</a> <a href="https://scholar.googleusercontent.com/scholar.bib?q=info:EyoJqWJkHWQJ:scholar.google.com/&output=citation&scisdr=Cm0htxMyELDKgN-e_JI:AGlGAw8AAAAAZH6Y5JL51RxV6e0RparGHyZYDfs&scisig=AGlGAw8AAAAAZH6Y5P90KbVHYWIjovQg3LtyPYc&scisf=4&ct=citation&cd=-1&hl=zh-CN">[BibTex]</a> 

</div>
</div>

[//]: # (----------- KBS 2023 -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KBS 2023</div><img src='images/KBS_Lite-FPN.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b> Lite-FPN for keypoint-based monocular 3d object detection </b>

[//]: # (<strong><span class='show_paper_citations' data='ElujT6oAAAAJ:hqOjcs7Dif8C'></span></strong>)
<u><b>Lei Yang</b></u>, Xinyu Zhang, Jun Li, Li Wang, Minghan Zhu, Lei Zhu.

<i>Knowledge-Based Systems (<b>KBS</b>), 2023</i>

<a href="https://www.sciencedirect.com/science/article/pii/S0950705123002678">[Paper]</a> <a href="https://github.com/yanglei18/Lite-FPN">[Code]</a> <a href="https://mp.weixin.qq.com/template/article/1696496478/index.html">[Blog]</a> <a href="https://scholar.googleusercontent.com/scholar.bib?q=info:lEao1LiWr98J:scholar.google.com/&output=citation&scisdr=Cm1glQeJEPG9riE6YHg:AGlGAw8AAAAAZIA8eHie_yTlDjLcI_t5s7KapRk&scisig=AGlGAw8AAAAAZIA8eH0ruHFo02rSBYicDcUohdA&scisf=4&ct=citation&cd=-1&hl=zh-CN">[BibTex]</a> 

</div>
</div>

[//]: # (----------- arXiv preprint -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv preprint</div><img src='images/Arxiv_BEVHeight++.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b> BEVHeight++: Toward Robust Visual Centric 3D Object Detection </b>

[//]: # (<strong><span class='show_paper_citations' data='ElujT6oAAAAJ:hqOjcs7Dif8C'></span></strong>)
<u><b>Lei Yang</b></u>, Tao Tang, Jun Li, Peng Chen, Kun Yuan, Li Wang, Xinyu Zhang, Kaicheng Yu.

<i>arXiv preprint, 2023</i>

<a href="https://arxiv.org/pdf/2309.16179.pdf">[Paper]</a> <a href="https://mp.weixin.qq.com/s/AdCXYzHIy2lTfAHk2AZ4_w">[Blog]</a> <a href="https://scholar.googleusercontent.com/scholar.bib?q=info:533Lb1iszaQJ:scholar.google.com/&output=citation&scisdr=ClECxAehELDKgb6hoVE:AFWwaeYAAAAAZR-nuVE7kT8jhMi9ZzOe_DvX9vc&scisig=AFWwaeYAAAAAZR-nuYuq-tLt1hJmn5apiURpBKI&scisf=4&ct=citation&cd=-1&hl=zh-CN">[BibTex]</a> 

</div>
</div>

[//]: # (----------- arXiv preprint -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv preprint</div><img src='images/Arxiv_preprint_MonoGAE.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b> MonoGAE: Roadside Monocular 3D Object Detection with Ground-Aware Embeddings </b>

[//]: # (<strong><span class='show_paper_citations' data='ElujT6oAAAAJ:hqOjcs7Dif8C'></span></strong>)
<u><b>Lei Yang</b></u>, Jiaxin Yu, Xinyu Zhang, Jun Li, Li Wang, Yi Huang, Chuang Zhang, Yiming Li.

<i>arXiv preprint, 2023</i>

<a href="https://arxiv.org/pdf/2310.00400.pdf">[Paper]</a> <a href="https://scholar.googleusercontent.com/scholar.bib?q=info:lEao1LiWr98J:scholar.google.com/&output=citation&scisdr=Cm1glQeJEPG9riE6YHg:AGlGAw8AAAAAZIA8eHie_yTlDjLcI_t5s7KapRk&scisig=AGlGAw8AAAAAZIA8eH0ruHFo02rSBYicDcUohdA&scisf=4&ct=citation&cd=-1&hl=zh-CN">[BibTex]</a>

</div>
</div>

[//]: # (----------- ICCV 2023 -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/ICCV23_GraphAlign.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b> GraphAlign: Enhancing Accurate Feature Alignment by Graph matching for Multi-Modal 3D Object Detection </b>

[//]: # (<strong><span class='show_paper_citations' data='ElujT6oAAAAJ:hqOjcs7Dif8C'></span></strong>)
Ziying Song, Haiyue Wei, Lin Bai, <u><b>Lei Yang</b></u>, Caiyan Jia.

<i>International Conference on Computer Vision (<b>ICCV</b>), 2023</i>

<a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Song_GraphAlign_Enhancing_Accurate_Feature_Alignment_by_Graph_matching_for_Multi-Modal_ICCV_2023_paper.pdf">[Paper]</a> <a href="https://scholar.googleusercontent.com/scholar.bib?q=info:a07KInI_iJ8J:scholar.google.com/&output=citation&scisdr=ClECxAehELDKgb6u_xQ:AFWwaeYAAAAAZR-o5xTJRglSYlODfLhHwsYIjsE&scisig=AFWwaeYAAAAAZR-o5wBrstQbd0Nvqg_giATrQSY&scisf=4&ct=citation&cd=-1&hl=zh-CN">[BibTex]</a> 

</div>
</div>

[//]: # (----------- TCSVT 2023 -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2023</div><img src='images/TCSVT23_GraphAlign++.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b> GraphAlign++: An Accurate Feature Alignment by Graph Matching for Multi-Modal 3D Object Detection </b>

[//]: # (<strong><span class='show_paper_citations' data='ElujT6oAAAAJ:hqOjcs7Dif8C'></span></strong>)
Ziying Song, Caiyan Jia, <u><b>Lei Yang</b></u>, Haiyue Wei, Lin Liu.

<i>IEEE Transactions on Circuits and Systems for Video Technology (<b>TCSVT</b>), 2023</i>

<a href="https://ieeexplore.ieee.org/abstract/document/10224545">[Paper]</a> <a href="https://scholar.googleusercontent.com/scholar.bib?q=info:zsU2J08p_JcJ:scholar.google.com/&output=citation&scisdr=ClHxIjv2EPG9rleM6eE:AFWwaeYAAAAAZPaK8eB84UCk8o_JlwKOX57Ku7s&scisig=AFWwaeYAAAAAZPaK8UDz0m0OADwI3i_e9LOJvz4&scisf=4&ct=citation&cd=-1&hl=zh-CN">[BibTex]</a> 

</div>
</div>

[//]: # (----------- TITS 2023 -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TITS 2023</div><img src='images/TITS23_CAMO-MOT.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b> CAMO-MOT: Combined Appearance-Motion Optimization for 3D Multi-Object Tracking with Camera-LiDAR Fusion </b>

[//]: # (<strong><span class='show_paper_citations' data='ElujT6oAAAAJ:hqOjcs7Dif8C'></span></strong>)
Li Wang, Xinyu Zhang, Wenyuan Qin, Xiaoyu Li, <u><b>Lei Yang</b></u>, Zhiwei Li, Lei Zhu, Hong Wang, Jun Li, Huaping Liu.

<i>IEEE Transactions on Intelligent Transportation Systems (<b>TITS</b>), 2023</i>

<a href="https://ieeexplore.ieee.org/abstract/document/10093116">[Paper]</a> <a href="https://github.com/adept-thu/CAMO-MOT">[Code]</a> <a href="https://mp.weixin.qq.com/s/0nz2jBYs6vAFoTFtqjdE7A">[Blog]</a> <a href="https://scholar.googleusercontent.com/scholar.bib?q=info:o-octXc6o90J:scholar.google.com/&output=citation&scisdr=ClHX4Zm0ELDKgZcsXhk:AFWwaeYAAAAAZTYqRhmrh8hwhZrfEor_pOTwiAY&scisig=AFWwaeYAAAAAZTYqRvo6BYsA3i75VDtwkncyvpw&scisf=4&ct=citation&cd=-1&hl=zh-CN">[BibTex]</a> 

</div>
</div>

[//]: # (----------- TITS 2023 -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TITS 2023</div><img src='images/TITS23_Attention-Track.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b> AttentionTrack: Multiple Object Tracking in Traffic Scenarios Using Features Attention </b>

[//]: # (<strong><span class='show_paper_citations' data='ElujT6oAAAAJ:hqOjcs7Dif8C'></span></strong>)
Chuang Zhang, Sifa Zheng, Haoran Wu, Ziqing Gu, Wenchao Sun, <u><b>Lei Yang.</b></u>

<i>IEEE Transactions on Intelligent Transportation Systems (<b>TITS</b>), 2023</i>

<a href="https://ieeexplore.ieee.org/abstract/document/10260285">[Paper]</a> <a href="https://scholar.googleusercontent.com/scholar.bib?q=info:sydp0k3Rt_QJ:scholar.google.com/&output=citation&scisdr=ClECxAehELDKgb6ub4w:AFWwaeYAAAAAZR-od4x3bx0GbTNHwl-XN-PIKOw&scisig=AFWwaeYAAAAAZR-odxfvRYd5GB2bJSlIF5cqu44&scisf=4&ct=citation&cd=-1&hl=zh-CN">[BibTex]</a> 

</div>
</div>

[//]: # (----------- TIV 2023 -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIV 2023</div><img src='images/TIV23_Survey.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b> Multi-Modal 3D Object Detection in Autonomous Driving: A Survey and Taxonomy </b>

[//]: # (<strong><span class='show_paper_citations' data='ElujT6oAAAAJ:hqOjcs7Dif8C'></span></strong>)
Li Wang, Xinyu Zhang, Ziying Song, Jiangfeng Bi, Guoxin Zhang, Haiyue Wei, Liyao Tang, <u><b>Lei Yang</b></u>, Jun Li, Caiyan Jia, Lijun Zhao.

<i>IEEE Transactions on Intelligent Vehicles (<b>TIV</b>), 2023.</i>

<a href="https://ieeexplore.ieee.org/abstract/document/10093116">[Paper]</a> <a href="https://zhuanlan.zhihu.com/p/627874944">[Blog]</a> <a href="https://scholar.googleusercontent.com/scholar.bib?q=info:ZlszHY0WQZ4J:scholar.google.com/&output=citation&scisdr=Cm0htxMyEPG9rt-ihzA:AGlGAw8AAAAAZH6knzByEsKzJoFqxX5mJtu_k7c&scisig=AGlGAw8AAAAAZH6kn3MGJd8WqJfBN_J8MZZjO7I&scisf=4&ct=citation&cd=-1&hl=zh-CN">[BibTex]</a> 

</div>
</div>

[//]: # (----------- TIV 2022 -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIV 2022</div><img src='images/TIV22_Parking.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b> Global perception-based robust parking space detection using a low-cost camera </b>

[//]: # (<strong><span class='show_paper_citations' data='ElujT6oAAAAJ:hqOjcs7Dif8C'></span></strong>)
Li Wang, Xinyu Zhang, Weijia Zeng, Wei Liu, <u><b>Lei Yang</b></u>, Jun Li, Huaping Liu.

<i>IEEE Transactions on Intelligent Vehicles (<b>TIV</b>), 2022.</i>

<a href="https://ieeexplore.ieee.org/abstract/document/9806359">[Paper]</a> <a href="https://scholar.googleusercontent.com/scholar.bib?q=info:uCGHmry-DkcJ:scholar.google.com/&output=citation&scisdr=Cm0htxMyEPG9rt-idLk:AGlGAw8AAAAAZH6kbLmsUnAC5A6KicBT3qlfzro&scisig=AGlGAw8AAAAAZH6kbPrZk60FaWJEfSnES2C_FTA&scisf=4&ct=citation&cd=-1&hl=zh-CN">[BibTex]</a> 

</div>
</div>


[//]: # (----------- TIV 2022 -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIV 2022</div><img src='images/TIV23_Survey_Flight.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b> Intelligent amphibious ground-aerial vehicles: State of the art technology for future transportation </b>

[//]: # (<strong><span class='show_paper_citations' data='ElujT6oAAAAJ:hqOjcs7Dif8C'></span></strong>)
Xinyu Zhang, Jiangeng Huang, Yuanhao Huang, Kangyao Huang, <u><b>Lei Yang</b></u>, Yan Han, Li Wang,  Huaping Liu, Jianxi Luo, Jun Li.

<i>IEEE Transactions on Intelligent Vehicles (<b>TIV</b>), 2022.</i>

<a href="https://ieeexplore.ieee.org/abstract/document/9839587">[Paper]</a> <a href="https://scholar.googleusercontent.com/scholar.bib?q=info:dFdW_cIAmHcJ:scholar.google.com/&output=citation&scisdr=Cm0htxMyELDKgN-fMk8:AGlGAw8AAAAAZH6ZKk8_MaLp_dAWmFg8FBZM8NA&scisig=AGlGAw8AAAAAZH6ZKtvxP_Pqzr9so573TFm3y9k&scisf=4&ct=citation&cd=-1&hl=zh-CN">[BibTex]</a> 

</div>
</div>

[//]: # (----------- TVT 2022 -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TVT 2022</div><img src='images/TVT22_M2-Fusion.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b> Multi-Modal and Multi-Scale Fusion 3D Object Detection of 4D Radar and LiDAR for Autonomous Driving </b>

[//]: # (<strong><span class='show_paper_citations' data='ElujT6oAAAAJ:hqOjcs7Dif8C'></span></strong>)
Li Wang, Xinyu Zhang, Jun Li, Baowei Xv, Rong Fu, Haifeng Chen, <u><b>Lei Yang</b></u>, Dafeng Jin, Lijun Zhao.

<i>IEEE Transactions on Vehicular Technology (<b>TVT</b>), 2022.</i>

<a href="https://ieeexplore.ieee.org/abstract/document/9991894">[Paper]</a> <a href="https://scholar.googleusercontent.com/scholar.bib?q=info:eBsPAJyrxK0J:scholar.google.com/&output=citation&scisdr=Cm0htxMyELDKgN-fUK4:AGlGAw8AAAAAZH6ZSK527w0MsOcbjpxCB55qBrI&scisig=AGlGAw8AAAAAZH6ZSKNcTFLBc1AKsHdFLLCxVeI&scisf=4&ct=citation&cd=-1&hl=zh-CN">[BibTex]</a> 

</div>
</div>

<span class='anchor' id='Datasets'></span>

# Datasets
[//]: # (----------- arXiv preprint -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv preprint</div><img src='images/Arxiv_preprint_Dual-Radar.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b> Dual Radar: A Multi-modal Dataset with Dual 4D Radar for Autononous Driving </b>

Dual-Radar is a brand new dataset based on 4D radar that can be used for studies on deep learning object detection and tracking in the field of autonomous driving. The system of ego vehicle includes a high-resolution camera, a 80-line LiDAR and two up-to-date and different models of 4D radars operating in different modes(Arbe and ARS548).

<i>arXiv preprint, 2023</i>

<a href="https://arxiv.org/pdf/2310.07602.pdf">[Paper]</a> <a href="https://github.com/adept-thu/Dual-Radar">[Preject & Code]</a> <a href="https://mp.weixin.qq.com/s/ybKdsI00sZU-YPkgcRwv3w">[Blog]</a> <a href="https://scholar.googleusercontent.com/scholar.bib?q=info:1LUiZTfE2jwJ:scholar.google.com/&output=citation&scisdr=ClEJsmBAELDKgZcdBUk:AFWwaeYAAAAAZTYbHUmZyg1CHZqDv_ww2gUld7w&scisig=AFWwaeYAAAAAZTYbHR0RxadsyVR743yCCHuu20U&scisf=4&ct=citation&cd=-1&hl=zh-CN">[BibTex]</a> 

</div>
</div>

[//]: # (----------- arXiv preprint -------------------------)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv preprint</div><img src='images/Arxiv_preprint_IPS300+.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<b> IPS300+: a Challenging Multimodal Dataset for Intersection Perception System </b>

IPS300+ is the first multimodal dataset available for roadside perception tasks in large-scale urban intersection scene, which is the most challenging dataset with the highest label density. 

<i>arXiv preprint, 2021</i>

<a href="https://arxiv.org/ftp/arxiv/papers/2106/2106.02781.pdf">[Paper]</a> <a href="http://openmpd.com/column/IPS300">[Preject & Code] <a href="https://scholar.googleusercontent.com/scholar.bib?q=info:gxLwOipuC3sJ:scholar.google.com/&output=citation&scisdr=ClHX4Zm0ELDKgZclWn4:AFWwaeYAAAAAZTYjQn4VPkNQjm5JPQhhn_AvDFM&scisig=AFWwaeYAAAAAZTYjQuprAhZ1grEXSrqINSz5zQU&scisf=4&ct=citation&cd=-1&hl=zh-CN">[BibTex]</a> 

</div>
</div>


<span class='anchor' id='service'></span>

# Service
- Reviewer of IEEE T-CSVT, CVPR, ICRA


[//]: # (**Contact:** yanglei20@mails.tsinghua.edu.cn)

[//]: # (<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=UA1prgTfM8f4KdsTtZDKPAqAagf4Sr6L0d9xRVyOdrE&cl=ffffff&w=300"></script>)

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=280&t=n&d=ALU32QyDXPeh-sF2onF5lOjhOQxpLsAeR9KhZdbBC-Q'></script>

[//]: # (<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=0BIYeBsibdR2LYwdkZWai6r2NccfTZ96HDqvr9WYt9s&cl=ffffff&w=a"></script>)