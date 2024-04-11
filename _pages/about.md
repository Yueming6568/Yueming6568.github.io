---
permalink: /
title: "Songlin Yang"
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

I am a final-year Master's student at [Center for Research on Intelligent Perception and Computing](http://cripac.ia.ac.cn/CN/model/index.htm) in [Institute of Automation, Chinese Academy of Sciences](http://www.ia.cas.cn/). Before this, I obtained my Bachelor Degree of Automation Engineering in Nanjing University of Aeronautics and Astronautics with Honors Distinction. I am fortunate to have internships at serveral leading research institutions, including MicroSoft Research Asia and SenseTime Research. I am an IEEE Student Member and serve as Publicity Chair for [IEEE Beijing Biometrics Council Chapter](https://r10.ieee.org/beijing-bio/) from 2021.

<font color="blue">My previous research mainly focused on three aspects: </font>
  - **Face Neural Rendering**: Talking-Head Video Generation, Face Reenactment, and Facial Attribute Editing
  - **Text-to-Image Face Analysis**: Personalization and Identity Erasure
  - **Robust Face Recognition System**: De-Identification, Anti-Spoofing, and Deepfake Detection  

I have extensive experience in studying the NeRF-based motion transfer and diffusion-based human-centric generation. Also, I am conducting cutting-edge research in 3D Human-Object Interaction Tracking for my possible PhD program.  

<font color="red">Do not hesitate to drop me an email for any possible collaboration if you are interested in these directions:</font>
  - Generative Models
  - 3D Human Motion and Human-Object-Scene Interaction
  - Face Synthesis and Analysis
  - Neural Rendering
  - Physics-Aware Content Generation
  - Robotics and Embodied Intelligence

# 🔈**Looking for a PhD Position!**

I embrace Richard Feynman's dictum, "What I can not create, I do not understand," as it aligns with my research goal, which is generating human-centric visual content to understand ourselves. I will continue to conduct research at the intersection of computer vision and graphics. Specifically, I plan to employ generative models to enhance human-computer interaction, based on technical expertise accumulated through my collaboration with 3D human-related researchers over the past year. Let's embark on our journey towards a technologically-advanced era of immersive human-object/scene interaction!

# 🔥 News
- 2024/03: One paper is accepted by [ICME 2024](https://2024.ieeeicme.org/).  
- 2023/12: One paper is accepted by [AAAI 2024](https://aaai.org/aaai-conference/).
- 2023/10: I am granted by National Scholarship (Graduate). What a fierce competition!
- 2023/07: One paper is accepted by [MM 2023](https://www.acmmm2023.org/).
- 2023/04: One paper is accepted by [CVPR 2023 Biometrics Workshop](https://www.vislab.ucr.edu/Biometrics2023/index.php).
- 2023/02: One paper is accepted by [ICASSP 2023](https://2023.ieeeicassp.org/).
- 2021/10: One paper is accepted by [CCBR 2021](https://ccbr99.cn/).

# 📖 Education

- **M.S. in Pattern Recognition and Intelligent Systems, [CRIPAC Department](http://cripac.ia.ac.cn/CN/model/index.htm), [CASIA Institute](http://www.ia.cas.cn/)**  
  Sep. 2021 - Jun. 2024
  Supervior: [Prof. Wei Wang](http://cripac.ia.ac.cn/people/wwang/#photos) (Co-Supervied by [Prof. Jing Dong](http://cripac.ia.ac.cn/people/jdong/) and [Prof. Bo Peng](http://cripac.ia.ac.cn/en/EN/column/item139.shtml))
  Thesis: Dynamic Facial Editing based on Neural Radiance Fields  
  GPA: 3.82/4.0 (National Scholarship)  

- **B.E. in Automation Engineering, Nanjing University of Aeronautics and Astronautics**  
  Sep. 2017 - Jun. 2021  
  Thesis: Face De-Identification based on Generative Adversarial Networks (Province Award)  
  GPA: 4.4/5.0 (Rank: 1/204, Honors Distinction)  

# 💻 Work Experience

- **Research Intern, Content Generation Group, SenseTime Research**  
  Sep. 2022 - Aug. 2023  
  Supervised by [Xiangyu Fan](https://events.keep.edu.hk/cuhk/engg5700/2017/team/fan-xiangyu/) and [Lei Yang](https://scholar.google.com/citations?hl=zh-CN&user=jZH2IPYAAAAJ).
  
 - **Research Intern, Machine Learning Group, MicroSoft Research Asia**  
  Mar. 2022 - Aug. 2022  
  Supervised by [Xu Tan](https://scholar.google.com/citations?user=tob-U1oAAAAJ&hl=zh-CN&oi=ao) and [Jun Ling](https://scholar.google.com/citations?hl=zh-CN&user=XsfjhQ0AAAAJ).
  
 - **Research Intern, Identity Verification Group, SenseTime Research**   
  Jun. 2021 - Sep. 2021  
  Supervised by Chenye Xu and [Yichao Wu](https://scholar.google.com/citations?hl=zh-CN&user=20Its9kAAAAJ).

# 📝 Publications - Face Neural Rendering

  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/publications/AAAI2024.gif' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  
  **Learning Dense Correspondence for NeRF-Based Face Reenactment**
  
  **Songlin Yang**, [Wei Wang](http://cripac.ia.ac.cn/people/wwang/index.html), [Yushi Lan](https://nirvanalan.github.io/), [Xiangyu Fan](https://events.keep.edu.hk/cuhk/engg5700/2017/team/fan-xiangyu/), [Bo Peng](http://cripac.ia.ac.cn/en/EN/column/item139.shtml), [Lei Yang](https://scholar.google.com/citations?hl=zh-CN&user=jZH2IPYAAAAJ), [Jing Dong](http://cripac.ia.ac.cn/people/jdong/)  
  
  [Proceedings of the AAAI Conference on Artificial Intelligence](https://aaai.org/aaai-conference/), 2024  
  [Paper](https://arxiv.org/pdf/2312.10422.pdf) [Project](https://songlin1998.github.io/planedict/)
  
  </div>
  </div>

  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/publications/MM2023.gif' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  
  **Context-Aware Talking-Head Video Editing**
  
  **Songlin Yang**, [Wei Wang](http://cripac.ia.ac.cn/people/wwang/index.html), [Jun Ling](https://scholar.google.com/citations?hl=zh-CN&user=XsfjhQ0AAAAJ), [Bo Peng](http://cripac.ia.ac.cn/en/EN/column/item139.shtml), [Xu Tan](https://scholar.google.com/citations?user=tob-U1oAAAAJ&hl=zh-CN&oi=ao), [Jing Dong](http://cripac.ia.ac.cn/people/jdong/)  
  
  [Proceedings of the 31st ACM International Conference on Multimedia](https://www.acmmm2023.org/), 2023  
  [Paper](https://dl.acm.org/doi/abs/10.1145/3581783.3611765) [Project](https://songlin1998.github.io/THEdit/)
  
  </div>
  </div>

  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2023</div><img src='images/publications/ICASSP.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  
  **Designing a 3D-Aware StyleNeRF Encoder for Face Editing**
  
  **Songlin Yang**, [Wei Wang](http://cripac.ia.ac.cn/people/wwang/index.html), [Bo Peng](http://cripac.ia.ac.cn/en/EN/column/item139.shtml), [Jing Dong](http://cripac.ia.ac.cn/people/jdong/) 
  
  [IEEE International Conference on Acoustics, Speech, and Signal Processing](https://2023.ieeeicassp.org/), 2023 
  
  [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10094932)   
  
  </div>
  </div>
  
# 📝 Publications - Face Manifold of Text-to-Image Diffusion Models

  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/publications/cvpr24.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">

  **Beyond Inserting: Learning Identity Embedding for Semantic-Fidelity Personalized Diffusion Generation**
  
  Yang Li\*, **Songlin Yang**\*, [Wei Wang](http://cripac.ia.ac.cn/people/wwang/index.html), [Jing Dong](http://cripac.ia.ac.cn/people/jdong/)  
  (\* Equal Contribution)  
  
  [Paper](https://arxiv.org/pdf/2402.00631.pdf) [Project](https://com-vis.github.io/SeFi-IDE/)  
  </div>
  </div>

# 📝 Publications - Robust Face Recognition Systems

  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR-W 2023</div><img src='images/publications/CVPRW23.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  
  **Exposing Fine-Grained Adversarial Vulnerability of Face Anti-Spoofing Models**
  
  **Songlin Yang**, [Wei Wang](http://cripac.ia.ac.cn/people/wwang/index.html), Chenye Xu, [Ziwen He](https://scholar.google.com/citations?user=PjkDK9cAAAAJ&hl=zh-CN&oi=sra), [Bo Peng](http://cripac.ia.ac.cn/en/EN/column/item139.shtml), [Jing Dong](http://cripac.ia.ac.cn/people/jdong/) 
  
  [IEEE Conference on Computer Vision and Pattern Recognition (CVPR)](https://cvpr2023.thecvf.com/) [Workshop](https://www.vislab.ucr.edu/Biometrics2023/index.php), 2023  
  **Long Oral Presentation**  
  [Paper](https://arxiv.org/pdf/2205.14851.pdf) 
  
  </div>
  </div>
  
  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCBR 2021</div><img src='images/publications/CCBR21.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  
  **A Systematical Solution for Face De-Identification**
  
  **Songlin Yang**, [Wei Wang](http://cripac.ia.ac.cn/people/wwang/index.html), Yuehua Cheng, [Jing Dong](http://cripac.ia.ac.cn/people/jdong/) 
  
  [Chinese Conference on Biometric Recognition](https://ccbr99.cn/2021/), 2021  
  
  [Paper](https://link.springer.com/chapter/10.1007/978-3-030-86608-2_3)  
  
  </div>
  </div>
  
  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/publications/tomm24.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  
  **Is It Possible to Backdoor Face Forgery Detection with Natural Triggers?**
  
  Xiaoxuan Han, **Songlin Yang**, [Wei Wang](http://cripac.ia.ac.cn/people/wwang/index.html), [Ziwen He](https://scholar.google.com/citations?user=PjkDK9cAAAAJ&hl=zh-CN&oi=sra), [Jing Dong](http://cripac.ia.ac.cn/people/jdong/)  

  [Paper](https://arxiv.org/pdf/2401.00414.pdf)  
  
  </div>
  </div>
  
  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2024</div><img src='images/publications/icme24.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  
  **Counterfactual Explanations for Face Forgery Detection via Adversarial Removal of Artifacts**  
  
  Yang Li\*, **Songlin Yang**\*, [Wei Wang](http://cripac.ia.ac.cn/people/wwang/index.html), [Ziwen He](https://scholar.google.com/citations?user=PjkDK9cAAAAJ&hl=zh-CN&oi=sra), [Bo Peng](http://cripac.ia.ac.cn/en/EN/column/item139.shtml), [Jing Dong](http://cripac.ia.ac.cn/people/jdong/)  
   (\* Equal Contribution)  

   [IEEE International Conference on Multimedia and Expo (ICME)](https://2024.ieeeicme.org/), 2024  
  
  </div>
  </div>

# 🎖️ Awards

- National Scholarship (Graduate). 2023
- National Scholarship (Bachelor). 2018
- Outstanding Graduate of Jiangsu Province. 2021
- Outstanding Bachelor Thesis Award of Jiangsu Province. 2021
- Outstanding Student of University of Chinese Academy of Sciences. 2022, 2023
- Outstanding Graduate of Nanjing University of Aeronautics and Astronautics. 2021
- Scholarship of Aviation Industry Corporation of China. 2019, 2020
- President Scholarship of Nanjing University of Aeronautics and Astronautics. 2020
- First Class Scholarship for Academic Excellence. 2017, 2018, 2019, 2020

# 🕴️ Professional Services

- Publicity Chair for [IEEE Beijing Biometrics Council Chapter](https://r10.ieee.org/beijing-bio/).
- Conference Reviewer
  - AAAI (2023, 2024)
  - CVPR (2022, 2023, 2024)
  - ECCV (2022, 2024)
  - ICME (2024)
  - IJCB (2022)
  - ICASSP (2024)
- Journal Reviewer
  - IEEE Transactions on Multimedia (TMM)
  - ACM Transactions on Multimedia Computing, Communications, and Applications (TOMM)

<script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=7vdDMk61HlQEKQd8AYn5-S0oCuWHWu5PXdYVUfgjX4I&cl=ffffff&w=300"></script>
