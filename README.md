# <img src="Resources\logo_blue.png"  height="100px" width="200px"> Sea-Land_Segmentation-Tracking Using AI 🌍

![](https://img.shields.io/badge/License-MIT-blue)![](https://img.shields.io/badge/Version-v1-blue)

![HOME PAGE](Resources\home_page.png)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

***Project Aims:*** This project aims to solve the issue of sea level rise affecting the land in Egypt. Its objective is to analyze and 
quantify the erosion and differences occurring over time in a specific region between the sea and the land. 
Additionally, it can predict potential events such as Reducing the expected problems on military ports, floods, 
droughts, and other related problems. This will be achieved through the use of AI for Satellite Image Segmentation 
and Tracking, employing the U-Net algorithm.

 ## System Architecture 
- ***Data Collection and Preparation:***
  ##### 1. Google Earth Dataset: 210 images and masks.
  ##### 2. Images: 3-band, 1000×1000, 3~5m resolution.
  ##### 3. Random sampling: 256×256 patches, 13,563 perdatase.
  <p align="center">
   <img src="Resources\Picture1.jpg"  height="210px" width="385px">
  </p>
  
 - ***Model Selection and Evaluation:***
   ##### 1. U-Net: Robust, boundary-focused sea-land segmentation.
   ##### 2. Versatile: Handles variations, limiteddata requirements.
   ##### 3. Evaluate Model for deploymentand improvement.
   <p align="center">
    <img src="Resources\u-net-architecture.png"  height="550px" width="600px">
   </p>
## System Methodology
   <p align="center">
    <img src="Resources\Picture3.jpg"  height="550px" width="660px">
   </p>
