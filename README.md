# Augmented Infrared Solar Modules Set

A quality‐metric–driven, augmented thermal‐infrared PV module dataset for robust fault classification.

---

## Overview

This repository contains an expanded thermal‐infrared dataset of photovoltaic (PV) modules designed to accelerate research on automated fault detection in solar installations. By combining contrast‐aware augmentations with geometric transforms and balanced sampling, this dataset helps training deep‐learning models that generalize well to low‐contrast, noisy infrared imagery.

---

## Repository Structure

- ```images/```  
  Contains the original dataset of infrared images of PV modules.

- ```augmented_images/```  
  Contains the resulting augmented images, organized into the following subfolders:
  
  - ```geometric/```  
    Images augmented with geometric transformations (e.g., horizontal/vertical flips).
  
  - ```enhanced/```  
    Optimally enhanced images based on image quality metrics.
  
  - ```colored_images/```  
    Heatmap-colored versions of the thermal images.
  
  - ```decolorized/```  
    Optimally decolorized grayscale images derived from the colored versions.


## Citations
If you find the dataset useful, please consider citing:

```
@Article{ayunts2025slantnet,
  AUTHOR = {Ayunts, Hrach and Agaian, Sos and Grigoryan, Artyom},
  TITLE = {SlantNet: A Lightweight Neural Network for Thermal Fault Classification in Solar PV Systems},
  JOURNAL = {Electronics},
  VOLUME = {14},
  YEAR = {2025},
  NUMBER = {7},
  ARTICLE-NUMBER = {1388},
  URL = {https://www.mdpi.com/2079-9292/14/7/1388},
  ISSN = {2079-9292},
  DOI = {10.3390/electronics14071388}
}
@article{ayunts2024enhancing,
  title={Enhancing Thermal Image Classification with Novel Quality Metric-Based Augmentation Techniques},
  author={Ayunts, Hrach Y},
  journal={Mathematical Problems of Computer Science},
  volume={62},
  pages={112--125},
  year={2024}
}
```
The original dataset:
```
@inproceedings{millendorf2020infrared,
  title={Infrared solar module dataset for anomaly detection},
  author={Millendorf, Matthew and Obropta, Edward and Vadhavkar, Nikhil},
  booktitle={Proc. Int. Conf. Learn. Represent},
  year={2020}
}
```
