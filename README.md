# Customer Churn Prediction Project

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://customer-churn-prediction-project.streamlit.app)  
_A machine learning application to predict customer churn in the banking sector._

## Overview

This project provides an end-to-end solution for predicting customer churn based on various demographic and account information. The application uses multiple machine learning models to assess the probability of customer churn and displays insights through an interactive web app.

## Features

- **Interactive Web Interface**: Built with Streamlit for easy navigation and interactivity.
- **Multiple ML Models**: Compares predictions from models like XGBoost, Random Forest, and K-Nearest Neighbors.
- **Churn Explanation and Email Generation**: Uses an LLM (Language Model) to explain churn predictions and generate personalized retention emails.
- **Dynamic Visualization**: Displays churn probability with gauge charts and bar charts for easy understanding.

## Dataset

The data used for this project is a simulated customer churn dataset for a bank, available on [Kaggle](https://www.kaggle.com/datasets).

## Installation and Setup

To run the project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/dusanbucalovic/customer-churn-prediction.git
    cd customer-churn-prediction
    ```

2. **Install Dependencies**:
    Make sure you have Python 3.10 or above. Then install the required packages.
    ```bash
    pip install -r requirements.txt
    ```

3. **Add API Keys**:
    - You’ll need an API key for the language model.
    - Set the API key as an environment variable in your local setup or in `.streamlit/secrets.toml` if running with Streamlit Cloud.

4. **Run the App**:
    ```bash
    streamlit run main.py
    ```

## Deployment

The app is deployed on Streamlit Cloud. You can access the live application here: [Customer Churn Prediction App](https://customer-churn-prediction-project.streamlit.app).

## Project Structure
├── main.py # Main app file for Streamlit ├── utils.py # Helper functions for visualizations ├── requirements.txt # Project dependencies ├── churn.csv # Sample dataset (replace if necessary) ├── .streamlit # Streamlit configuration folder │ └── secrets.toml # File for securely storing API keys ├── README.md # Project documentation └── runtime.txt # Specifies the Python version for Streamlit Cloud

## Future Improvements

- Add more models, such as Gradient Boosting and Neural Networks.
- Implement more advanced feature engineering for better accuracy.
- Deploy the model as a standalone API for broader use cases.

## License

This project is open-source under the MIT License.

---

Developed with 💻 and 🔍 by dusanbucalovic.
