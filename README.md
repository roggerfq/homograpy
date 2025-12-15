# Homography with LoFTR

This repository demonstrates the computation of **homography** between image pairs using **LoFTR (Detector-Free Local Feature Matching with Transformers)**.

## Results

Please visit the following link to see the results of the homography estimation and the visualization of the **mapping of the red point**:

👉 https://roggerfq.github.io/homograpy/

## Homography Computation

The **homography matrices** used in the website are computed in the following **Google Colab notebook**:

👉 https://colab.research.google.com/drive/1rlNnYn-ySr884uogk5cUjXIeLDwKroQ_?usp=sharing

This notebook computes the homography using feature correspondences obtained with **LoFTR**, and the resulting matrices are then used to visualize the point mapping on the website.

## Method

The homography is computed using **LoFTR**, a detector-free local feature matching approach based on Transformers.

## Reference

Sun, J., Shen, Z., Wang, Y., Bao, H., & Zhou, X. (2021).  
*LoFTR: Detector-Free Local Feature Matching with Transformers.*  
Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR).  
https://openaccess.thecvf.com/content/CVPR2021/papers/Sun_LoFTR_Detector-Free_Local_Feature_Matching_With_Transformers_CVPR_2021_paper.pdf
