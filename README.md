# intel-image-classification-CNN
A deep learning project using CNN to classify natural scene images (buildings, forest, glacier, mountain, sea, street) with TensorFlow/Keras, including preprocessing, training, evaluation, and visualization.

# 🌄 Intel Image Classification using CNN

## 📌 Project Overview

This project focuses on building a **Convolutional Neural Network (CNN)** to classify natural scene images into six categories:

* Buildings
* Forest
* Glacier
* Mountain
* Sea
* Street

The model is trained on the **Intel Image Classification Dataset** and demonstrates the complete deep learning pipeline:
data preprocessing → model building → training → evaluation → prediction.

---

## 🎯 Objectives

* Understand image data and preprocessing techniques
* Build a CNN model from scratch
* Improve model performance using data augmentation
* Evaluate using multiple metrics
* Visualize predictions and results

---

## 📂 Dataset

* Dataset: Intel Image Classification Dataset (Kaggle)
* Total Images: 25,000+
* Classes: 6

Directory structure:

```
seg_train/
seg_test/
seg_pred/
```

---

## ⚙️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🔧 Data Preprocessing

* Resized all images to **150×150**
* Normalized pixel values (0–1)
* Split dataset into training and validation sets
* Applied data augmentation:

  * Rotation
  * Zoom
  * Horizontal flip
  * Width & height shift

---

## 🧠 Model Architecture

* 3 Convolutional Layers (ReLU activation)
* Max Pooling Layers
* Fully Connected Dense Layer
* Dropout for regularization
* Output Layer with Softmax (6 classes)

---

## 🚀 Model Training

* Optimizer: Adam
* Loss Function: Categorical Crossentropy
* Metrics: Accuracy
* Techniques used:

  * Early Stopping
  * Model Checkpointing

---

## 📊 Results

* Achieved high accuracy on validation and test datasets
* Training vs Validation curves plotted
* Model generalized well with minimal overfitting

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score (per class)
* Confusion Matrix

---

## 🔍 Model Evaluation

* Classification report generated using sklearn
* Confusion matrix visualized using heatmap

---

## 🖼️ Predictions

* Visualized predictions on random test images
* Compared **Actual vs Predicted labels**

---

## 📷 Sample Output

* Correct classification of scene images
* Few misclassifications observed in similar classes (e.g., glacier vs mountain)

---

## 💡 Key Learnings

* CNNs automatically extract spatial features
* Data augmentation improves generalization
* Dropout helps reduce overfitting
* Proper validation is critical for model performance

---

## 🚀 Future Improvements

* Use Transfer Learning (ResNet, VGG16, MobileNet)
* Hyperparameter tuning
* Deploy model using Flask / FastAPI
* Convert into a web application

---


## 📌 Conclusion

This project demonstrates how CNNs can effectively classify images by learning hierarchical features, making them powerful for real-world computer vision tasks.

