# Data-Cleaning-App
# 🧹 Smart Data Cleaning App

An intuitive and modular data cleaning platform built with Python and Streamlit. Whether you're prepping data for analysis or machine learning, this tool helps you clean, encode, and export your datasets in seconds.

## 🚀 Features

- ✅ Upload `.csv` or `.xlsx` files
- ✅ Drop unwanted columns
- ✅ Handle missing values and duplicates
- ✅ Label encode categorical columns
- ✅ Remove outliers with IQR
- ✅ Preview and download cleaned datasets
- ✅ Choose only the steps you need

## 🖼️ Demo

> Add a GIF or video link here once published  
> Example:  
> ![App Demo](https://link-to-your-demo.gif)

## 🛠️ Tech Stack

- [Streamlit](https://streamlit.io/) – for building the interactive UI  
- [Pandas](https://pandas.pydata.org/) – for all data operations  
- [scikit-learn](https://scikit-learn.org/) – LabelEncoder  
- [xlsxwriter](https://pypi.org/project/XlsxWriter/) – Excel file exports  
- Docker & AWS Ready 💻☁️

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/smart-data-cleaning-app.git
cd smart-data-cleaning-app

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py


# Project Structure
smart-data-cleaning-app/
├── app.py                # Streamlit UI
├── requirements.txt
└── cleaner/
    ├── __init__.py
    ├── cleaning.py       # Main cleaning logic
    ├── outliers.py       # IQR-based filtering
    └── report.py         # Cleaning summary generator

