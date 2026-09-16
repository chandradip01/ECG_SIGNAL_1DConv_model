# ECG_SIGNAL_1DConv_model
1D-CNN model built in TensorFlow/Keras for multi-class ECG arrhythmia classification on the MIT-BIH dataset, featuring custom class imbalance weighting.
# 🫀 1D-CNN ECG Arrhythmia Classifier

An end-to-end Deep Learning pipeline built in TensorFlow/Keras to classify heartbeat signals from the **MIT-BIH Arrhythmia Dataset** into 5 distinct categories.

## 📌 Key Features
* **Model Architecture:** 3-block 1D Convolutional Neural Network (Conv1D, Batch Normalization, MaxPool1D) with a Global Average Pooling head.
* **Class Imbalance Handling:** Applied inverse frequency weighting via `scikit-learn` to prevent bias toward normal beat patterns.
* **Optimized Pipeline:** Structured for 3D signal arrays `(batch_size, 187, 1)` compliant with Keras 3 standards.

## 🛠️ Tech Stack
* **Language:** Python
* **Frameworks:** TensorFlow / Keras, Scikit-learn, NumPy, Pandas
