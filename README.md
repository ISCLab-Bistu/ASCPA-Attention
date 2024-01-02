# ASCPA-Attention


## Introduction

This repository contains the official implementation of **ABSOD: Attention Based Small Object Detector for Outfalls Inspection in Aerial Images**. 

<p align="center">
  <img src="https://github.com/ISCLab-Bistu/ASCPA-Attention/blob/main/Image/ASCPA.jpg" />
</p>

<p align = "center">
Adaptive Spatial Correlation Pyramid Attention (ASCPA). 
</p>

The structure of the ASCPA network is shown in above picture. This network is mainly composed of SPE (Spatial Pyramid Extractor) and SCFM (Spatial Correlation Fusion Module). The purpose of the SPE is to extract multi-scale spatial information on the feature map. The SCFM is used to perform spatial correlation feature recalibration to selectively emphasized informative features. 


## Result

<p align="center">
    <img src="https://github.com/ISCLab-Bistu/ASCPA-Attention/blob/main/Image/Grad_CAM.jpg" />
</p>

<p align = "center">
Visualization results are shown in above picture using Gradcam tool.
</p>

## Summary & Prospect

Our research introduces the Attention Based Small Object Detector (ABSOD) for outfall detection in UAV imagery, addressing the need for improved monitoring of pollutant emissions into natural water bodies. The ABSOD model leverages an adaptive spatial correlation pyramid attention (ASCPA) network to effectively identify outfalls in high-resolution aerial images, outperforming existing detection models. We anticipate that ABSOD will offer a valuable tool for environmental experts, and we are optimistic about its potential to contribute to more efficient and accurate outfall surveys, ultimately aiding in environmental protection and management.