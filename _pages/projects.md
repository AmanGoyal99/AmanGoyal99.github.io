---
title: "Projects"
excerpt: "Projects"
author_profile: true
permalink: /projects/
redirect_from:
  - /tags/
---

{% include base_path %}

Intrusion Detection in Low-Light scenarios
------
- A video surveillance based solution for low light scenarios. 
- The motivation behind this solution was to enhance the security of the borders using AI given the rise in terrorism.

<p align="center">
<img src = "/images/final_output.gif" width="95%">
</p>

- Low-light images were processed using stacking and averaging techniques. 
- Detection of intruders and their firearms were done using *YOLOv4* based model.
- *HRNet* was utilized for intruder pose estimation
- *Viola-Jones* algorithm was used for intruder face recognition.

2.MindWare
------
[MindWare](https://github.com/PKU-DAIR/mindware) is an efficient open-source system to help users to automate the process of 1) data pre-processing, 2) feature engineering, 3) algorithm selection, 4) architecture design, 5) hyper-parameter tuning, and 6) model ensembling. It is capable of improving its AutoML power by decomposing the entire large AutoML search space into small ones, and solve each sub-problems jointly and efficiently.

<p align="center">
<img src="/images/mindware.png" width="30%">
</p>

MindWare is developed by <a href="http://net.pku.edu.cn/~cuibin/" target="_blank" rel="nofollow">DAIR Lab</a> at Peking University.
The goal of MindWare is to make machine learning easier to apply both in industry and academia.

3.OpenBox
------
[OpenBox](https://open-box.readthedocs.io/en/latest) is an efficient open-source system designed for solving generalized black-box optimization (BBO) problems.
<p align="center">
<img src="/images/Openbox.png" width="30%">
</p>
It owns the following characteristics:
1. BBO with multiple objectives and constraints.
2. BBO with transfer learning.
3. BBO with distributed parallelization.
4. BBO with multi-fidelity acceleration.
5. BBO with early stops.

