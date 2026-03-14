# Traffic Sign Classification using CNN 🚦

## 📌 Project Overview

This project builds a *Traffic Sign Recognition System* using a *Convolutional Neural Network (CNN)*.
The model is trained on traffic sign images to automatically classify them into *43 different categories*.

Traffic sign recognition is an important component in *autonomous driving systems* and *driver assistance technologies*.

---

## 🎯 Objective

The goal of this project is to:

* Preprocess and analyze traffic sign image data
* Train a CNN model for image classification
* Evaluate model performance using accuracy and classification metrics
* Build a system capable of predicting traffic signs from images

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* TensorFlow / Keras
* Scikit-learn
* PIL (Python Imaging Library)

---

## 📂 Project Structure


Project Structure

traffic-sign-recognition
│
├── traffic-sign-recognition-using-cnn.ipynb
├── traffic_classifier.h5
├── Train.csv
├── Test.csv
├── Meta.csv
├── README.md
└── LICENSE


---

## 🔄 Project Workflow

### 1️⃣ Data Loading

Traffic sign images are loaded from the dataset directory and resized to a standard dimension.

### 2️⃣ Data Preprocessing

* Images resized to *30×30 pixels*
* Normalization applied
* Labels encoded using *one-hot encoding*

### 3️⃣ Data Augmentation

Image augmentation techniques used:

* Rotation
* Zoom
* Width shift
* Shear transformation

This helps improve model generalization.

### 4️⃣ CNN Model Architecture

The CNN model includes:

* Convolutional layers
* Max pooling layers
* Dropout layers
* Fully connected dense layers
* Softmax output layer for *43 classes*

### 5️⃣ Model Training

The model is trained using:

* *Adam optimizer*
* *Categorical Crossentropy loss*
* *Batch size: 32*
* *Epochs: 6*

### 6️⃣ Model Evaluation

The model is evaluated using:

* Accuracy score
* Confusion matrix
* Classification report

---

## 📊 Model Performance

After training, the model predicts traffic sign classes on the test dataset and evaluates performance using accuracy and classification metrics.

---

## 🚀 Results

The trained model successfully classifies traffic sign images and demonstrates the capability of CNNs for *image classification tasks*.

---

## Model File

The trained CNN model is saved as:

traffic_classifier.h5

You can load the model using:

from tensorflow.keras.models import load_model
model = load_model("traffic_classifier.h5")

---

## ▶️ How to Run the Project

1. Clone the repository


git clone https://github.com/yourusername/traffic-sign-cnn.git


2. Install required libraries


pip install tensorflow numpy pandas matplotlib seaborn scikit-learn pillow


3. Run the notebook


traffic-sign-recognition-using-cnn.ipynb


---

## 📚 Future Improvements

* Increase training epochs for better accuracy
* Deploy the model as a web application
* Implement real-time traffic sign detection using a camera

---

## 👩‍💻 Author

*Muthulaxmi Lakhani*

Aspiring Data Scientist / AI Engineer
