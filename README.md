# Traffic Congestion Prediction

B.Sc. thesis project (Yıldız Technical University, 2023). Collects travel times from the Google Maps Distance Matrix API into Google Sheets on a schedule, labels congestion with fuzzy-logic membership functions, and trains neural-network regressors (scikit-learn `MLPRegressor`) comparing logistic, tanh and ReLU activations.

## Tech

Python, pandas, NumPy, scikit-learn, scikit-fuzzy, Matplotlib, Google Maps API, Google Sheets API

## Setup

Credentials are read from the environment and are not part of this repository:

- `GOOGLE_MAPS_API_KEY`: a Google Maps API key with the Distance Matrix and Geocoding APIs enabled.
- `GOOGLE_APPLICATION_CREDENTIALS`: path to a Google Cloud service-account JSON key with Sheets access (defaults to `./keys.json`, which is git-ignored).
