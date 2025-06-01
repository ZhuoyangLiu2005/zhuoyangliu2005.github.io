---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a second year undergraduate student from [Yuanpei College](https://yuanpei.pku.edu.cn/), [Peking University](https://www.pku.edu.cn/). My research interest includes robotics, computer vision, and machine learning.

[Email](zhuoyang_liu@stu.pku.edu.cn) / [Github](https://github.com/miniFranka) / [Wechat](../images/wechat.jpg) 


# Projects and Works

## HybridVLA: Collaborative Autoregression and Diffusion in a Unified Vision-Language-Action Model
![hybridvla_teaser](/images/hybridvla_teaser_0520.png)
We introduce HybridVLA, a unified framework that absorbs the continuous nature of diffusion-based actions and the contextual reasoning of autoregression within a single large language model. To mitigate interference between the two generation paradigms, we propose a collaborative training recipe that seamlessly incorporates diffusion denoising into the next-token prediction process. With this recipe, we find these two action prediction methods not only reinforce each other but also exhibit varying strength across different tasks. Therefore, we design a collaborative action ensemble mechanism that adaptively fuses both predictions, leading to more robust control. HybridVLA outperforms previous state-of-the-art VLA methods by 14% and 19% in mean success rate on simulation and real-world tasks, respectively, while demonstrating stable manipulation in unseen configurations.
[project page](https://hybrid-vla.github.io/) / [paper on arxiv](https://arxiv.org/abs/2503.10631) / [github repo](https://github.com/PKU-HMI-Lab/Hybrid-VLA)

## H2R: A Human-to-Robot Data Augmentation for Robot Pre-training from Videos
![h2r_teaser](/images/h2r_teaser_0522.png)
We propose H2R, a simple data augmentation technique that detects human hand keypoints, synthesizes robot motions in simulation, and composites rendered robots into egocentric videos. This process explicitly bridges the visual gap between human and robot embodiments during pre-training. We apply H2R to augment large-scale egocentric human video datasets such as Ego4D and SSv2, replacing human hands with simulated robotic arms to generate robot-centric training data. Based on this, we construct and release a family of 1M-scale datasets covering multiple robot embodiments (UR5 with gripper/Leaphand, Franka) and data sources (SSv2, Ego4D). The H2R dataset can be accessed on [https://huggingface.co/datasets/yaoxu789/H2R-1M/](https://huggingface.co/datasets/yaoxu789/H2R-1M/)
[project page](https://sites.google.com/view/h2r-robotics/) / [paper on arxiv](https://arxiv.org/abs/2505.11920) 
