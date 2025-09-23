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
# 👨‍🎓 About Me
I am currently pursuing my Ph.D. in the [Elmore Family School of Electrical and Computer Engineering](https://engineering.purdue.edu/ECE) at [**Purdue University**](https://www.purdue.edu/), under the supervision of [Prof. Lingxi Li](https://engineering.purdue.edu/ECE/People/Faculty/Indianapolis/ptProfile?resource_id=296655&group_id=87916) and [Prof. Satish Ukkusuri](https://umnilab.github.io/?_ga=2.262274188.1279605593.1758417719-1924412767.1752791020). Prior to this, I received my Master’s degree from [**Shanghai Jiao Tong University (SJTU)**](https://en.sjtu.edu.cn/), under the guidance of [Prof. Dewei Li](https://scholar.google.com/citations?user=mLSocOwAAAAJ&hl=en&oi=ao) and [Dr. Yunwen Xu](https://scholar.google.com/citations?user=7eLzr2sAAAAJ&hl=en&oi=ao) at [CSC Lab](https://english.csc-lab.com/en/). 

My current research interests lie at the intersection of control, optimization, and learning, with their applications to *cooperative driving automation*, *traffic control* and *intelligent transportation systems*. If you share similar interests and have any interesting questions, feel free to email me 📬 at [yang3062@purdue.edu](mailto:yang3062@purdue.edu)!

<!--My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).-->


# 🔥 News
- *2025.09*: &nbsp;🎉 My [first-author paper](https://ieeexplore.ieee.org/document/11175582) has been accepted by IEEE-TITS.
- *2025.08*: &nbsp;🛫 Arrived in West Lafayette, IN — the Ph.D. journey begins!
<!--*2025.01*: &nbsp; I have received the [2024 Theoretical Innovation Award](https://drive.google.com/file/d/1EhJjKccHYxAGgvtBB8RdmE9MKjYZrHlK/view?usp=drive_link) from [CSC Lab](https://english.csc-lab.com/en/). Thank you to my professors for their encouragement. 🥳-->
- *2024.09*: &nbsp;🎉 My [first-author paper](https://ieeexplore.ieee.org/document/10709851) has been accepted by IEEE-TITS.


# 📝 Publications 

<!--<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>-->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TITS</div><img src='images/VF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Valve Fleets: A Novel Control Method for Mixed Traffic Flow Regulation with Applications in Bottleneck Segments](https://ieeexplore.ieee.org/document/11175582), 

**Siwen Yang**, Yunwen Xu, and Dewei Li. 

**IEEE Transactions on Intelligent Transportation Systems**, (IEEE TITS), 2025.
- proposed a mixed traffic flow control structure, utilizing multi-lane fleets composed of a small portion of CAVs in mixed flow as mobile actuators. Multiple fleets formed within the mixed traffic flow feature a novel structure and a valve-like function that regulates both traffic volume and speed, referred to as "valve fleets", which are applied to decongest freeway bottlenecks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TITS</div><img src='images/MPC-MPF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Efficient Rolling-Horizon Approach for Cooperative Multi-Lane Platoon Formation With Undefined Configurations](https://ieeexplore.ieee.org/document/10709851), 

**Siwen Yang**, Yunwen Xu, Ping Wang, and Dewei Li. 

**IEEE Transactions on Intelligent Transportation Systems**, (IEEE TITS), 2024.
- Proposed a multi-lane platoon formation scheme that coordinates the lane-changing decisions and longitudinal trajectories of CAVs to form platoons based on each vehicle's target lane, aiming to reduce the negative impact of lane-changing maneuvers on traffic flow and improve platoon formation efficiency. The platoon configurations and vehicles' motions are jointly optimizaed dynamically to enhance flexibility.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ITSC 2023</div><img src='images/itsc2023_presentation.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Trajectory Optimization for Multi-Lane Platoon Formation with Undefined Configurations](https://ieeexplore.ieee.org/document/10422641), 

**Siwen Yang**, Yunwen Xu, Dewei Li, and Chen Zhang.

**IEEE 26th International Conference on Intelligent Transportation Systems** (ITSC 2023) | [**Slides**](https://drive.google.com/file/d/1_MdqCLhpxTC6DYeGvIBlNbbrKR710ODG/view?usp=drive_link)
- Proposed a trajectory optimization method for platoon formation that assigns and regulates vehicles distributed across different lanes into platoons with undefined vehicular sequences, aiming to reduce vehicle delays and time consumption.
</div>
</div>

<!--<span style="display: inline-block; background-color: #00369F; color: white; padding: 0.0em 1.2em; font-size: 12px; margin-right: 6px;">CVPR 2020</span>
[Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C.-->


# 🎖 Honors and Awards
### Scholarships:
- *2024.11*, First-Class Scholarship, Shanghai Jiao Tong University. 
- *2023.11*, First-Class Scholarship, Shanghai Jiao Tong University. 
- *2023.10*, [Pan Wen-Yuan Scholarship](https://pan.itri.org.tw/awards/scholarship.aspx?nid=A229B5EC5952C71E#2021), Shanghai Jiao Tong University & Pan Wen-Yuan Foundation.  
- *2022.11*, First-Class Scholarship, Shanghai Jiao Tong University. 
### Honors:
- *2024.12*, Outstanding Graduate, Shanghai Jiao Tong University.
- *2022.04*, Outstanding Graduate, Central South University.

# 📖 Educations
- *2022.09 - 2025.03*, **M.Eng. in Control Engineering**, *GPA: 3.95/4.0*, School of Electronic Information and Electrical Engineering, [**Shanghai Jiao Tong University**](https://en.sjtu.edu.cn/), Shanghai, China. 
- *2018.09 - 2022.06*, **B.Eng. in Automation**, *GPA: 91.9/100*, School of Automation, [**Central South University**](https://en.csu.edu.cn/), Changsha, China. 

<!--# 💬 Invited Talks
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)-->

# 💻 Experiences
- *2022.10 - 2023.12*, "Development of MPC-based Heat Pump Controller and Thermal Comfort Algorithm for New Energy Vehicles", **Collaborative Project** between [SJTU - CSC Lab](http://csc-lab.com/index) and [Thermalnology Hi-Tech Co., Ltd.](http://www.thermalnology.com/), Shanghai, China.
