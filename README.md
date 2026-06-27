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

## Metrics 
<img width="501" height="198" alt="image" src="https://github.com/user-attachments/assets/82b220d5-9e7a-4004-80f9-1457da064f0f" />

## Validation Set
<img width="466" height="184" alt="image" src="https://github.com/user-attachments/assets/944d38a1-065e-45d0-9d43-eb0f4b329a46" />


## Test Set
<img width="471" height="185" alt="image" src="https://github.com/user-attachments/assets/76014d69-7f87-4f9a-9c54-2449c57190b1" />

## Model Performance 
<img width="1485" height="884" alt="image" src="https://github.com/user-attachments/assets/079b8f96-2f28-4dd3-bfe5-92df98b7fb9a" />


---

## How to Run
```bash
pip install -r requirements.txt
python training_yolov8.py
