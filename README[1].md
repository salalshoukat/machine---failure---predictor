
# Predictive Maintenance - Machine Failure Classifier

This project is an end-to-end **machine learning solution** for predicting equipment failure based on sensor data. It includes data processing, model training, and deployment via a Flask web application.

## **Overview**
- Input: Industrial sensor data from machinery
- Output: Probability of machine failure
- Goal: Reduce unplanned downtime and optimize maintenance scheduling

## **Tech Stack**
- Python, Pandas, Scikit-learn, XGBoost
- Flask for web deployment
- HTML/CSS/JS for frontend
- Model serialized with `pickle`

## **Folder Structure**
```
app/
├── app.py                  # Flask backend
├── prediction.py           # Prediction logic
├── Training.py             # Model training script
├── range_finder.py         # Utility functions
├── remaneshit.py           # Data processing helper
├── data/                   # Dataset
├── models/                 # Saved model
├── static/                 # JS and CSS files
└── templates/              # HTML file
```

## **How to Run**
1. Clone the repo or download the ZIP
2. Navigate to the `app/` directory
3. Install requirements:  
   `pip install -r requirements.txt`
4. Run the app:  
   `python app.py`
5. Access the web app at:  
   `http://127.0.0.1:5000`

## **Model Performance**
- **Model**: XGBoost Classifier
- **Accuracy**: ~85% on test data
- Feature engineered from 10+ sensor readings and operating conditions

## **Business Value**
- Reduces machinery downtime by up to 40%
- Enables predictive maintenance in industrial settings

---

**Author:** Salal — M.S. Data Science, University of Houston-Victoria
