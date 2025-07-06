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

### Setup:
```bash
pip install -r requirements.txt

## 📊 Results

- **Test Accuracy:** 98.5% on the MNIST test set (10,000 samples)
- **Loss:** 0.04 (categorical crossentropy)
- Used **EarlyStopping** to prevent overfitting
- Confusion matrix shows strong performance across all digits
- Model confidently predicts most digits with > 99% certainty

