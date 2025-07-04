# shallow-cnn-image-classification
This repository contains a Jupyter notebook implementing the shallow CNN architecture described in “[Shallow Convolutional Neural Network for Image Classification](paper/Shallow_CNN_for_Image_Classification.pdf)”. I demonstrate its performance on MNIST, Fashion‑MNIST, and CIFAR‑10 datasets.


---

## 💻 Environment & Installation

1. **Clone this repo**
   ```bash
   git clone https://github.com/AryaKoureshi/shallow-cnn-image-classification.git
   cd shallow-cnn-image-classification
   ```

2. **Create a virtual environment**

   ```bash
   python3 -m venv venv
   source venv/bin/activate     # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

---

## 📝 Notebook Overview

The notebook (`Shallow_CNN_for_Image_Classification.ipynb`) contains:

1. **Data Loading & Preprocessing**

   * MNIST, Fashion‑MNIST, CIFAR‑10
   * Normalization, one‑hot encoding, optional resizing

2. **Model Definition**

   * Shallow CNN: 2×Conv2D → MaxPooling → Flatten → Dense
   * BatchNormalization & Dropout for regularization
   * SGD optimizer

3. **Training & Evaluation**

   * Trained for 10–20 epochs
   * Plots of training vs. validation accuracy & loss
   * Final test accuracy on each dataset

4. **Results Summary**

   * **MNIST**: \~98% test accuracy
   * **Fashion‑MNIST**: \~91% test accuracy
   * **CIFAR‑10**: \~60% test accuracy

   (See the notebook’s final cells for precise numbers and graphs.)

---

## 📈 Results

The notebook produces:

* **Accuracy curves** for training vs. validation
* **Loss curves** for training vs. validation
* **Bar chart** comparing final test accuracies across datasets

---

## 🛠️ How to Run

1. Launch Jupyter:

   ```bash
   jupyter lab
   ```
2. Open `Shallow_CNN_for_Image_Classification.ipynb`.
3. Run all cells sequentially.

All figures and final metrics will appear in‑notebook.
