---
layout: page
title: Utility Structures Identification with SDGE
description: a collaboration with SDGE
img: assets/img/proj1.jpg
importance: 2
category: work
---

This project was a collaboration with San Diego Gas & Electric. The project uses Google Street View and computer vision to identify utility structures in San Diego. A python script is created to collect images of powerline poles and overhead structures in different angles and field of view using the Google Street View API, which then serve to train a computer vision model (DETR) and is then fine-tuned. The analysis of DETR models trained on minimal and extensive image sets reveals that while both show effective learning, the extensively trained model is more prone to overfitting, as seen in higher class error and misclassifications in certain cases.

[View the project on GitHub](https://github.com/Derek-Wen/StreetViewRiskDetector-DSC180A)

<div style="display:flex; justify-content:space-between;">
  <img src="../../assets/img/proj1_1.png" alt="Image 1" style="width:50%; margin-right:10px;">
  <img src="../../assets/img/proj1_2.jpg" alt="Image 2" style="width:50%; margin-left:10px;">
</div>

<embed src="../../assets/pdf/DSC_Capstone_Quarter1_Project.pdf" type="application/pdf" width="100%" height="600px" />