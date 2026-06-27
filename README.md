# Bee Object Detection using YOLOv8

## Project Overview
This project implements an object detection system using the YOLOv8 deep learning model to identify and classify bee-related objects:
- Queen Bee
- Worker Bee
- Drone Bee
- Varroa Mite

The project demonstrates the complete machine learning workflow, including data preparation, model training, evaluation, and deployment.

---

## Key Features
- YOLOv8-based object detection (Ultralytics)
- Data augmentation (flip, rotation, brightness, blur, cropping)
- Hyperparameter tuning (epochs, batch size, learning rate)
- Optimizer comparison (SGD, Adam, AdamW)
- Model evaluation using Precision, Recall, and mAP
- Object counting system for real-world hive monitoring

---

## Results
- **mAP@50:** ~0.79
- **Precision:** ~0.82
- **Recall:** ~0.73

### Key Observations
- Strong performance for Worker and Queen Bees
- Moderate performance for Drone Bees
- Lower performance for Varroa Mites due to small object size
- Detection accuracy depends on feature clarity and object visibility

---

## Learning Outcomes
- Understanding of full ML pipeline  
- Training and evaluating deep learning models  
- Importance of hyperparameter tuning  
- Real-world challenges such as class imbalance and small object detection  

---

## Technologies Used
- Python
- PyTorch
- Ultralytics YOLOv8
- Roboflow
- Google Colab

---

## Dataset
Roboflow Dataset:  
https://universe.roboflow.com/varuns-workspace-u056q/bee-object-detection-final

---

## How to Run
```bash
pip install -r requirements.txt
python machine_learning_assesment_2_varun.py
