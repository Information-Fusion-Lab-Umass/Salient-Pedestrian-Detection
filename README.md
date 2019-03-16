
# Pedestrian Detection fom Thermal Images using Saliency Maps

<center>Debasmita Ghose*, Shasvat Desai*, Sneha Bhattacharya*, Deep Chakraborty, Tauhidur Rahman, Madalina Fiterau</center>

## Abstract

Thermal images are mainly used to detect the presence of people at night or in bad lighting conditions, but perform
poorly at daytime. To solve this problem, most state-of-the-art techniques use a fusion network that uses features from
paired thermal and color images. We propose to augment thermal images with their saliency maps as an attention
mechanism to provide better cues to the pedestrian detector, especially during daytime. We investigate how such an
approach results in improved performance for pedestrian detection using only thermal images, eliminating the need
for color image pairs. We train a state-of-the art Faster R-CNN for pedestrian detection and explore the added
effect of PiCA-Net and R3-Net as saliency detectors. Our proposed approach results in an absolute improvement
of 13.4% and 19.4% in log average miss rate over the baseline in day and night images respectively. We also annotate
and release pixel level masks of pedestrians on a subset of the KAIST Multispectral Pedestrian Detection dataset,
which is a first publicly available dataset for salient pedestrian detection.

<center>
<img src="Block_Diagram_Final_compact.png" width="400" height="400" align="center"/>
</center>


## KAIST Salient Pedestrian Dataset

### Description

### Sample Images

### Downloads
- [Training Set]()
- [Test Set]()
- [Imagesetfiles]()
- [Code]()

### Pre-trained Weights for State-of-the-Art Deep Saliency Detection Networks for this Dataset
- [PICA-Net]()
- [R3-Net]()

## Pedestrian Detection Using Faster R-CNN

### Code

- [Faster R-CNN]() 
- [PICA-Net]()
- [R3-Net]()

### Results

### Sample Images


### Pretrained Weights for Faster R-CNN trained on the KAIST Pedestrian Dataset

- [Thermal Images]()
- [Static Saliency Maps generated from Thermal Images]()
- [Thermal Images Fused with Static Saliency Maps]()
- [Thermal Images Fused with Saliency Maps generated using PICA-Net]()
- [Thermal Images Fused with Saliency Maps generated using R3-Net]()

