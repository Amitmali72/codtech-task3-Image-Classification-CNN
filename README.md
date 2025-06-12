# codtech-task3-Image-Classification-CNN
# 🧠 Task 3 - CNN Based Image Classification | CodTech Internship

This project implements a Convolutional Neural Network (CNN) using **TensorFlow** and **Keras** to classify handwritten digits from the **MNIST** dataset. It is part of the Task 3 submission for the CodTech AI/ML internship.

---

## 📚 Dataset: MNIST

- **Total Samples**: 70,000 (60,000 train + 10,000 test)
- **Image Size**: 28x28 pixels (grayscale)
- **Classes**: Digits from 0 to 9 (10 classes)

---

## 🏗️ Model Architecture

| Layer            | Output Shape      | Parameters |
|------------------|-------------------|------------|
| Conv2D (32, 3x3) | (26, 26, 32)      | 320        |
| MaxPooling2D     | (13, 13, 32)      | 0          |
| Conv2D (64, 3x3) | (11, 11, 64)      | 18,496     |
| MaxPooling2D     | (5, 5, 64)        | 0          |
| Flatten          | (1600)            | 0          |
| Dense (128)      | (128)             | 204,928    |
| Dropout (0.2)    | -                 | 0          |
| Dense (10)       | (10 - softmax)    | 1,290      |

✅ **Activation Function**: ReLU  
✅ **Optimizer**: Adam  
✅ **Loss**: Sparse Categorical Crossentropy  
✅ **Metrics**: Accuracy  

---

## 📊 Results

| Metric        | Value    |
|---------------|----------|
| 🧪 Test Accuracy | **98.85%** |
| 🔥 Test Loss     | 0.0402   |

- ✅ Accuracy and loss graphs plotted
- ✅ True vs Predicted labels visualized for sample images

---

## 🧾 Files Included

| File Name                         | Description                               |
|----------------------------------|-------------------------------------------|
| `Task3_CNN_Image_Classification.ipynb` | Jupyter notebook with full code          |
| `mnist_model.keras` *(optional)* | Trained model saved in Keras format       |
| `README.md`                      | Project description and usage             |

---

## 🔧 Tools Used

- Python
- TensorFlow & Keras
- Matplotlib
- NumPy

---

## 📌 How to Run

1. Clone the repository:
   ```bash
  git clone https://github.com/your-username/Task3_Image_Classification.git(https://github.com/Amitmali72/codtech-task3-Image-Classification-CNN)
