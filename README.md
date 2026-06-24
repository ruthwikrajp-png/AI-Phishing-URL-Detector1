# AI-Powered Phishing URL Detection System

## Overview

The AI-Powered Phishing URL Detection System is a machine learning project developed to identify whether a website URL is legitimate or potentially malicious. The system analyzes URL characteristics and predicts if the URL belongs to a phishing website.

## Features

* URL feature extraction and analysis
* Machine Learning-based classification
* Detection of phishing and legitimate websites
* Fast and simple prediction process
* Easy-to-use Python implementation

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Machine Learning
* Git & GitHub

## Project Structure

```
Phishing-Detector/
│
├── features.py
├── train.py
├── predict.py
├── urls.csv
└── README.md
```

## How It Works

1. Load a dataset containing phishing and legitimate URLs.
2. Extract relevant features from each URL.
3. Train a Random Forest Machine Learning model.
4. Predict whether a new URL is safe or phishing.

## Installation

1. Clone the repository:

```
git clone https://github.com/ruthwikrajp-png/AI-Phishing-URL-Detector.git
```

2. Install dependencies:

```
pip install pandas scikit-learn
```

3. Run the training script:

```
python train.py
```

4. Run the prediction script:

```
python predict.py
```

## Sample Output

```
Enter URL: https://google.com
Prediction: Safe Website
```

## Future Enhancements

* Flask-based web interface
* Browser extension integration
* Real-time URL scanning
* Advanced feature engineering
* Enhanced model accuracy

## Author

Ruthwik Raj
B.Tech CSE
Cybersecurity, Blockchain & IoT Specialization
