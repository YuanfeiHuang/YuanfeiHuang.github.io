---
permalink: /
title: "About me"
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

I am a lecturer at the [School of Artificial Intelligence](https://ai.bnu.edu.cn/), Beijing Normal University, Beijing, China since 2021, where I work in the [Intelligent Media Computing Lab](https://vmcl.bnu.edu.cn/) led by Prof. [Hua Huang](https://ai.bnu.edu.cn/xygk/szdw/zgj/194482e0996d4044806ac39019896e9c.htm). I received my Ph.D. degree in 2021 from the [Video & Image Processing System Lab](https://see.xidian.edu.cn/vipsl/index.html), affiliated with the School of Electronic Engineering, Xidian University, Xi'an, China, under the supervision of Prof. [Xinbo Gao](https://web.xidian.edu.cn/xbgao/) and Prof. Jie Li.

My research interest includes computer vision and signal processing, with specialized expertise in: 
- *Image restoration*: super-resolution, denoising, etc.
- *Object Perception*: object detection and recognition in remote sensing imagery.

Location: Room 526, Library Building, Changping Campus, Beijing Normal University, Changping District, Beijing, China.

We are looking for self-motivated undergraduate interns, graduate students, and collaborators to join us. If you are interested, please email me with your resume.
*欢迎本科科研实习生，研究生加入我们团队！有意向的同学请发送邮件给我。*

# 🔥 News
**2025.07**, ***Condformer*** is accepted by IJCV.

**2025.07**, ***DeflareMamba*** is accepted by ACMMM 2025, congratulations to Yihang.

# 📝 Selected Publications 
***More are available in [Google Scholar](https://scholar.google.com/citations?user=HcwtiyUAAAAJ)***

<div class='paper-box' style="display: flex; width: 100%;"><div class='paper-box-image' style="flex: 0 0 30%;"><div>
<div class="badge" style="background-color: #3498db; color: white">IJCV 2025</div>  
<img src='images/2024arXiv_Condformer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' style="flex: 0 0 70%; padding-left: 20px;" markdown="1"> 

[Beyond Image Prior: Embedding Noise Prior into Conditional Denoising Transformer](https://arxiv.org/abs/2407.09094)
- **Yuanfei Huang**; Hua Huang
- *Accepted by IJCV*
- A new perspective on the denoising challenge by highlighting the distinct separation between noise and image priors.
- [**Code**](https://github.com/YuanfeiHuang/Condformer)

</div>  
</div>  

<div class='paper-box' style="display: flex; width: 100%;"><div class='paper-box-image' style="flex: 0 0 30%;"><div>
<div class="badge" style="background-color: #2ecc71; color: white">ACMMM 2025</div>  
<img src='images/2025ACMMM_DeflareMamba.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' style="flex: 0 0 70%; padding-left: 20px;" markdown="1"> 

[DeflareMamba: Hierarchical Vision Mamba for Contextually Consistent Lens Flare Removal]
- Yihang Huang; **Yuanfei Huang#**; Junhui Lin; Hua Huang
- *Accepted by ACMMM 2025*
- Introducing state space models to the flare removal task, which leverages the efficient sequence modeling capabilities of state space models while maintaining the ability to capture local-global dependencies.
- [**Code**](https://github.com/hyhsjd2/DeflareMamba)

</div>  
</div>  

<div class='paper-box' style="display: flex; width: 100%;"><div class='paper-box-image' style="flex: 0 0 30%;"><div>
<div class="badge" style="background-color: #FFA500; color: white">arXiv 2025</div>  
<img src='images/2025arXiv_WIN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' style="flex: 0 0 70%; padding-left: 20px;" markdown="1"> 

[Tackling Ill-posedness of Reversible Image Conversion with Well-posed Invertible Network]
- **Yuanfei Huang**; Hua Huang
- *Under Review*
- A well-posed invertible convolution by constructing an overdetermined system with a non-zero Gram determinant, enabling reliable invertible models and achieving state-of-the-art results on various reversible image conversion tasks, including image hiding/steganagraphy, image rescaling, and reversible image decolorization.
- [**Code**](https://github.com/YuanfeiHuang/WIN)

</div>  
</div>  

<div class='paper-box' style="display: flex; width: 100%;"><div class='paper-box-image' style="flex: 0 0 30%;"><div>
<div class="badge" style="background-color: #3498db; color: white">TCSVT 2024</div>  
<img src='images/2024TCSVT_CoMoNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' style="flex: 0 0 70%; padding-left: 20px;" markdown="1"> 

[Deep Convolution Modulation for Image Super-resolution](https://ieeexplore.ieee.org/document/10256095)
- **Yuanfei Huang**; Jie Li; Yanting Hu; Hua Huang; Xinbo Gao
- *IEEE Transactions on Circuits and Systems for Video Technology*, 2024, 34(5): 3647-3662.
- Building image-specific deep networks, thereby adaptively modulating the kernel weights without additional parameters.
- [**Code**](https://github.com/YuanfeiHuang/CoMoNet)

</div>  
</div>  

<div class='paper-box' style="display: flex; width: 100%;"><div class='paper-box-image' style="flex: 0 0 30%;"><div>
<div class="badge" style="background-color: #3498db; color: white">JEIT 2024</div>  
<img src='images/2024JEIT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' style="flex: 0 0 70%; padding-left: 20px;" markdown="1"> 

[Shutter-less Non-uniformity Correction Methods in Uncooled Infrared Imagery](https://jeit.ac.cn/article/doi/10.11999/JEIT231400)
- **Yuanfei Huang**; Hua Huang
- *Journal of Electronics & Information Technology (电子与信息学报)*, 2024, 46(5): 2198-2216.
- A survey on the physical formation and spatial characteristics of the non-uniformity in uncooled infrared imagery detectors.

</div>  
</div>  

<div class='paper-box' style="display: flex; width: 100%;"><div class='paper-box-image' style="flex: 0 0 30%;"><div>
<div class="badge" style="background-color: #3498db; color: white">TGRS 2024</div>  
<img src='images/2024TGRS_ACASP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' style="flex: 0 0 70%; padding-left: 20px;" markdown="1"> 

[Infrared Image Dynamic Range Compression Based on Adaptive Contrast Adjustment and Structure Preservation](https://ieeexplore.ieee.org/abstract/document/10689442)
- Jinyi Qiu; Zhan Wang; **Yuanfei Huang**; Hua Huang
- *IEEE Transactions on Geoscience and Remote Sensing*, 2024, 62: 1-12, Art no. 5006512.
- A gradient domain-based DRC method for IR images with adaptive contrast adjustment and structure preservation.

</div>  
</div>  

<div class='paper-box' style="display: flex; width: 100%;"><div class='paper-box-image' style="flex: 0 0 30%;"><div>
<div class="badge" style="background-color: #3498db; color: white">TPAMI 2023</div>  
<img src='images/2023TPAMI_TLSR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' style="flex: 0 0 70%; padding-left: 20px;" markdown="1"> 

[Transitional Learning: Exploring the Transition States of Degradation for Blind Super-resolution](https://ieeexplore.ieee.org/abstract/document/9893392)
- **Yuanfei Huang**; Jie Li; Yanting Hu; Xinbo Gao; Hua Huang
- *IEEE Transactions on Pattern Analysis and Machine Intelligence*, 2023, 45(5): 6495-6510.
- A transitional learning method for blind super-resolution and an effective representation for unknown degradation.
- [**Code**](https://github.com/YuanfeiHuang/TLSR)

</div>  
</div>  

<div class='paper-box' style="display: flex; width: 100%;"><div class='paper-box-image' style="flex: 0 0 30%;"><div>
<div class="badge" style="background-color: #3498db; color: white">KBS 2023</div>  
<img src='images/2023KBS_MSID.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' style="flex: 0 0 70%; padding-left: 20px;" markdown="1"> 

[Multi-scale information distillation network for efficient image super-resolution](https://www.sciencedirect.com/science/article/pii/S0950705123004689)
- Yanting Hu; **Yuanfei Huang#**; Kaibing Zhang
- *Knowledge-Based Systems*, 2023, 275：1-14, 2023, Art no. 110718.
- A lightweight super-resolution network with multi-scale receptive field.

</div>  
</div>  

<div class='paper-box' style="display: flex; width: 100%;"><div class='paper-box-image' style="flex: 0 0 30%;"><div>
<div class="badge" style="background-color: #3498db; color: white">TIP 2021</div>  
<img src='images/2021TIP_DeFiAN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' style="flex: 0 0 70%; padding-left: 20px;" markdown="1"> 

[Interpretable Detail-Fidelity Attention Network for Single Image Super-Resolution](https://ieeexplore.ieee.org/abstract/document/9334407)
- **Yuanfei Huang**; Jie Li; Xinbo Gao; Yanting Hu; Wen Lu
- *IEEE Transactions on Image Processing*, 2021, 30: 2325-2339.
- An interpretable detail-fidelity attention network for improving image super-resolution.
- [**Code**](https://github.com/YuanfeiHuang/DeFiAN)

</div>  
</div>  

<div class='paper-box' style="display: flex; width: 100%;"><div class='paper-box-image' style="flex: 0 0 30%;"><div>
<div class="badge" style="background-color: #2ecc71; color: white">ICCVW 2019</div>  
<img src='images/2019ICCVW.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' style="flex: 0 0 70%; padding-left: 20px;" markdown="1"> 

[Un-Paired Real World Super-Resolution with Degradation Consistency](https://ieeexplore.ieee.org/abstract/document/9022113)
- **Yuanfei Huang**; Xiaopeng Sun; Wen Lu; Jie Li; Xinbo Gao
- In *IEEE/CVF International Conference on Computer Vision Workshop*, 2019.
- 2nd place on "Target Domain RWSR" track of the AIM Real-World Super-Resolution Challenge.

</div>  
</div>  

<div class='paper-box' style="display: flex; width: 100%;"><div class='paper-box-image' style="flex: 0 0 30%;"><div>
<div class="badge" style="background-color: #2ecc71; color: white">ICME 2019</div>  
<img src='images/2019ICME.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' style="flex: 0 0 70%; padding-left: 20px;" markdown="1"> 

[Improving Image Super-Resolution via Feature Re-Balancing Fusion](https://ieeexplore.ieee.org/abstract/document/8784891)
- **Yuanfei Huang**; Jie Li; Xinbo Gao; Wen Lu; Yanting Hu
- In *IEEE International Conference on Multimedia and Expo*, 2019.

</div>  
</div>  

<div class='paper-box' style="display: flex; width: 100%;"><div class='paper-box-image' style="flex: 0 0 30%;"><div>
<div class="badge" style="background-color: #3498db; color: white">TIP 2018</div>  
<img src='images/2018TIP_MMPM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' style="flex: 0 0 70%; padding-left: 20px;" markdown="1"> 

[Single Image Super-Resolution via Multiple Mixture Prior Models](https://ieeexplore.ieee.org/abstract/document/8421656)
- **Yuanfei Huang**; Jie Li; Xinbo Gao; Lihuo He; Wen Lu
- *IEEE Transactions on Image Processing*, 2018, 27(12): 5904-5917.
- An effective way with mixture prior models for image super-resolution.
- [**Code**](https://github.com/YuanfeiHuang/MMPM)

</div>  
</div>  

# 💼 Projects and Fundings
- *2024* the Fundamental Research Funds for the Central Universities (中央高校基本科研业务费)
- *2022* the National Natural Science Foundation of China (国家自然科学基金青年项目)

# 🎖 Honors and Awards
- *2024* Beijing Association for Science and Technology Youth Talent Support Program (北京科协青年人才托举工程)
- *2024* 2nd Prize in the 19th Young Teachers' Teaching Skills Competition of Beijing Normal University (北京师范大学第十九届青年教师教学基本功比赛二等奖)
- *2024* 1st Prize in the 10th Beijing College Students' Biology Competition (Advisor) (第十届北京市大学生生物学竞赛一等奖（指导教师）)

# 💬 Invited Talks
- *2024.11*, "Intelligent Perception Empowering Autonomous Driving"(智能感知助力自动驾驶), a Cross-disciplinary Exchange Salon for Young Scientific Talents in the Field of Image and Graphics (图象图形领域青年科技人才跨界交流沙龙). Location: Beijing Conference Center, Organizer: Beijing Society of Image and Graphics.
