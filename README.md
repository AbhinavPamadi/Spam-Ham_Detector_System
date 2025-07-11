# Spam-Ham_Detector_System

A machine learning project to classify SMS messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing and various classification models.

## Overview

This project uses the [UCI SMS Spam Collection Dataset] to build a text classifier that can distinguish between spam and non-spam messages. The classification pipeline includes:

- Data loading and preprocessing
- Exploratory data analysis
- Feature extraction using TF-IDF
- Model training and evaluation (e.g., Naive Bayes)


## Dataset

- File: `SMSSpamCollection.txt`
- Format: Tab-separated text file
- Columns:
  - `label`: Indicates whether the message is spam or ham
  - `message`: The text of the SMS message

## Dependencies

Make sure you have the following libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/AbhinavPamadi/Spam-Ham_Detector_System.git
cd Spam-Ham_Detector_System
```

2. Open the Jupyter notebook:

```bash
jupyter notebook main.ipynb
```

3. Run all cells to load the data, train the models, and evaluate performance.


