---
title: "Human Action Quality Assesment from Videos"
collection: publications
permalink: /research/AQAWD/x
excerpt: 'Action quality assessment (AQA) aims at automatically judging human action based on a
video of the said action and assigning a performance score to it. The aim of this project in to build a system that is capable of judging and assigning a score to human actions by inspecting a video of the said action being performed. Such a system would have potential use in
applications such as health care, sports video analysis, skill discrimination for a specific task etc. In this porject, we experiment with ResNets and a novel aggregation scheme titled Weight-Decider to achieve better performacne in benchmark dataset(MTL-AQA).'
date: '21 Feb 2021'
venue: 'reject'
github: 'https://github.com/Farabi-shafkat/Improving-Action-Quality-Assessment-using-ResNets-and-Weighted-Aggregation'
paperurl: 'https://arxiv.org/pdf/2102.10555.pdf'
arxiv: https://arxiv.org/abs/2102.10555
citation: ''
underReview: 'yes'
---

Action quality assessment (AQA) aims at automatically judging human action based on a
video of the said action and assigning a performance score to it. The majority of works in the
existing literature on AQA divide RGB videos in short clips, transform these clips to higher-level representations using Convolutional 3D (C3D) networks, and aggregate them through averaging. These higher-level representations are used to perform AQA. We find that
the current clip level feature aggregation technique of averaging is insufficient to capture
the relative importance of clip level features. In this work, we propose a learning-based
weighted-averaging technique. Using this technique, better performance can be obtained
without sacrificing too much computational resources. We call this technique WeightDecider(WD). We also experiment with ResNets for learning better representations for
action quality assessment. We assess the effects of the depth and input clip size of the
convolutional neural network on the quality of action score predictions. We achieve a new
state-of-the-art Spearman’s rank correlation of 0.9315 (an increase of 0.45%) on the MTL-AQA dataset using a 34 layer (2+1)D ResNet with the capability of processing 32 frame
clips, with WD aggregation.

<img src='/images/paper-image.png' style="width:100%">

[PDF](https://arxiv.org/pdf/2102.10555.pdf){:.btn--research}
[ArXiv](https://arxiv.org/abs/2102.10555){:.btn--research}
[Github](https://github.com/Farabi-shafkat/Improving-Action-Quality-Assessment-using-ResNets-and-Weighted-Aggregation){:.btn--research}
