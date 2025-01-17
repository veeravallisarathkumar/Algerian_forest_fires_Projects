# Algerian Forest Fire Dataset Analysis

This repository contains an analysis of the **Algerian Forest Fire Dataset**, along with tools and code to preprocess, analyze, and model the data.

The dataset focuses on forest fire incidents in Algeria and includes meteorological, environmental, and fire-related parameters.

---

## Table of Contents

- **Introduction**  
- **Dataset Description**  
- **Features**  
- **Features of the Project**  
- **Prerequisites**  
- **Installation & Setup**  
- **File Structure**  
- **How to Use**  
- **Customization**  
- **License**  

---

## Introduction

- The **Algerian Forest Fire Dataset** provides data for two distinct regions in Algeria: the **Bejaia Region** and the **Sidi Bel-abbes Region**.  
- This project explores the data to gain insights into the factors affecting forest fires.  
- It applies machine learning models to predict fire occurrence and severity based on environmental and meteorological variables.  
- The goal is to develop predictive models that can assist in fire prevention and management strategies.  

---

## Dataset Description

- The dataset contains records from **June 1st to September 30th, 2012**.  
- It includes the following:  
  - **Meteorological data** (e.g., temperature, relative humidity, wind speed).  
  - **Fire Weather Index (FWI) parameters**.  
  - **Region-specific information**.  
  - **Fire occurrence indicators** (classes: `Fire` or `No Fire`).  

---

## Features

- **Region**: The region of Algeria (Bejaia or Sidi Bel-abbes).  
- **Date**: Day, month, and year of the observation.  
- **Temperature (°C)**: Average temperature of the day.  
- **RH (%)**: Relative humidity percentage.  
- **Ws (km/h)**: Wind speed.  
- **Rain (mm)**: Rainfall in millimeters.  
- **FWI System Parameters**: Includes FFMC, DMC, DC, ISI, BUI, and FWI values.  
- **Classes**: Binary class indicating the presence of a fire (`Fire` or `No Fire`).  

---

## Features of the Project

- **Data Cleaning**: Handles missing or corrupted data.  
- **Exploratory Data Analysis (EDA)**: Generates insights about the relationship between environmental factors and fire occurrences.  
- **Visualization**: Provides graphs and charts for a better understanding of patterns and correlations.  
- **Modeling**: Predicts fire occurrence using machine learning models like Logistic Regression, Decision Trees, and Random Forests.  
- **Evaluation**: Compares model performance using metrics like accuracy, precision, recall, and F1-score.  

---

## Prerequisites

To run this project, you need the following:  

- **Python** (3.7 or higher).  
- Libraries:  
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `seaborn`  
  - `scikit-learn`  

---

## Installation & Setup

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/your-username/algerian-forest-fire-analysis.git
   cd algerian-forest-fire-analysis
