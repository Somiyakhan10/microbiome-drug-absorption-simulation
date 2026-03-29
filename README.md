# Microbiome-Drug Absorption Simulation

This project simulates and analyzes drug absorption based on microbiome data using Python and machine learning techniques. It also demonstrates a simple digital twin simulation of intestine-on-chip drug absorption.

## Project Overview
The project performs the following steps:

1. **Data Upload and Cleaning**  
   - Upload CSV dataset interactively (Google Colab)  
   - Keep numeric columns and fill missing values  

2. **Drug Absorption Modeling**  
   - Create a drug absorption score using microbiome features  
   - Add biological noise for realistic simulation  
   - Convert absorption score to a binary classification (High vs Low absorption)

3. **Machine Learning**  
   - Train a Random Forest classifier to predict absorption class  
   - Evaluate model performance using accuracy and classification report  
   - Identify feature importance (which microbiome features most influence drug absorption)

4. **Digital Twin Simulation**  
   - Simulate drug absorption over time using exponential absorption curves  
   - Visualize high vs low absorption scenarios  

