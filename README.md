# 🌸 Iris Flower Species Prediction


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
```

### ▶️ Run the App

```bash
streamlit run app.py
```

---

## 📂 Code Structure

```python
# 1. Import libraries
# 2. Load dataset (cached)
# 3. Train a Random Forest model
# 4. Create sliders for user input
# 5. Make prediction based on input
# 6. Display the result
```

---

## 📸 Screenshot

![UI Screenshot] <img width="503" alt="image" src="https://github.com/user-attachments/assets/b6a97dd2-5f55-443b-9d67-fb1e4104492d" />


---

## 🤖 Example Output

> 🌸 **The predicted species is: versicolor**


---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
