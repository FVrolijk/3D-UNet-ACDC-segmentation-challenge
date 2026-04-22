# 3D U-Net ACDC Segmentation challenge
This repository contains the source code for the 3D segmentation task of the ACDC challenge, developed for the Deep Learning for Medical Imaging course (Group 2, 2026).

## Overview
The project implements a **3D U-Net** architecture to segment the three cardiac structures from 3D MRI volumes: The Right Ventricle (RV), Left Ventricle (LV), and Myocardium (MYO).

## The final results
The model achieved the followinf performance on the test set:
* **Mean Dice Score**: 0.8636
* **HD95**: 4.7761 mm

## Installation
To ensure compatibility with MONAI, it is required to have **NumPy < 2.0**. Other mandatory packages are enlisted within the requirements text file.

## Dataset and challenge
Information about the ACDC challenge as well as the dataset can be found using the following link:
https://www.creatis.insa-lyon.fr/Challenge/acdc/databases.html
