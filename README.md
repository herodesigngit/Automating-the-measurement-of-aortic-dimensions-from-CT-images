## Project Overview

This repository provides a solution for **automatically segmenting the aorta** and measuring its dimensions in **CT images** using a pretrained model from the MONAI framework. The primary objective is to:

- **Segment** the aorta from CT scans.
- **Measure** aortic diameters at different points along its length.

The project utilizes **MONAI**, a robust framework for medical image analysis that leverages **PyTorch**. The pretrained model used here for segmentation was trained on a whole-body CT dataset and can be adapted to segment specific structures such as the aorta.

### Key Features:
- **Automatic segmentation of the aorta** in CT images.
- **Measurement of aortic diameters** at various points.
- **Pretrained MONAI model** for segmentation.
  
![download (2)](https://github.com/user-attachments/assets/9a396462-376c-418c-9b95-7e0adf7729a5)

1. Preprocessing the CT Images

2. Segmentation of the Aorta

3. Extract the Aortic Voxels

4. Calculate the Centroid at Each Z Coordinate

5. Identify the Plane of Minimal Cross-Sectional Area

6. Output the Measurements
