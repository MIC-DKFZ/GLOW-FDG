# GLOW-FDG

![GLOW-FDG logo](GLOW-FDG/logo.jpg)

**GLOW-FDG** is an open-source AI model for whole-body cancer lesion segmentation in  
**<sup>18</sup>F-FDG PET/CT**.

GLOW-FDG stands for:

**G**eneralized cancer **L**esi**O**n **W**hole-body segmentation model for FDG-PET/CT.

## Overview

Whole-body FDG-PET/CT is widely used in oncology, but manual lesion delineation is time-consuming, subjective, and difficult to scale. GLOW-FDG provides automated segmentation of FDG-avid cancer lesions across whole-body PET/CT scans.

The model was trained on **1,563 FDG-PET/CT scans** spanning multiple cancer types and evaluated on **185 external validation scans** from independent cohorts.

## Key Features

- Whole-body FDG-PET/CT cancer lesion segmentation
- Trained on diverse multi-cancer data
- Validated on independent external cohorts
- Built on the nnU-Net framework with a ResEncL U-Net architecture
- Uses multitask organ supervision to reduce physiologic uptake false positives

## Model Weights

Model weights are available on Hugging Face: [mrokuss/GLOW-FDG](https://huggingface.co/mrokuss/GLOW-FDG)

## Intended Use

GLOW-FDG is intended for research use in automated FDG-PET/CT lesion segmentation.

## Citation

If you use GLOW-FDG, please cite: TODO
