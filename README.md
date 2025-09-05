
# 🚗 Car Price Predictor

This project is a Machine Learning web application built with Flask that predicts the selling price of used cars based on features like company, car model, year, fuel type, and kilometers driven.



# ⚙️ Installation
  1.  Clone the Repository
  ```
  git clone https://github.com/your-username/Car_Price_Predictor.git
cd Car_Price_Predictor
```
2. Create Virtual Environment (Optional but Recommended)
```
python -m venv .venv
source .venv/bin/activate   # On Mac/Linux
.venv\Scripts\activate      # On Windows

```
3. Install Dependencies
```
pip install -r requitement.txt

```


## 📂 Project Structure

```
Car_Price_Predictor/
│
├── application.py              # Flask backend application
├── LinearRegressionModel.pkl   # Trained ML model (Pickle file)
├── Cleaned_Car_data.csv        # Dataset used for predictions
├── Car_Price_Predictor.ipynb   # Jupyter Notebook (model training)
├── requitement.txt             # Python dependencies
└── templates/
    └── index.html              # Frontend HTML template (Flask uses this)
```
---
## 🖼️ Screenshots

![Image](https://github.com/user-attachments/assets/70169fa2-44de-4be3-831f-70314dab1eea)


## 📊 How it Works

1. User selects:

* Car Company

* Car Model

* Year

* Fuel Type

* Kilometers Driven

2. Flask sends this data to the ML model (LinearRegressionModel.pkl).

3. Model predicts the selling price.

4. Prediction is displayed on the screen

---

## 🛠️ Tech Stack

Backend: Flask, Flask-CORS

ML Model: scikit-learn (Linear Regression with preprocessing)

Frontend: HTML (Jinja2 templates)

Dataset: Cleaned car price dataset (Cleaned_Car_data.csv)

---

