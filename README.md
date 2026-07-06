# Project Overview

Insurance companies cover expenses the policyholder incurs from damages to health or property policies commonly offered: medical bills, house, motor vehicle, and fire insurance, and financial losses such as a loss of income against a fee or premium paid by the client. Traditional approaches to premium calculation require a lot of time-consuming human labor and are getting more complicated daily to capture the increasingly complex interactions in the data. Insurance firms should normally collect a higher premium than the amount given to the insured individual if that person files a valid claim to generate a profit. Since profitability is the fundamental factor that helps the insurance firm survive, they need a mechanism for reliably forecasting healthcare expenses.



Hence, our goal is to build a machine learning model that helps establish the rates by predicting the charges or payouts done by the health insurance firm to maintain profitability.



In this project, we will primarily focus on building an XGBoost Regressor to determine healthcare expenses based on features such as age, BMI, smoking, etc. We will also learn about categorical correlation, build a linear regression model as a baseline and compare it with the results of the XGBoost regressor. We will eventually learn how to communicate technical results to stakeholders who are not technical.



## 📊 Dataset

The dataset is excluded from this repository via `.gitignore` for data privacy and repository hygiene. To run the pipeline, please place your `insurance.csv` file inside a `data/` folder in the root directory.



# Installation

The Python 3.12 version is supported for the execution of this project.



Running the codes locally: Python 3.12 with **uv** package manager.



This project utilizes `uv` for blazing-fast virtual environment and dependency management.



Create a virtual environment:

`uv venv`



This command creates a new virtual environment named `.venv` in the current directory.



Activate the virtual environment:



For macOS and Linux (Terminal / WSL):

`source .venv/bin/activate`



For Windows (Command Prompt):

`.venv\\Scripts\\activate`



Install project requirements:

With the environment active, install the dependencies (cleanly extracted via pigar) using the following command:

`uv pip install -r requirements.txt`



# Execution Instructions

To run the entire modular ML pipeline from data ingestion to XGBoost Bayesian optimization, execute the production engine:



`uv run python engine.py`
