 <p align="center"><img src="Resources\logo_blue.png"  height="100px" width="200px"></p> 
# Sea-Land_Segmentation-Tracking Using AI 🌍

![](https://img.shields.io/badge/License-MIT-blue)![](https://img.shields.io/badge/Version-v1-blue)

![HOME PAGE](Resources\home_page.jpg)

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
   <p align="center">
     <b>U-NET ARCHITECTURE</b>
   </p>
   
## System Methodology
   <p align="center">
    <img src="Resources\Picture3.png"  height="550px" width="660px">
   </p>
   

## Implementation and Design
- A project consisting of three pages on the main where the map and image capture are located, the analysis page through which the mask for the image and the proportion of sea and land can be obtained, and the tracking page through which the difference between places can be tracked at certain time periods.
<br>
 <p align="center">
     <p>
       <b>ANALSIS RESULT</b>
     </p>
     <img src="Resources\Analysis_result.png"  height="500px" width="890px">
 </p>
 <p align="center">    
     <p>
       <b>TRACKING RESULT</b>
     </p>
     <img src="Resources\Trace_result.png"  height="500px" width="890px">
 </p>
