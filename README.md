# Food Safety Compliance Prediction System

## Overview

The **Food Safety Compliance Prediction System** is a web-based application designed to predict whether a packaged food item complies with food safety regulations. The system uses machine learning models to evaluate food items based on various attributes and determine their compliance status. Users can interact with the system via a user-friendly interface that allows them to select food items and view their compliance status in real time.

## Key Features

- **Predict Compliance**: The system predicts if a food item is safe for consumption based on its attributes like main ingredient, shelf life, packaging type, etc.
- **Machine Learning**: The backend uses machine learning models (Random Forest Classifier) to analyze food safety data and predict compliance.
- **Database Integration**: The application connects to a MySQL database to store and retrieve food data for prediction.
- **Interactive UI**: Users can select food items and input various parameters using dropdowns and buttons to see the predicted compliance status.
- **Real-Time Analysis**: The system provides real-time feedback on food compliance, helping businesses and consumers ensure that food items meet safety standards.

## Tech Stack

- **Frontend**: Streamlit (for creating the interactive UI)
- **Backend**: Python (with libraries such as `scikit-learn`, `pandas`, `numpy`)
- **Database**: MySQL (for storing food safety data)
- **Machine Learning**: scikit-learn (Random Forest Classifier)

## Installation

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- MySQL Database
- Streamlit (`pip install streamlit`)
- scikit-learn (`pip install scikit-learn`)
- pandas (`pip install pandas`)
- numpy (`pip install numpy`)
