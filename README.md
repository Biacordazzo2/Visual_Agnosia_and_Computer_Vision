# Understanding Visual Agnosia with Computer Vision
Final Project for Harvard College's Neuro140 - Biological and Artificial Intelligence. Learn more here: https://drive.google.com/file/d/1lUOtXDkiPSxIHDBkDmFP2s3exjtg8OVE/view?usp=sharing

# Introduction
Visual agnosia is a rare condition characterized by the inability to recognize objects, faces, colors, or places. There are several types of visual agnosia, but here I focus on object agnosia; the inability to recognize or characterize visually presented objects. This condition is caused when certain brain pathways are damaged, sometimes as a result of stroke, head trauma, or inflammation of brain tissue. In order to study the virtual version of this human condition, a pre-trained CNN was used to perform image classification under normal and artificially induced conditions, simulating a healthy person and a patient with object agnosia, respectively. The results were analyzed to shed light into potential mechanisms or to identify interesting patterns behind this condition. 

# Objectives
1.	Learn about convolutional neural networks (CNNs), their architectures, and how they work.
2.	Use a pre-trained CNN for image classification.
3.	Artificially induce visual agnosia and determine its effects on the CNN’s performance. 

# Materials needed:
1. Jupyter Notebook.
2. Python3.

# How to run this project
Two notebooks are provided above:
1. Neuro140_FinalProject
2. Initial Tests
The first one contains the main implementation of the final project while the second one contains initial tests performed to optimize the model's image classification performance. The second notebook is provided only for reference.

All steps necessary to run the Neuro140_FinalProject notebook have been provided inside in chronological order. These steps include:
- Downloading the CIFAR-10 dataset. 
- Optimizing the specified CNN - in this case ResNet18.
- Inducing object agnosia by:
    - Weight Ablation
    - Weight Augmentation
- Plotting and analysis of results.

The only requirement to guarantee successful performance is to run every cell in order. No additional steps are required.
