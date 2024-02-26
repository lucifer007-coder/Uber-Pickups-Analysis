# Uber-Pickups-Analysis

This app provides visualization of Uber pickup data in NYC. It utilizes Streamlit to build interactive UI components on a Jupyter notebook.

## Usage
Clone this repository
Make sure you have Streamlit and dependencies installed (see requirements.txt)
Run streamlit run app.py
The app will launch on your browser at http://localhost:8501

## Features
Loads Uber pickup data from AWS S3 and caches it for performance
Shows raw data preview
Bar plot of number of pickups by hour
Slider to filter data by hour
Map showing locations of all pickups for the selected hour

## Data
The data used is from Kaggle containing over 10k rows of Uber pickups in NYC from September 2014.
It contains fields like date/time, latitude, longitude, etc. Date/time is parsed and set as datetime index.

## Deployment
The app is designed to be run locally on Streamlit for interactive development/prototyping.
To deploy online, it needs to be optimized and packaged as a standalone web app. The cacheing and data loading code may also need modifications.

## Credits
Built using Streamlit, Pandas, Numpy and Plotly Express.
Data sourced from Kaggle.
