---
title: "RDR-KD: A Knowledge Distillation Detection Framework for Drone Scenes"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
date: 2024-05-08
venue: 'IEEE Geoscience and Remote Sensing Letters'
paperurl: 'https://Golden-Ele.github.io/files/RDR-KD_A_Knowledge_Distillation_Detection_Framework_for_Drone_Scenes.pdf'
citation: 'J. Huang, H. Chang, X. Yang, Y. Liu, S. Liu and Y. Song, "RDR-KD: A Knowledge Distillation Detection Framework for Drone Scenes," in IEEE Geoscience and Remote Sensing Letters, vol. 21, pp. 1-5, 2024'
---

Drone object detection (DOD) with real-time deployment is a research hotspot. On the one hand, the performance of tiny object detection is closely related to the ground detection capability of the drone platform. Existing methods are keen on designing complex networks to enhance the accuracy of tiny objects, which significantly increases computational costs. On the other hand, the limited drone hardware resources urgently require lightweight models for deployment. To address the dilemma of balancing detection accuracy and computational efficiency, we propose a regenerated-decoupled-responsive knowledge distillation (RDR-KD) framework specifically for drone scenes. First, we design the Regenerated Distillation and the Decoupled Distillation to fully transfer the tiny object feature information from the teacher model to the student model. Meanwhile, we devise the logit-based Responsive Distillation based on focal loss and efficient intersection over union (EIoU) to alleviate class imbalance. Finally, we conduct extensive experiments on the VisDrone2019 dataset. The experimental results demonstrate that the proposed RDR-KD framework improves AP and AP_S of the student model by 3.3% and 2.9% respectively, which outperforms other state-of-the-art distillation frameworks.
