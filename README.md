# mmpose Excavator Keypoints Detection using HRNet with RTMDet

[![python](https://img.shields.io/badge/Python-3.11-3776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![pytorch](https://img.shields.io/badge/PyTorch-2.0.1+cu117-EE4C2C.svg?style=flat&logo=pytorch)](https://pytorch.org)
![Static Badge](https://img.shields.io/badge/Keypoints-Detection-cyan)
![Static Badge](https://img.shields.io/badge/mmpose-blue)

This repository contains keypoints detection project focused on **Robotic like Machine, Excavator** with **6 keypoints** using **HRNet**.

<img src="https://github.com/user-attachments/assets/e45924c3-0412-4d49-aa03-96dbd8a42b7b" width="270">
<img src="https://github.com/user-attachments/assets/aded60e9-5008-44f7-ae90-d15a87f07e47" width="270">
<img src="https://github.com/user-attachments/assets/2442b719-adf1-44aa-8889-2dc669008e6b" width="270">

<img src="https://github.com/user-attachments/assets/e45924c3-0412-4d49-aa03-96dbd8a42b7b" width="270">
<img src="https://github.com/user-attachments/assets/aded60e9-5008-44f7-ae90-d15a87f07e47" width="270">
<img src="https://github.com/user-attachments/assets/2442b719-adf1-44aa-8889-2dc669008e6b" width="270">

<img src="https://github.com/user-attachments/assets/8d1a83cf-7503-44a3-b98b-a35d343fa7cb" width="270">
<img src="https://github.com/user-attachments/assets/86c5ad89-fd86-4c5a-ab96-23f0bd0a71b9" width="270">
<img src="https://github.com/user-attachments/assets/ca7c739e-63c9-42b8-8799-8dd11ae73a34" width="270">

<img src="https://github.com/user-attachments/assets/8d1a83cf-7503-44a3-b98b-a35d343fa7cb" width="270">
<img src="https://github.com/user-attachments/assets/86c5ad89-fd86-4c5a-ab96-23f0bd0a71b9" width="270">
<img src="https://github.com/user-attachments/assets/ca7c739e-63c9-42b8-8799-8dd11ae73a34" width="270">

---

## 🧭 Dataset Overview

Total train images: 642 / Total val images: 54

✅ keypoint_names = [ 'bucket', 'hinge1', 'hinge2', 'driver_seat', 'rear', 'b_hinge' ]  
✅ skeleton = [ (1,6), (2,3), (3,4), (4,5), (6,2) ] 

---

## 🏗️ Model Architecture

- 🦾 Model: **HRNet**
- 🦾 Type: **Top-down**
- 🦾 Det Model: **RTMDet**
- 🦾 Weight: **"td-hm_hrnet-w32_8xb64-210e_ubody-coco-256x192"**
- 🦾 Framework: **PyTorch + mmpose**
- 🦾 Input Size: **192, 256**
- 🦾 Trained Epochs: **20**

---

## 🎨 Visualization Samples

The model outputs of **validation set** are visualized:

📌 Example of val:
![Visualization val](Excavators-val-keypoints-results.png)  

---
