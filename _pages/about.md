---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a second year undergraduate student from [Yuanpei College](https://yuanpei.pku.edu.cn/), [Peking University](https://www.pku.edu.cn/). My research interest includes robotic manipulation, multimodal large models, computer vision, and machine learning.

[Email](zhuoyang_liu@stu.pku.edu.cn) / [Github](https://github.com/miniFranka) / [Wechat](../images/wechat.jpg) 


# Publications

## [In Submission] Fast-in-Slow: A Dual-System Foundation Model Unifying Fast Manipulation within Slow Reasoning 
Hao Chen*, Jiaming Liu*, Chenyang Gu*, **Zhuoyang Liu***(equal contribution), Renrui Zhang, Xiaoqi Li, Xiao He, Yandong Guo, Chi-Wing Fu, Shanghang Zhang, Pheng-Ann Heng
![fis_teaser](/images/fis_teaser_0604.png)
We propose Fast-in-Slow (FiS), a unified dual-system vision-language-action (VLA) model that embeds the System 1 execution module within the VLM-based System 2 by partially sharing parameters. Unlike previous dual-system VLA methods that attach a separate policy head as System 1, FiS-VLA repurposes the final transformer blocks of an intact VLM as System 1, while retaining the full model for System 2 reasoning.
[[Project Page](https://fast-in-slow.github.io/)]/[[Paper on Arxiv](https://arxiv.org/abs/2506.01953)]/[[Github Repo](https://github.com/CHEN-H01/Fast-in-Slow)]

## [In Submission] HybridVLA: Collaborative Autoregression and Diffusion in a Unified Vision-Language-Action Model 
Jiaming Liu*, Hao Chen*, Pengju An*, **Zhuoyang Liu***(equal technical contribution), Renrui Zhang, Chenyang Gu, Xiaoqi Li, Ziyu Guo, Sixiang Chen, Mengzhen Liu, Chengkai Hou, Mengdi Zhao, KC alex Zhou, Pheng-Ann Heng, Shanghang Zhang
![hybridvla_teaser](/images/hybridvla_teaser_0520.png)
We introduce HybridVLA, a unified framework that absorbs the continuous nature of diffusion-based actions and the contextual reasoning of autoregression within a single large language model. HybridVLA outperforms previous state-of-the-art VLA methods by 14% and 19% in mean success rate on simulation and real-world tasks, respectively, while demonstrating stable manipulation in unseen configurations.
[[Project Page](https://hybrid-vla.github.io/)]/[[Paper on Arxiv](https://arxiv.org/abs/2503.10631)]/[[Github Repo](https://github.com/PKU-HMI-Lab/Hybrid-VLA)]

## [CVPR 2025 Synthetic Data for Computer Vision Workshop][In Submission] H2R: A Human-to-Robot Data Augmentation for Robot Pre-training from Videos 
Guangrun Li*, Yaoxu Lyu*, **Zhuoyang Liu***(equal contribution), Chengkai Hou, Jieyu Zhang, Shanghang Zhang
![h2r_teaser](/images/h2r_teaser_0522.png)
We propose H2R, a simple data augmentation technique that detects human hand keypoints, synthesizes robot motions in simulation, and composites rendered robots into egocentric videos. This process explicitly bridges the visual gap between human and robot embodiments during pre-training. We apply H2R to augment large-scale egocentric human video datasets such as Ego4D and SSv2, replacing human hands with simulated robotic arms to generate robot-centric training data.
[[Project Page](https://sites.google.com/view/h2r-robotics/)]/[[Paper on Arxiv](https://arxiv.org/abs/2505.11920)]/[[Dataset](https://huggingface.co/datasets/yaoxu789/H2R-1M/)]
