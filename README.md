# Augmented Infrared Solar Modules Set

A quality‐metric–driven, augmented thermal‐infrared PV module dataset for robust fault classification.

---

## Overview

This repository contains an expanded thermal‐infrared dataset of photovoltaic (PV) modules designed to accelerate research on automated fault detection in solar installations. By combining contrast‐aware augmentations with geometric transforms and balanced sampling, this dataset helps training deep‐learning models that generalize well to low‐contrast, noisy infrared imagery.

---

## Repository Structure

**raw_images/**  
  Contains the original infrared snapshots of PV modules, organized by fault category (e.g., `hot_spot/`, `cell_crack/`, `diode/`, `soiling/`, `healthy/`).

- **augmented_images/**  
  Contains the resulting augmented images, structured in the same category folders as `raw_images/`.

## Citation
If you find the dataset useful, please consider citing:

```
@Article{electronics14071388,
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
```
