## Star Rating Classification of Yelp Businesses

This is the repository for my DATA 1030 final project using the Yelp business dataset. The [final report](https://github.com/emilynomura1/1030FinalProject/blob/main/report/Final-Report.pdf) is split into six main sections:
1. Introduction
2. Exploratory Data Analysis
3. Methods
4. Results
5. Outlook
6. References

The midterm report is also provided in the [report](https://github.com/emilynomura1/1030FinalProject/tree/main/report) folder. It focuses primarily on exploratory data analysis and data preprocessing while the final report focuses on the machine learning pipeline, evaluation metrics of various ML algorithms, and feature importance.

The main models and predictions used for feature importance have been saved in the [results](https://github.com/emilynomura1/1030FinalProject/tree/main/results) folder. They can be loaded into a Jupyter session using the pickle library. The final model implementing random forest classification is not included in the results folder because it was too large to upload (>1 GB). The model can still be reproduced by running the relevant code in [preprocessing-ml.ipynb](https://github.com/emilynomura1/1030FinalProject/blob/main/src/preprocessing-ml.ipynb).

The Jupyter Notebook used to clean the data can be found in [data-cleaning-final.ipynb](https://github.com/emilynomura1/1030FinalProject/blob/main/src/data-cleaning-final.ipynb). Relevant figures used in the final report and also figures not included have been saved in the [Figures](https://github.com/emilynomura1/1030FinalProject/tree/main/Figures) folder. The final cleaned dataset can be found in the [Data](https://github.com/emilynomura1/1030FinalProject/tree/main/Data) folder. Alternatively, one can download the raw Yelp business dataset from the [Yelp Open dataset website](https://www.yelp.com/dataset). A JSON to CSV converter for this dataset can be downloaded on the [Yelp Dataset Github](https://github.com/Yelp/dataset-examples). The raw data is not provided because a user agreement must be signed by the intended user to download it.

To save time and avoid data rate limit errors in Jupyter Notebook, the cleaned data should be read in rather than the raw data. If it is necessary to read in the raw data and execute the data cleaning steps again, one should specify the data rate limit when opening Jupyter Notebook from Terminal. More specific details relating to this issue can be found [here](https://stackoverflow.com/questions/43288550/iopub-data-rate-exceeded-in-jupyter-notebook-when-viewing-image).

This project uses Python version 3.9 and a number of standard libraries including pandas, matplotlib, numpy, and scikit-learn. The specific packages and package version deatils can be found in [yelp-report.yml](https://github.com/emilynomura1/1030FinalProject/blob/main/src/yelp-report.yml)
