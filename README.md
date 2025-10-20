# Healthcare_Premium_Prediction

Here’s a professional and detailed **README.md** content you can use for your GitHub project **Healthcare_Premium_Prediction** based on the image you provided and typical Streamlit ML project structure:

---

# 🩺 Healthcare Premium Prediction

This project aims to predict **health insurance premiums** based on individual demographic and lifestyle factors such as age, BMI, gender, smoking habits, and region. The model uses **Machine Learning algorithms** to estimate the insurance premium, helping insurance companies and individuals make data-driven decisions.

---

## 🚀 Project Overview

The **Healthcare Premium Prediction** system is designed to:

* Analyze a user’s health and demographic information.
* Predict the expected premium amount using a trained ML model.
* Provide an interactive and easy-to-use interface built with **Streamlit**.

It demonstrates how machine learning can be applied to real-world insurance and healthcare-related problems.

---

## 📂 Repository Structure

```
Healthcare_Premium_Prediction/
│
├── artifacts/                         # Saved model, scaler, and encoder files
├── ColabNoteBook_&_DataSets.zip       # Dataset and Jupyter/Colab notebook
├── HelthCare_Premium_Prediction_Demo.mp4  # Demo video of the Streamlit app
├── LICENSE                            # License file
├── README.md                          # Project documentation (this file)
├── main.py                            # Streamlit web app entry point
├── prediction_helper.py               # Helper functions for model prediction
└── requirements.txt                   # Python dependencies
```

---

## ⚙️ Features

✅ Predicts health insurance premiums based on input parameters.
✅ Uses pre-trained ML models for quick and accurate predictions.
✅ Clean and interactive **Streamlit UI**.
✅ Modular code structure for scalability.
✅ Supports easy deployment on cloud platforms like **Streamlit Cloud** or **Heroku**.

---

## 🧠 Machine Learning Model

The dataset used contains information such as:

* **Age**
* **Gender**
* **BMI** (Body Mass Index)
* **Children** (Number of dependents)
* **Smoker status**
* **Region**

### Model Workflow:

1. Data Preprocessing (handling categorical data, scaling numerical data).
2. Model Training (Linear Regression / Random Forest / XGBoost).
3. Model Evaluation (using R² score, MAE, MSE).
4. Saving trained model in `artifacts/` for Streamlit use.

---

## 🧩 Tech Stack

* **Python 3.10+**
* **Streamlit** – for web app interface
* **scikit-learn** – for ML model training and evaluation
* **pandas**, **numpy** – for data handling
* **pickle/joblib** – for model serialization

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/TechNarendra25/Healthcare_Premium_Prediction.git
cd Healthcare_Premium_Prediction
```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Run the Streamlit App

```bash
streamlit run main.py
```

The app will open in your browser (default: `http://localhost:8501`).

---

## 📊 Example Output

After entering details such as age, BMI, smoker status, and region, the app displays:

> 💰 **Predicted Annual Premium: ₹xxxxx.**

---

## 📽️ Demo

A working demo video is available in the repository:
`HelthCare_Premium_Prediction_Demo.mp4`

---

## 📁 Dataset

The dataset used for training is included inside `ColabNoteBook_&_DataSets.zip`.
It is a modified version of the popular **Medical Insurance Cost Dataset** (Kaggle).

---

## 📜 License

This project is licensed under the **Apache 2.0 License** – see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Developed by:** [TechNarendra25](https://github.com/TechNarendra25)
**Role:** AI/ML Developer | Data Science Enthusiast
**Contact:** [tech.narendra25@gmail.com](mailto:tech.narendra25@gmail.com)

