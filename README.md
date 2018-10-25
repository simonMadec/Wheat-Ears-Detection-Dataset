# Wheat-Ears-Detection-Dataset
Dataset from the Ear density estimation from high resolution RGB imagery using deep learning technique paper

[Simon Madec], [Frederic Baret], [Benoit de Solan], [Shouyang Liu]
The Wheat-Ears-Dection-Dataset (WEDD) is a dataset is a image dataset designed fo wheat ears detection in field condition.  
![Ex](https://github.com/simonMadec/Wheat-Ears-Dection-Dataset/blob/master/Sans%20titre.png?raw=true)
## Overview
- [Highlights](#highlights)
- [Research Paper](#research-paper)
- [Downloads](#downloads)
- [Labels](#labels)
- [Results](#results)
- [Annotation Tool](#annotation-tool)

## Highlights
- 236 high resolution images images (6000*4000)
- Wheat ears annotated with a bounding box
- 30729 ears identified
- Spatial resolution (GSD) of 0.13mm/pixel
- Two images for each microplots 
- 20 contrasted genotype with 6 replicated growth in two environment 

## Research Paper

## Downloads

## Labels
Please download replicate information along with images used for training and testing [here]
## Results
Below we present results.

Method               | Date | Source| AP | rRMSE | R² 
---                  | ---  | ---   | ---                     | ---             | ---     
Faster-RCNN [1]       |   21/10/2018  |[2]| 0.85              | 5.3%|0.91     

### Annotation Tool
The LabelIMG tool were used, please refer to [this repository](https://github.com/tzutalin/labelImg).

