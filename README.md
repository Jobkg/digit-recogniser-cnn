# 🧠 Digit Recogniser using CNN (MNIST)

A simple yet powerful Convolutional Neural Network (CNN) built with TensorFlow and trained on the MNIST dataset to recognise handwritten digits (0–9).

---

## 📌 Features

- Preprocessing and normalisation of image data
- CNN with Conv2D, MaxPooling, Dense, Dropout layers
- EarlyStopping to prevent overfitting
- Visualisation of predictions and model confidence
- Confusion matrix to evaluate performance

---

## 📁 Files

- `mnist_cnn.ipynb` – Full Jupyter Notebook with model code, training, evaluation and visualisations
- `README.md` – You're reading it!
- *(Optional)* `requirements.txt` – All dependencies if you want others to run it

---

## 🚀 Getting Started

### Requirements:
- Python 3.x
- TensorFlow
- Matplotlib
- NumPy
- scikit-learn (for confusion matrix)

## 📊 Results

- **Test Accuracy:** 98.5% on the MNIST test set (10,000 samples)
- **Loss:** 0.04 (categorical crossentropy)
- Used **EarlyStopping** to prevent overfitting
- Confusion matrix shows strong performance across all digits
- Model confidently predicts most digits with > 99% certainty

## 📚 Dataset

- **MNIST Handwritten Digits** from Yann LeCun’s dataset
- 60,000 training images and 10,000 test images
- Each image is a **28x28 grayscale pixel** digit (0–9)
- Labels are **one-hot encoded** for classification
- Downloaded via TensorFlow's built-in Keras dataset loader

![sample digit image](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

## ✍️ Author

- **Job [Gandhi]**
- Final Year BSc Computer Science Student
- University of Essex
- [GitHub Profile](https://github.com/Jobkg)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/18X5dvhZ7_T4hT-B_w_SlHj0YSjbpNfD4#scrollTo=szXbe8O12p31)


### Setup:
```bash
pip install -r requirements.txt


