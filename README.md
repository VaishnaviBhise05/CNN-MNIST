# 🧠 CNN MNIST Digit Classification

A deep learning project that uses a **Convolutional Neural Network (CNN)** built with **TensorFlow/Keras** to classify handwritten digits from the **MNIST dataset**. The model is trained on thousands of grayscale images and accurately predicts digits from **0 to 9**.

---

## 📌 Project Overview

Handwritten digit recognition is one of the most common introductory problems in computer vision and deep learning. This project demonstrates how a CNN can automatically learn image features and classify handwritten digits with high accuracy.

The notebook covers the complete deep learning workflow:
- Data loading
- Data preprocessing
- CNN model creation
- Model training
- Performance evaluation
- Predictions on test images

---

## 🚀 Features

- 📊 Uses the MNIST handwritten digits dataset
- 🧠 Convolutional Neural Network (CNN)
- 📈 Model training and validation
- 🔍 Predicts handwritten digits (0–9)
- 📉 Training accuracy and loss visualization
- 💻 Implemented using Jupyter Notebook

---

## 🛠️ Tech Stack

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📂 Project Structure

```
CNN-MNIST/
│── CNN_Mnist.ipynb
│── README.md
│── requirements.txt
└── .gitignore
```

---

## 📚 Dataset

This project uses the **MNIST Handwritten Digit Dataset**.

Dataset Details:
- 70,000 grayscale images
- 60,000 training images
- 10,000 testing images
- Image size: **28 × 28 pixels**
- Classes: **Digits 0–9**

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/CNN-MNIST.git
```

Move into the project directory:

```bash
cd CNN-MNIST
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
CNN_Mnist.ipynb
```

Run all notebook cells.

---

## 📦 Requirements

```
tensorflow
numpy
matplotlib
jupyter
```

You can also install them manually:

```bash
pip install tensorflow numpy matplotlib jupyter
```

---

## 🧠 CNN Architecture

The model consists of:

- Convolution Layer
- ReLU Activation
- Max Pooling Layer
- Flatten Layer
- Dense Layer
- Output Layer (Softmax)

This architecture enables the model to automatically extract image features and classify handwritten digits accurately.

---

## 📈 Results

After training, the CNN model achieves high classification accuracy on the MNIST test dataset.

Typical performance:

- Training Accuracy: **≈99%**
- Test Accuracy: **≈98–99%**

(The exact values depend on the number of training epochs.)

---

## 📷 Sample Prediction

The trained model predicts handwritten digits such as:

```
Image → Predicted Digit

🖼️ → 7
🖼️ → 2
🖼️ → 9
🖼️ → 0
```

---

## 🎯 Learning Outcomes

Through this project, you will learn:

- Image preprocessing
- Convolutional Neural Networks
- TensorFlow/Keras fundamentals
- Model training and evaluation
- Deep learning workflow
- Image classification

---

## 🔮 Future Improvements

- Data augmentation
- Hyperparameter tuning
- CNN optimization
- Model deployment using Flask or Streamlit
- Real-time handwritten digit recognition
- Support for custom handwritten images

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Open a Pull Request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Vaishnavi**

Computer Science Engineering Student(AIDS)

Interested in:
- Artificial Intelligence
- Machine Learning
- Deep Learning
- Computer Vision
- Data Science

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.
