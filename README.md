# Heart Disease Risk Predictor 🫀

A machine learning-powered web application that predicts the risk of heart disease based on various health parameters.

## 🚀 Live Demo

**Try the app here:** [Heart Disease Risk Predictor](https://heart-disease-risk-predictor-jrxnjwwebgh2dyjhp7vudf.streamlit.app/)

## 📋 Description

This application uses a K-Nearest Neighbors (KNN) machine learning model to assess the risk of heart disease. Users can input their health metrics and receive an instant prediction about their heart disease risk level.

## ✨ Features

- **Interactive User Interface**: Easy-to-use sliders and dropdown menus for data input
- **Real-time Predictions**: Instant risk assessment based on input parameters
- **Machine Learning Powered**: Uses trained KNN model with standardized scaling
- **User-Friendly Results**: Clear visual feedback with color-coded risk indicators

## 🔧 Input Parameters

The application requires the following health metrics:

- **Age**: 18-100 years
- **Sex**: Male (M) or Female (F)
- **Chest Pain Type**: ATA, NAP, TA, or ASY
- **Resting Blood Pressure**: mm Hg
- **Cholesterol**: mg/dL
- **Fasting Blood Sugar**: > 120 mg/dL (Yes/No)
- **Resting ECG**: Normal, ST, or LVH
- **Max Heart Rate**: Beats per minute
- **Exercise-Induced Angina**: Yes (Y) or No (N)
- **Oldpeak**: ST Depression value
- **ST Slope**: Up, Flat, or Down

## 🛠️ Technology Stack

- **Frontend**: Streamlit
- **Data Processing**: Pandas, NumPy
- **Machine Learning**: Scikit-learn (KNN Classifier)
- **Model Persistence**: Joblib

## 📦 Installation

To run this application locally:

1. Clone the repository:
```bash
git clone <your-repo-url>
cd <your-repo-directory>
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Run the Streamlit app:
```bash
streamlit run app.py
```

## 📄 Requirements

```
streamlit
pandas
numpy
scikit-learn
joblib
```

## 🎯 Model Information

The application uses three pre-trained files:
- `KNN_heart.pkl`: Trained K-Nearest Neighbors model
- `scaler.pkl`: StandardScaler for feature normalization
- `columns.pkl`: Expected feature columns for proper data alignment

## ⚠️ Disclaimer

**Important**: This application is for educational and informational purposes only. It should NOT be used as a substitute for professional medical advice, diagnosis, or treatment. Always consult with qualified healthcare professionals for medical concerns.

## 👨‍💻 Author

**Abhishek**

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📧 Contact

For questions or feedback, please open an issue in the repository.

---

**Note**: The predictions are based on statistical models and historical data. Individual health outcomes can vary significantly.
