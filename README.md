# MONK Dataset Classification using Feedforward Network and SOM 🧠🤖

This project explores the classification of symbolic MONK datasets using machine learning models, specifically:
- **Feedforward Neural Networks (FFNN)**
- **Self-Organizing Maps (SOM)**

The MONK problems are synthetic but challenging classification tasks used to evaluate learning algorithms, especially with symbolic and categorical data.

---

## 📊 Dataset: MONK

- **Instances**: 432
- **Attributes**: `a1`–`a6` (categorical), `id`, and binary class label
- **Class Versions**: MONK-1, MONK-2, MONK-3 — each with distinct logical rules for class membership

### Attributes Description:

| Feature | Meaning         | Values                           |
|---------|------------------|----------------------------------|
| a1      | Head shape       | round, square, octagon           |
| a2      | Body shape       | round, square, octagon           |
| a3      | Is smiling       | yes, no                          |
| a4      | Holding          | sword, balloon, flag             |
| a5      | Jacket color     | red, yellow, green, blue         |
| a6      | Has tie          | yes, no                          |

---

## 🧠 Models Used

### 🔹 Self-Organizing Map (SOM)
- Unsupervised clustering and topology-preserving projection
- Trained to find structure in the MONK data and visualize class separability

### 🔹 Feedforward Neural Network
- Supervised learning for binary classification
- Trained on encoded categorical features using TensorFlow/Keras
- Optimized using `Optuna` hyperparameter tuning

---

## 🔧 Libraries

- `minisom` – for SOM training
- `tensorflow`, `keras` – for FFNN
- `optuna` – hyperparameter optimization
- `scikit-learn`, `pandas`, `matplotlib`, `tqdm`

---

## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib ucimlrepo scikit-learn optuna tensorflow minisom tqdm ipywidgets
   ```

2. Launch the notebook:
   ```bash
   jupyter notebook monk_feedforwad_Som.ipynb
   ```

3. Run the cells to:
   - Load and preprocess the MONK dataset
   - Train a SOM and visualize clustering
   - Train and evaluate a feedforward network

---

## 🎯 Learning Goals

- Work with symbolic datasets
- Apply neural networks to categorical data
- Combine unsupervised and supervised learning
- Explore visualization and model optimization

---

## 📌 Credits

- Author: FW

---

