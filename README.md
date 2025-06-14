# Wildfire Prediction Model

This project predicts the likelihood of wildfires based on satellite images of forests using a Machine Learning model built with TensorFlow. The model is wrapped in an interactive web application using Streamlit.

---
## Web Application Link
 Link: https://forest-fire-prediction-app-twrs4cwtgmvonuzspdegxi.streamlit.app/

---

## 📂 Project Structure

```
├── app.py               # Streamlit application
├── model.h5             # Trained TensorFlow model
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation (this file)
├── wildfire_dataset     # Dataset file (downloaded from Kaggle)
```

---

## 🧰 Requirements

All required Python libraries are listed in the `requirements.txt` file. Key libraries include:

- **Streamlit**: For the web application UI
- **TensorFlow**: For the ML model
- **Pillow (PIL)**: For image handling
- **NumPy**: For numerical operations

Install them using:

```bash
pip install -r requirements.txt
```

---

## 📊 Dataset

- **Source**: [Wildfire Prediction Dataset on Kaggle](https://www.kaggle.com/datasets/abdelghaniaaba/wildfire-prediction-dataset?resource=download)
- Description: The dataset includes environmental and meteorological factors useful for predicting wildfire occurrences.

---

## 🚀 Running the App

To run the Streamlit application locally:

```bash
streamlit run app.py
```

---

## 🔍 Features

- **Wildfire Prediction**: Predict wildfire possibility based on input image
- **Interactive Interface**: Simple Streamlit-based UI.
- **Pre-trained Model**: TensorFlow model 

---


## 🙌 Acknowledgments

- Dataset by [Abdelghani Aaba on Kaggle](https://www.kaggle.com/datasets/abdelghaniaaba/wildfire-prediction-dataset).

---

## ⚠️ Disclaimer

This model is for educational and research purposes only and should not be used for real-life wildfire prediction or prevention without professional validation.

