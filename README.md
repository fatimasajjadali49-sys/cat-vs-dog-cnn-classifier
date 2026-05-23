# Cat vs Dog Image Classification using CNN (MobileNetV2)

##  Project Overview
This project is a deep learning image classification model that classifies images of cats and dogs using **Convolutional Neural Networks (CNN)** with **Transfer Learning (MobileNetV2)**.  
The model is built using TensorFlow/Keras and trained on the Cats vs Dogs dataset from TensorFlow Datasets (TFDS).

---

##  Features
- Transfer Learning using MobileNetV2 (ImageNet pretrained)
- Image preprocessing and normalization
- Data augmentation (flip, rotation, zoom, contrast)
- CNN classification head
- Model evaluation (Accuracy, Loss, Confusion Matrix, ROC Curve)
- Custom image prediction support
- Model saving and reusability (.keras format)

---

##  Tech Stack
- Python  
- TensorFlow / Keras  
- TensorFlow Datasets (TFDS)  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

##  Dataset
- Cats vs Dogs dataset (TensorFlow Datasets)
- Binary classification problem:
  - Class 0: Cat   
  - Class 1: Dog   

---

##  Model Architecture
- Base Model: MobileNetV2 (Pretrained on ImageNet)
- GlobalAveragePooling2D
- Batch Normalization
- Dense layers with ReLU activation
- Dropout for regularization
- Output layer: Sigmoid (Binary classification)

---

##  Results
- Accuracy: ~98%+
- High precision and recall
- Strong generalization using transfer learning

---

##  Project Structure
cat-vs-dog-cnn-classifier/
│
├── cat_vs_dog.ipynb
├── cats_dogs_model.keras
├── README.md
└── requirements.txt

---

##  How to Run

### 1. Install dependencies
pip install tensorflow tensorflow-datasets numpy matplotlib scikit-learn

### 2. Run notebook
Open Jupyter Notebook or Google Colab and run all cells step by step.

### 3. Load saved model (optional)
model = tf.keras.models.load_model("cats_dogs_model.keras")

---

##  Objective
To build a high-accuracy image classification model using deep learning and transfer learning techniques.
---

##  Note
This project is for learning and portfolio building purposes (Deep Learning / Computer Vision basics).

## ⭐ Note
This project is for learning and portfolio building purposes (Deep Learning / Computer Vision basics).
