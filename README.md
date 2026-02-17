# doctor-rating-analytics

Interactive data analytics project for analyzing German doctor rating data using Python, Pandas, Altair and Streamlit.

---

## Overview

This project explores structured doctor and patient review data to uncover rating patterns across medical specialties, geographic regions and insurance types.

It combines data preparation, relational merging and interactive dashboard-based exploration to identify structural differences in healthcare perception.

The analytical focus lies on aggregation behavior, distribution characteristics and structural clustering patterns.

### Core Analytical Dimensions

- Medical specialties (Fachgruppen & Fachrichtungen)
- Regional variation (Bundesländer & Städte)
- Insurance type (Public vs. Private)
- Individual rating criteria (Typ 1–17)
- City size vs. doctor density
- Doctor profiling via clustering

---

## Analytical Objectives

The project investigates the following research questions:

- Are medical specialties rated equally on average?
- Do certain regions systematically perform better or worse?
- Is there a measurable rating difference between public and private patients?
- Is the number of registered doctors proportional to city population size?
- Which rating criteria perform consistently best or worst?
- Can structural doctor types be identified using clustering techniques?

---

## Technical Implementation

The system is implemented as an interactive Streamlit dashboard within a Jupyter Notebook environment.

### Technologies Used

- Python
- Pandas (data manipulation)
- Altair (interactive visualizations)
- Streamlit (dashboard interface)
- Scikit-Learn (K-Means clustering)
- StandardScaler (feature normalization)

---

## Analytical Methods

- Data cleaning and relational merging
- Aggregation (mean, median, standard deviation)
- Distribution analysis via boxplots
- Regional comparison using heatmaps
- Scatter plot correlation analysis
- K-Means clustering for structural doctor profiling
- Feature scaling prior to clustering

---

## Repository Structure

├── project_streamlit.ipynb # Interactive analysis dashboard
├── project_prep.ipynb # Data preparation & cleaning steps
├── project_files/
│ ├── doc_extended.csv # Doctor master data
│ ├── rev_cleaned.csv # Cleaned review data
│ └── typ.csv # Rating criteria mapping

---

## Key Features

- Dynamic filtering by region, city, specialty and rating range
- Adjustable minimum review threshold per doctor
- Regional heatmaps for rating criteria comparison
- Distribution analysis via boxplots
- Doctor clustering visualization
- Median vs. mean comparison for outlier detection
- Interactive city-size correlation analysis

---

## Academic Context

Developed as part of a university data analytics project focusing on:

- Data preparation and transformation
- Exploratory Data Analysis (EDA)
- Statistical interpretation
- Interactive visualization design
- Applied clustering methods

---

## Project Classification

Data Analytics / Exploratory Data Science  
Focus: Healthcare rating analysis and structural pattern detection
