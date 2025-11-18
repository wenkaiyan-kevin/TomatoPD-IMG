# Tomato Pests and Diseases Detection Dataset  
*Supporting the paper: **“YOLOv11n-KL: A Lightweight Tomato Pests and Diseases Detection Model for Edge Devices”***

## 📘 Overview  
This repository provides a high-quality tomato pests and diseases image dataset used in our paper **YOLOv11n-KL: A Lightweight Tomato Pests and Diseases Detection Model for Edge Devices**.  
The dataset supports research on lightweight and efficient agricultural vision systems by offering diverse, reliable, and well-annotated images covering major tomato diseases and pests.

## 📂 Dataset Description  
To construct a representative dataset for tomato pests and diseases detection, image resources were collected from multiple publicly available sources, including:

- **AI Challenger 2018**
- **Agricultural Pest and Disease Image Library** (Chinese Academy of Sciences)
- Additional open agricultural datasets

The dataset was processed following a standardized workflow, including:

- Data cleaning and quality control  
- Removal of duplicates, blurred, and low-resolution images  
- Expert annotation and manual verification by agricultural specialists  

After preprocessing, **10,429 high-quality images** with a unified resolution of **640 × 640 × 3** were retained to form the final dataset.

## 🏷️ Category Information  
A total of **13 categories** are included, covering both fruit-related and leaf-related symptoms.

### **Fruit-related Categories**
- Healthy Fruit  
- Sunscald  
- Blossom End Rot  
- Fruit Cracking  
- Spotted Wilt Virus (Fruit)  
- Bacterial Spot (Fruit)

### **Leaf-related Categories**
- Mosaic Virus  
- Late Blight  
- Early Blight  
- Leaf Miner Damage  
- Leaf Mold  
- Septoria Leaf Spot  
- Spider Mite Damage  
- Yellow Leaf Curl Virus  
- Healthy Leaf

This diversity enhances the model's robustness and generalization ability in complex agricultural environments.

## 📊 Dataset Split  
The dataset is randomly divided into training, validation, and test subsets at an **8:1:1** ratio:

| Subset      | Ratio | Image Count |
|-------------|-------|-------------|
| Training    | 80%   | – |
| Validation  | 10%   | – |
| Test        | 10%   | – |

*(Add exact counts if required.)*

## 📁 File Structure  
A typical folder organization is as follows:

