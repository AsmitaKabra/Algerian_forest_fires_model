# Forest Fire Prediction - End-to-End ML Web Application

## Project Overview
This project is an end-to-end Machine Learning web application developed to predict forest fire risk using environmental and weather-related parameters. The application allows users to input values such as temperature, humidity, wind speed, rain, and other fire weather indices to generate predictions using a trained Ridge Regression model.

The project demonstrates:
- Data preprocessing
- Feature engineering
- Exploratory Data Analysis (EDA)
- Model training and evaluation
- Model deployment using Flask
- Frontend integration using HTML/CSS

---

## Tech Stack
- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- HTML/CSS
- Pickle

---

## Features
- User-friendly web interface
- Real-time prediction generation
- Data scaling using StandardScaler
- Ridge Regression model integration
- End-to-end ML pipeline

---

## Project Structure

```bash
project/
│
├── application.py
├── requirements.txt
├── README.md
│
├── models/
│   ├── ridge.pkl
│   └── scaler.pkl
│
├── templates/
│   ├── index.html
│   └── home.html
│
├── notebooks/
│   ├── EDA&FeatureSelection.ipynb
│   └── model training.ipynb
│
├── screenshots/
│   ├── home.png
│   └── result.png
```

---

## Machine Learning Workflow
1. Data Collection  
2. Data Cleaning  
3. Exploratory Data Analysis  
4. Feature Selection  
5. Data Scaling  
6. Model Training  
7. Model Evaluation  
8. Model Serialization using Pickle  
9. Flask App Development  
10. Deployment Ready Application  

---

## Input Parameters
The model uses the following features:
- Temperature
- Relative Humidity (RH)
- Wind Speed (Ws)
- Rain
- FFMC
- DMC
- ISI
- Classes
- Region

---

## Model Used
### Ridge Regression

Reason for selection:
- Helps reduce overfitting
- Performs well on multicollinearity
- Provides stable predictions

---

## Installation & Setup

### Clone Repository
```bash
git clone https://github.com/AsmitaKabra/Algerian_forest_fires_model.git
```

### Navigate to Project Directory
```bash
cd Algerian_forest_fires_model
```

### Create Virtual Environment
```bash
python -m venv venv
```

### Activate Virtual Environment

#### Windows
```bash
venv\Scripts\activate
```

#### Mac/Linux
```bash
source venv/bin/activate
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run Application
```bash
python application.py
```

---

## Learning Outcomes
Through this project, I learned:
- End-to-end ML workflow
- Flask integration with ML models
- Model deployment basics
- Data preprocessing techniques
- Frontend and backend integration

---

## Future Improvements
- Deploy on Render
- Add advanced ML models
- Improve UI/UX
- Add prediction visualizations
- Add model comparison dashboard

---

## Author
Asmita Kabra  
AI & Data Science Student

---

## Connect With Me
- LinkedIn: www.linkedin.com/in/asmita-kabra-1a6298342
- GitHub: https://github.com/AsmitaKabra

---

## License
This project is for educational and learning purposes.
