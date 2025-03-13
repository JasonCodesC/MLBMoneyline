# Moneyline MLB Predictor

## Note
If you are an employer and wish to see the files please contact me at majorosjason@gmail.com  
Thanks!

## Overview
This project is a XGBoost classifier to predict moneyline MLB baseball games. All of the data was scraped from various websites and went through rigorous pre-processesing. The model achieved the following statistics:

Accuracy: 0.9340885684860968

              precision    recall  f1-score   support

           0       0.96      0.91      0.93       484
           1       0.91      0.96      0.94       487

    accuracy                           0.93       971


## Installation

1. Get the repository:
  ```sh
  Contact me!
  ```


2. Navigate to the repository folder:
  ```sh
  cd <your-repo-path>
  ```


3. Install the required dependencies:
  ```sh
  pip install -r requirements.txt
  ```


4. Run Prediction_Data.py:
  ```sh  
  i) Fill in '#Todos' with whatever desired
  ii) python3 Prediction_Data.py
  ```


5. Run model.py
  ```sh  
  python3 model.py
  ```

## Project Structure
```
/project-root
│── /data                  # Folder for data 
|-- CurrentRecords.py      # Templete for getting data
|-- Prediction_Data.ipynb  # Scrapes for new prediction data
|-- Scraper.ipynb          # Scrapes for traing data
|-- Preprocessesing.ipynb  # Wrangles Data to get it ready for Model.py
│── model.py               # Machine learning model implementation
│── requirements.txt       # Project dependencies
│── README.md              # Documentation
```

## Authors
- Jason Majoros

