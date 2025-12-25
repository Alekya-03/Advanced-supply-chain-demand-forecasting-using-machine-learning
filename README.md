# Advanced supply chain demand forecasting using machine learning

Smart Demand Forecast is a Flask-based web application designed for demand forecasting and inventory management. It allows users to upload their datasets, generate demand forecasts, view dashboards, and download detailed reports in PDF and CSV formats.

## Features
* Upload CSV datasets with product demand and inventory data.
* Validate and preprocess uploaded datasets.
* Generate demand forecasts for selected products.
* View interactive dashboards.
* Download results as CSV.
* Generate PDF reports.
* Uses SARIMAX forecasting.
* Caching for performance.

## Installation and Setup

1. Clone the repository:
```bash
git clone <repository-url>
cd <repository-directory>

2.Create and activate a Python virtual environment (optional but recommended):
bash

python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

3.Install dependencies:
bash

pip install -r requirements.txt

4.(Optional) Set session key:
bash

export SESSION_SECRET="your_secret_key"

5.Run the Flask application:
bash

python app.py

6.Open your browser and navigate to http://localhost:5000 to access the app.
  




