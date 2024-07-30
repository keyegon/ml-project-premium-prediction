# Health Insurance Cost Predictor

This project is a Streamlit web application that predicts health insurance costs based on various input factors. The model used for prediction is a machine learning model trained on health insurance data.

## Project Overview

This application was developed by Erick Yegon after completing the Codebasics ML course. The app allows users to input various factors such as age, number of dependents, income, genetical risk, and other categorical data. Based on these inputs, the app predicts the expected health insurance cost.

## Features

- User-friendly web interface built with Streamlit.
- Input fields for various factors affecting health insurance costs.
- Predicts health insurance costs using a pre-trained machine learning model.
- Displays the predicted cost in a user-friendly manner.

## Installation

To run this app locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/health-insurance-cost-predictor.git
    cd health-insurance-cost-predictor
    ```

2. **Create and activate a virtual environment (optional but recommended):**
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app:**
    ```bash
    streamlit run app.py
    ```

## Usage

Open your web browser and navigate to `http://localhost:8501`. You will see the web interface of the Health Insurance Cost Predictor.

- **Age**: Enter the age of the individual.
- **Number of Dependants**: Enter the number of dependants.
- **Income in Lakhs**: Enter the annual income in lakhs.
- **Genetical Risk**: Enter the genetical risk score (0-5).
- **Insurance Plan**: Select the insurance plan (Bronze, Silver, Gold).
- **Employment Status**: Select the employment status.
- **Gender**: Select the gender.
- **Marital Status**: Select the marital status.
- **BMI Category**: Select the BMI category.
- **Smoking Status**: Select the smoking status.
- **Region**: Select the region.
- **Medical History**: Select the medical history.

After entering all the required information, click on the "Predict" button to get the predicted health insurance cost.

## Code Structure

- `app.py`: Main Streamlit app script.
- `prediction_helper.py`: Contains the `predict` function and helper functions for preprocessing and scaling input data.
- `requirements.txt`: List of dependencies required to run the app.
- `artifacts/`: Directory containing pre-trained models and scalers.

## CI/CD

This project includes a GitHub Actions workflow for Continuous Integration (CI). The workflow file is located at `.github/workflows/ci.yml`.

## License

This project is licensed under the MIT License.

## Acknowledgments


This project was developed by Erick Yegon after completing Codebasics ML course: [codebasics.io](https://codebasics.io), all rights reserved.
