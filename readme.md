# 🔥 Algerian Forest Fire Prediction

A machine learning web application that predicts the **Fire Weather Index (FWI)** using real-world environmental data from Algeria.

## 🚀 Live Demo
[Deployed App](http://fwi-prediction-env.eba-xskemwgm.ap-south-1.elasticbeanstalk.com/)

---

## 📌 About the Project

Forest fires are a major environmental hazard. This project uses historical weather and environmental data from Algeria to predict the Fire Weather Index (FWI), which indicates the risk level of a forest fire occurring under given conditions.

---

## 🧠 Model

- **Algorithm:** Ridge Regression
- **Framework:** Scikit-learn
- **Evaluation Metrics:** R² Score, RMSE

---

## 📥 Input Features

| Feature | Description |
|---|---|
| Temperature | Ambient temperature (°C) |
| RH | Relative Humidity (%) |
| Ws | Wind Speed (km/h) |
| Rain | Rainfall (mm) |
| FFMC | Fine Fuel Moisture Code |
| DMC | Duff Moisture Code |
| ISI | Initial Spread Index |
| Classes | Fire/No Fire class |
| Region | Region of Algeria |

## 📤 Output

Predicted **Fire Weather Index (FWI)** value indicating fire risk level.

---

## 🛠️ Tech Stack

- **Language:** Python
- **Framework:** Flask
- **Libraries:** NumPy, Pandas, Scikit-learn
- **Deployment:** AWS Elastic Beanstalk

---

## ⚙️ How to Run Locally

```bash
# Clone the repository
git clone https://github.com/preet-99/FWI-Prediction.git
cd FWI-Prediction

# Install dependencies
pip install -r requirements.txt

# Run the app
python application.py
```

Open `http://10.224.209.45:5000` in your browser.

---

## 📁 Project Structure

```
FWI-Prediction/
├── app.py
├── model/
│   └── ridge_model.pkl
├── templates/
│   └── index.html
├── requirements.txt
└── README.md
```

---

## 👤 Author

**Preet** — [GitHub](https://github.com/preet-99) | [LinkedIn](https://www.linkedin.com/in/preet-vishwakarma-b775a7317)