# ASCPA-Attention


## Introduction

This repository contains the official implementation of **Adaptive Spatial Correlation Pyramid Attention Network for Detecting Outfalls into Rivers and Oceans in Aerial Images**. The purpose of our work is to propose an intelligent system, which assists inspectors in completing the task of detecting and locating regions of outfalls in aerial images well. To be specfic, the proposed ASCPA as a novel attention module is embedded into the YOLOv5s architecture. Its purpose is to construct multi-scale spatial correlations and explore intra-regional associations of feature maps. Therefore, it is able to better capture contextual information and long-range dependencies in aerial images, so as to improve the performance of the YOLOv5s architecture in completing the outfall detection task. This work was completed by Intelligent Sensing and Computing Laboratory affiliated to Beijing Information Science and Technology University. It has been submitted to the Journal of Engineering Applications of Artificial Intelligence published by Elsevier.

<p align="center">
  <img src="https://github.com/ISCLab-Bistu/ASCPA-Attention/blob/main/Image/ASCPA.jpg" />
</p>

<p align = "center">
Adaptive Spatial Correlation Pyramid Attention (ASCPA). 
</p>

The structure of the ASCPA network is shown in above picture. This network is mainly composed of SPE (Spatial Pyramid Extractor) and SCFM (Spatial Correlation Fusion Module). The purpose of the SPE is to extract multi-scale spatial information on the feature map. The SCFM is used to perform spatial correlation feature recalibration to selectively emphasized informative features. 


## Result

<p align="center">
    <img src="https://github.com/ISCLab-Bistu/ASCPA-Attention/blob/main/Image/vis.jpg" />
</p>

<p align = "center">
Visualization results are shown in above picture using Gradcam tool. Obviously, the heat map of YOLOv5-ASCPA is completely able to cover the core area of the outfall which reflects higher response intensity with dark red. The error-prone region has a very weak response intensity for the YOLOv5-ASCPA model compared with the other three models.
</p>

## Usage

ASCPA can be inserted into [YOLOv3](https://github.com/ultralytics/yolov3), [YOLOv4](https://github.com/Tianxiaomo/pytorch-YOLOv4) and [YOLOv5](https://github.com/ultralytics/yolov5/) as a standalone module.

The [configuration file](config/yolov5s.yaml) for YOLOv5 is provided here as an example.

## Summary & Prospect

Our team proposed ASCPA in order to promote the capability of YOLO series network for small object detection. ASCPA was tested on our outfall dataset and proved its excellent capability. Despite that ASCPA has not been tested in other datasets, we still hope that it will demonstrate his power in more datasets.




