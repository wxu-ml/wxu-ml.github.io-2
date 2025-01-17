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

<p align="justify">
**Dr. Xu Wang (王旭)** is currently an associate researcher at the College of Computer Science, Sichuan University. He received the B.E. degree and Ph.D. degree from Sichuan University in 2015 and 2021, respectively. He was a Joint Ph.D at the Australian Institute for Machine Learning (AIML), University of Adelaide, funded by the China Scholarship Council from 2019 to 2021. His research interests include Machine Learning, Deep Learning, Multi-view Analysis, and Multi-modal Learning. 
</p>

[//]: (<a href='https://scholar.google.com/citations?user=XTOXhy4AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).)


# 📖 Educations
- *2015.07 - 2021.06*, <a href="https://en.scu.edu.cn/"><img class="png" src="/images/SCU_logo.png" width="20pt"></a> Ph.D., Sichuan University, Chengdu, China.
- *2019.09 - 2021.03*, <a href="https://www.adelaide.edu.au/aiml/"><img class="png" src="/images/UOA_logo.png" width="20pt"></a> Joint Ph.D., Australian Institute for Machine Learning (AIML), University of Adelaide, Adelaide, Australia.
- *2011.09 - 2015.06*, <a href="https://en.scu.edu.cn/"><img class="png" src="/images/SCU_logo.png" width="20pt"></a> B.E., Sichuan University, Chengdu, China.

# 🔥 News
- *2024.12*: &nbsp; Two papers were accepted by The AAAI Conference on Artificial Intelligence (AAAI 2025, <font color="red">CCF-A</font>). Congratulations to Chao and Zi-niu!
- *2024.09*: &nbsp; I will serve as the Workflow Chair for the 34th International Joint Conference on Artificial Intelligence (IJCAI 2025, <font color="red">CCF-A</font>), which will be held in Montreal, Canada from 16th Aug 2025 – 22th Aug 2025.
- *2024.06*: &nbsp; One paper was accepted by IEEE Transactions on Information Forensics & Security (IEEE TIFS, <font color="red">CCF-A</font>). Congratulations to Yong!
- *2024.05*: &nbsp; One paper was recognized by ESI as a <font color="red">Highly Cited Paper</font>!
- *2023.12*: &nbsp; One paper was accepted by The AAAI Conference on Artificial Intelligence (AAAI 2024, <font color="red">CCF-A</font>). Congratulations to Hao-ran!
- *2023.11*: &nbsp; One paper was accepted by IEEE Transactions on Image Processing (IEEE TIP, <font color="red">CCF-A</font>). Congratulations to Peng!
- *2023.04*: &nbsp; One paper was accepted by IEEE Transactions on Circuits and Systems for Video Technology (IEEE TCSVT, <font color="red">JCR-Q1</font>). Thanks to all coauthors!
- *2022.12*: &nbsp; One paper was accepted by The AAAI Conference on Artificial Intelligence (AAAI 2023, <font color="red">CCF-A</font>). Thanks to all coauthors!

# ✏️ Call for Paper
- Electronics (Q2, IF: 2.9) special issue on 'Data-Driven Intelligence in Autonomous Systems', Deadline: 15 May 2025. [Call for paper](https://www.mdpi.com/journal/electronics/special_issues/data_auto_sys)


# 📝 Publications 
### (# denotes corresponding author, ^ denotes equal contribution)


## 2024
[//]: - Yong Chen, Peng Hu, Zhong Yuan, Dezhong Peng, **Xu Wang#**. [Integrating Confidence Calibration and Adversarial Robustness via Adversarial Calibration Entropy](https://www.sciencedirect.com/science/article/pii/S0020025524004456). **Information Sciences**. 2024.
- Yong Chen, Xuedong Li, Peng Hu, Dezhong Peng, **Xu Wang#**. [DifFilter: Defending Against Adversarial Perturbations with
Diffusion Filter](https://ieeexplore.ieee.org/document/10584510). **IEEE Transactions on Information Forensics & Security (IEEE TIFS)**. 2024. (<font color="red">CCF-A</font>)
- Haoran Liu, Ying Ma, Ming Yan, Yingke Chen, Dezhong Peng, **Xu Wang#**. [DiDA: Disambiguated Domain Alignment for Cross-Domain Retrieval with Partial Labels](https://ojs.aaai.org/index.php/AAAI/article/view/28150). **AAAI Conference on Artificial Intelligence (AAAI)**. 2024, 38(4), 3612-3620. (<font color="red">CCF-A Oral</font>) [**[Code]**](https://github.com/wangxu-scu/DiDA) 
- Chao Su, Zhi Li, Tianyi Lei, Dezhong Peng, **Xu Wang#**. [MetaVG: A Meta-Learning Framework for Visual Grounding](https://ieeexplore.ieee.org/abstract/document/10365212). **IEEE Signal Processing Letters**. 2024, 31: 236-240. [**[Code]**](https://github.com/Rose-bud/MetaVG) 
- Yuan Sun, Zhenwen Ren, Peng Hu, Dezhong Peng, **Xu Wang#**. [Hierarchical Consensus Hashing for Cross-Modal Retrieval](https://ieeexplore.ieee.org/abstract/document/10119165). **IEEE Transactions on Multimedia**. 2024, 26: 824-836. (<font color="red">ESI Highly Cited</font>) [**[Code]**](https://github.com/sunyuan-cs/HCCH) 


## 2023
- <p align="justify"> 
Peng Hu, Liangli Zhen, Xi Peng, Hongyuan Zhu, Jie Lin, **Xu Wang**, Dezhong Peng. <a href="https://ieeexplore.ieee.org/abstract/document/10341289/">Deep Supervised Multi-View Learning with Graph Priors</a>. <b>IEEE Transactions on Image Processing (IEEE TIP)</b>. 2023, doi: 10.1109/TIP.2023.3335825. (<font color="red">CCF-A</font>) <a href="https://github.com/penghu-cs/DMLPA">[Code]</a 
</p>
- **Xu Wang**, Dezhong Peng, Peng Hu, Yunhong Gong, Yong Chen. [Cross-Domain Alignment for Zero-Shot Sketch-Based Image Retrieval](https://ieeexplore.ieee.org/abstract/document/10098211). **IEEE Transactions on Circuits and Systems for Video Technology (IEEE TCSVT)**. 2023, 33(11): 7024-7035. [**[Code]**](https://github.com/wangxu-scu/CA)
- **Xu Wang**, Dezhong Peng, Ming Yan, Peng Hu. [Correspondence-Free Domain Alignment for Unsupervised Cross-Domain Image Retrieval](https://arxiv.org/pdf/2302.06081.pdf). **AAAI Conference on Artificial Intelligence (AAAI)**. 2023, 10200–10208. (<font color="red">CCF-A Oral</font>) [**[Code]**](https://github.com/wangxu-scu/CoDA)
- Peng Hu, Zhenyu Huang, Dezhong Peng, **Xu Wang**, Xi Peng. [Cross-Modal Retrieval with Partially Mismatched Pairs](https://ieeexplore.ieee.org/abstract/document/10050111). **IEEE Transactions on Pattern Analysis and Machine Intelligence (IEEE TPAMI)**. 2023, doi: 10.1109/TPAMI.2023.3247939. (<font color="red">CCF-A</font>) [**[Code]**](https://github.com/penghu-cs/RCL)
- Yuan Sun, **Xu Wang**, Dezhong Peng, Zhenwen Ren, Xiaobo Shen. [Hierarchical Hashing Learning for Image Set Classification](https://ieeexplore.ieee.org/abstract/document/10061433/). **IEEE Transactions on Image Processing (IEEE TIP)**. 2023, 32: 1732-44. (<font color="red">CCF-A</font>)
- Qian Wang, Weiqi Zhang, Tianyi Lei, Yu Cao, Dezhong Peng, **Xu Wang#**. [CLSEP: Contrastive Learning of Sentence Embedding with Prompt](https://www.sciencedirect.com/science/article/pii/S0950705123001314). **Knowledge-Based Systems**. 2023, 266: 110381. [**[Code]**](https://github.com/qianandfei/CLSEP-Contrastive-Learning-of-Sentence-Embedding-with-Prompt)
- Yong Chen, **Xu Wang**, Peng Hu, Zhong Yuan, Dezhong Peng, Qilin Li. [Learning Relationship-Preserving Representation for Multi-Task Adversarial Attacks](https://www.sciencedirect.com/science/article/pii/S0925231223007038). **Neurocomputing**. 2023, 554: 126580.

## 2022
- Tianyi Lei, Honghui Hu, Qiaoyang Luo, Dezhong Peng, **Xu Wang#**. [Adaptive Meta-learner via Gradient Similarity for Few-shot Text Classification](https://arxiv.org/abs/2209.04702). **International Conference on Computational Linguistics (COLING)**. 2022, 4873–4882. [**[Code]**](https://github.com/Tianyi-Lei/Adaptive-Meta-learner-via-Gradient-Similarity-for-Few-shot-Text-Classification)
- Yang Qin, Dezhong Peng, Xi Peng, **Xu Wang**, Peng Hu. [Deep Evidential Learning with Noisy Correspondence for Cross-modal Retrieval](https://dl.acm.org/doi/abs/10.1145/3503161.3547922). **The ACM International Conference on Multimedia (ACM MM)**. 2022, 4948-4956. (<font color="red">CCF-A</font>) [**[Code]**](https://github.com/wangxu-scu/DECL)
- Yong Chen, **Xu Wang#**, Peng Hu, Dezhong Peng. [MagicGAN: Multiagent Attacks Generate Interferential Category via GAN](https://www.sciencedirect.com/science/article/pii/S0950705122011169). **Knowledge-Based Systems**. 2022, 258: 110023.
  
## 2021
- **Xu Wang^**, Peng Hu^, Liangli Zhen, Dezhong Peng. [DRSL: Deep Relational Similarity Learning for Cross-modal Retrieval](https://www.sciencedirect.com/science/article/pii/S0020025520307684). **Information Sciences**. 2021, 546: 298-311. [**[Code]**](https://github.com/wangxu-scu/DRSL)

## 2020
- **Xu Wang**, Peng Hu, Pei Liu, Dezhong Peng. [Deep Semisupervised Class- and Correlation-collapsed Cross-view Learning](https://ieeexplore.ieee.org/abstract/document/9086133/). **IEEE Transactions on Cybernetics (IEEE TCYB)**. 2020, 52(3): 1588-1601.


## 2019
- Liangli Zhen, Peng Hu, **Xu Wang**, Dezhong Peng. [Deep Supervised Cross-Modal Retrieval](http://openaccess.thecvf.com/content_CVPR_2019/html/Zhen_Deep_Supervised_Cross-Modal_Retrieval_CVPR_2019_paper.html). **IEEE Conference on Computer Vision and Pattern Recognition (CVPR)**. 2019, 10394-10403. (<font color="red">CCF-A</font>) [**[Code]**](https://github.com/penghu-cs/DSCMR)
- Peng Hu^, **Xu Wang^**, Liangli Zhen, Dezhong Peng. [Separated Variational Hashing Networks for Cross-Modal Retrieval](https://dl.acm.org/doi/abs/10.1145/3343031.3351078). **The ACM International Conference on Multimedia (ACM MM)**. 2019, 1721-1729. (<font color="red">CCF-A</font>)
- **Xu Wang**, Dezhong Peng, Peng Hu, Yongsheng Sang. [Adversarial Correlated Autoencoder for Unsupervised Multi-view Representation Learning](https://www.sciencedirect.com/science/article/pii/S0950705119300176). **Knowledge-Based Systems**. 2019, 168: 109-20.
- Peng Hu, Dezhong Peng, **Xu Wang**, Yong Xiang. [Multimodal Adversarial Network for Cross-modal Retrieval](https://www.sciencedirect.com/science/article/pii/S0950705119302230). **Knowledge-Based Systems**. 2019, 180: 38-50. [**[Code]**](https://github.com/penghu-cs/MAN)


# 🎖 Honors and Awards
- Special Support from China Postdoctoral Foundation.
- Excellent Doctoral Candidate of Sichuan Province.
- Support from the China Scholarship Council.
- China National Scholarship.
