# URL Phishing Detection Using Logistic Regression & Weight & Biases

This repository contains a project that aims to detect phishing websites using a logistic regression model. The model is trained to classify URLs as either legitimate or phishing based on various features. The performance and accuracy of the model are tracked using Weights & Biases.

## Project Overview

Phishing is a fraudulent attempt to obtain sensitive information by disguising oneself as a trustworthy entity. This project employs a logistic regression algorithm to analyze features of URLs and determine their legitimacy. 

The model's performance is monitored and visualized using Weights & Biases, a platform for tracking machine learning experiments.

## Dataset

The dataset used for training the model consists of labeled URLs, with features extracted from the URLs that help in distinguishing phishing sites from legitimate ones.

## Features

- **URL Length:** Measures the length of the URL.
- **Presence of IP Address:** Checks if the URL contains an IP address.
- **Hyphen Count:** Counts the number of hyphens in the URL.
- **Subdomain Level:** Analyzes the number of subdomains.
- **Suspicious Keywords:** Detects the presence of suspicious keywords like "login", "secure", "update", etc.

## Model

The project uses a logistic regression model, a simple yet effective statistical method for binary classification tasks. The model is trained on a dataset with labeled URLs and corresponding feature vectors.

## Performance Tracking with Weights & Biases

Weights & Biases is used to log the model's training and evaluation metrics, including accuracy, precision, recall, and F1-score. This helps in understanding the model's performance and making necessary adjustments to improve it.

## How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/url-phishing-detection.git
   cd url-phishing-detection
Install the required packages:

Ensure you have Python installed, then run:

bash
Always show details

Copy code
pip install -r requirements.txt
Run the Jupyter Notebook:

You can explore the model and its performance by running the provided Jupyter Notebook.

Colab Link:

The project is also available on Google Colab, which can be accessed here.

Contributing
Contributions to improve the model or add new features are welcome. Please fork the repository and submit a pull request with your changes.

License
This project is licensed under the MIT License. See the LICENSE file for more details.
