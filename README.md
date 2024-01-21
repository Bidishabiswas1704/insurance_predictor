# 🏥 Medical Insurance Predictor System

## 🚀 Project Purpose

The Medical Insurance Predictor project is a sophisticated application utilizing data science and machine learning to deliver personalized insights into medical insurance charges. Employing a Decision Tree Regressor model, the system analyzes diverse health factors—such as age, BMI, number of children, smoking habits, and gender—to provide accurate predictions tailored to individual profiles.

## 🔍 Problem Statement

The project addresses the need for transparent and personalized predictions of medical insurance charges. By leveraging machine learning, it empowers users to make informed decisions about insurance coverage based on their unique health profiles.

## 📊 Key Aspects and Features

### 🔄 Decision Tree Regressor Model:
Utilizes an advanced machine learning model to analyze health parameters and predict accurate medical insurance charges.

### 🌐 User-Friendly Streamlit Web App:
Interactive web app developed with Streamlit, enabling users to navigate and explore medical insurance charges effortlessly.

### 🤖 Predictive Analytics:
Transparent and informed decision-making through precise predictions, providing insights into potential insurance costs.

### 📊 Data Visualization:
Visual representations of the impact of different health factors on insurance charges for a better understanding.

### 📈 Exploratory Data Analysis (EDA):
In-depth analysis of the medical insurance dataset to uncover patterns, trends, and correlations.

### 📉 Model Evaluation Metrics:
Utilizes key metrics such as Mean Absolute Error (MAE) and R-squared for assessing the accuracy of predictions.

### 🚀 Continuous Integration/Continuous Deployment (CI/CD):
Ensures code quality and deployment readiness with GitHub Actions for seamless integration.

### 🛑 Handling Outliers:
Incorporates techniques to identify and handle outliers in the dataset for improved model robustness.

## 🛠️ Technologies and Techniques Used

### 🐍 Python:
Implemented in Python, a versatile language widely used in data science.

### 📊 Pandas, NumPy, Matplotlib, Seaborn:
Data processing and visualization libraries to organize and analyze health data.

### 🤖 Scikit-Learn:
Machine learning library used for implementing the Decision Tree Regressor model.

### 🌐 Streamlit:
Web app development with Streamlit for an intuitive user experience.

### 📡 Requests:
Used for HTTP handling to enhance data retrieval and communication.

### 📈 GitHub Actions:
Continuous integration for code quality assurance.



## 📄 Usage
Clone the Repository:

```bash
git clone https://github.com/Bidishabiswas1704/insurance_predictor/tree/main

```

Install Dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit App:

```bash
streamlit run medical_insurance.py
``

Open the web browser and go to http://localhost:8501 to explore the medical insurance predictor application.

## 📊 Example Screenshots and User Guidance

### Step 1: Opening the Web App

![image](https://github.com/Bidishabiswas1704/HR_Insights_Dashboard/assets/140384850/a654b156-5389-48c3-9a8d-757b0d115c50)

- Navigate to the web app by running the provided command in the terminal.
- The initial screen presents a clean and user-friendly interface.

### Step 2: Adjusting Health Parameters

- Use the sliders to set your age, BMI, and the number of children.

![image](https://github.com/Bidishabiswas1704/insurance_predictor/assets/140384850/b9400833-bc07-4303-992a-c54dd1b38ea5)

- Select 'Yes' or 'No' to indicate whether you are a smoker.

![image](https://github.com/Bidishabiswas1704/insurance_predictor/assets/140384850/efa14cb0-4477-48a9-a13b-a5f20124378e)

- Choose your gender by clicking on 'Male' or 'Female'.

![image](https://github.com/Bidishabiswas1704/insurance_predictor/assets/140384850/18856fd3-f0db-4884-bbf6-3696e4ee1be0)

### Step 3: Predicting Insurance Charges

- After setting your health parameters, click the "Predict Insurance Charges" button.

![image](https://github.com/Bidishabiswas1704/insurance_predictor/assets/140384850/0697af35-6059-4847-931b-bf7bda46865d)

- The app processes your inputs using the advanced Decision Tree Regressor model.

### Step 4: Viewing Predictions

- The predicted insurance charges are displayed on the screen.

![image](https://github.com/Bidishabiswas1704/insurance_predictor/assets/140384850/27c88af7-5de0-4721-9a3d-b7a1c106aad5)

- The result provides transparency into the estimated cost based on your health profile.

### Special Feature: Currency Conversion

- The app goes beyond predictions with a special feature.
- The predicted values are automatically converted into the top five exchangeable currencies at the current rates.

![image](https://github.com/Bidishabiswas1704/insurance_predictor/assets/140384850/ee4bb597-d75d-4fb4-b8ca-1cb459317bfe)


### Recruiters and Users Note:
- As a recruiter or user, this intuitive interface allows for easy navigation and a seamless experience.
- Explore the power of predictive analytics and currency conversion all in one place!



## 📂 Directory Structure

```
.
├── data/
│   └── Medical_insurance.csv
├── notebooks/
│   └── Medical Insurance Predictor.ipynb
├── screenshots/
│   ├── ![Screenshot 1](https://github.com/Bidishabiswas1704/insurance_predictor/assets/140384850/c51a52f9-99c8-4dae-aa47-8347dae96f0d)

│   └── ![Screenshot 1]https://github.com/Bidishabiswas1704/insurance_predictor/assets/140384850/007542d2-3bc4-46aa-906e-46078d3028cf)

├── medical_insurance.py
├── insurane_predictor_dtr.pkl
├── requirements.txt
├── README.md
└── .github/https://github.com/Bidishabiswas1704/insurance_predictor
    └── workflows/
        └── ci_cd.yml
```

## 🤝 Contribution

Contributions are welcome! Feel free to open issues, propose new features, or submit pull requests.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Feel free to modify and adapt this template to suit the specifics of your Medical Insurance Predictor project.
