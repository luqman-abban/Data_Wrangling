# SpaceX Falcon 9 Landing Prediction – Data Collection with API

## Overview

This project is part of a data science capstone focused on predicting whether the **SpaceX Falcon 9 first stage** will successfully land after launch.

The notebook demonstrates how to collect and prepare launch data using the **SpaceX REST API**. The collected data can later be used for exploratory analysis, visualization, and machine learning models to predict landing outcomes.

Successful booster recovery significantly reduces launch costs, making landing prediction an important business and engineering problem.

---

## Project Objectives

* Access and retrieve launch data from the SpaceX API
* Perform data wrangling and preprocessing
* Extract useful launch features
* Convert raw JSON data into structured tabular format
* Prepare the dataset for future analysis and machine learning tasks

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Requests
* REST API
* Data Wrangling Techniques

---

## Dataset Source

The data used in this project is collected from the official SpaceX API.

API Endpoint:

```text
https://api.spacexdata.com/v4/launches/past
```

---

## Project Workflow

### 1. Data Collection

* Connect to the SpaceX API
* Retrieve launch records
* Parse JSON responses

### 2. Data Wrangling

* Handle missing values
* Select relevant launch features
* Transform nested JSON structures

### 3. Feature Extraction

Key fields extracted include:

* Flight number
* Launch date
* Booster version
* Payload mass
* Orbit type
* Launch site
* Landing outcome
* Reused booster information

### 4. Data Preparation

* Convert data into Pandas DataFrame
* Clean and standardize columns
* Prepare dataset for analysis/modeling

---

## File Structure

```text
.
├── jupyter_labs_spacex_data_collection_api_v2.ipynb
└── README.md
```

---

## How to Run

### Clone the Repository

```bash
git clone <your-repository-url>
cd <repository-folder>
```

### Install Required Libraries

```bash
pip install pandas numpy requests jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook file:

```text
jupyter_labs_spacex_data_collection_api_v2.ipynb
```

---

## Example Use Cases

This project can be used for:

* Data science portfolio projects
* API data collection practice
* Machine learning preprocessing workflows
* SpaceX launch analytics
* Predictive modeling projects

---

## Future Improvements

* Add exploratory data analysis (EDA)
* Build classification models for landing prediction
* Deploy an interactive dashboard
* Automate live API updates
* Integrate visualization tools such as Plotly or Power BI

---

## Learning Outcomes

By completing this project, you will learn:

* Working with REST APIs in Python
* JSON data extraction and transformation
* Data cleaning and preprocessing
* Feature engineering fundamentals
* Preparing datasets for machine learning

---

## Author Reference

[Nayef Abou Tayoun](https://www.linkedin.com/in/nayefaboutayoun/) is a Data Scientist at IBM and is pursuing a Master of Management in Artificial Intelligence degree at Queen's University.

---

## Acknowledgements

This notebook is based on a data science capstone lab focused on SpaceX launch analysis and predictive modeling.

Special thanks to:

* SpaceX API
* IBM Data Science learning resources
* Open-source Python community

---

## License

This project is for educational and learning purposes.
