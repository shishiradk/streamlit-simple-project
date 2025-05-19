# 🌸 Iris Flower Species Prediction

![Iris Prediction UI](b469e348-a030-4c43-9e04-b4263739f8ef.png)

This web app allows you to **predict the species of an Iris flower** using a **Random Forest Classifier** trained on the classic [Iris dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html). It’s built with **Streamlit** and features an interactive UI for exploring how the flower’s features influence the prediction.

---

## 🚀 Features

- 📊 Uses **sepal and petal measurements** as inputs.
- 🔍 Real-time prediction of **Iris species** (Setosa, Versicolor, or Virginica).
- 🧠 Powered by a **Random Forest Classifier**.
- ⚡ Live slider interface to adjust input features dynamically.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas** & **NumPy**
- **Scikit-learn**
- **Streamlit**

---

## 🧪 How It Works

1. Load the built-in Iris dataset.
2. Train a `RandomForestClassifier` on the dataset.
3. Let users adjust the input features via sliders.
4. Predict and display the Iris species instantly.

---

## 🖥️ Usage

### 🔧 Requirements

```bash
pip install streamlit scikit-learn pandas numpy

