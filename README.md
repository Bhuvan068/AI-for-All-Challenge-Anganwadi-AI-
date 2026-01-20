# Anganwadi AI Dashboard & Infant Mortality Risk Analysis (India)

An AI-driven data analytics and visualization project that analyzes Infant Mortality Rate (IMR) trends across India and maps infrastructure-based child health risk for Telangana Anganwadi Centers using open government datasets.

Project Overview

Anganwadi Centers (AWCs) play a crucial role in child nutrition, maternal care, and early education in India.
This project combines historical IMR data, child health indicators, and Anganwadi infrastructure data to:

Analyze long-term Infant Mortality Rate (IMR) trends

Compare India-level and state-level IMR patterns

Build a Machine Learning model to understand key child health factors

Generate a geospatial risk map of Telangana Anganwadi Centers

Datasets Used
1️⃣ Infant Mortality Rate (IMR) Data

State-wise IMR (1971–2012)

Gender-based IMR trends

Rural vs Urban IMR trends
Source: Open Government Data Platform (India) & Kaggle

2️⃣ Child Health Dataset

Birth weight

Gestation period

Maternal age

Smoking status
File: babies.csv

3️⃣ Anganwadi Infrastructure Data (Telangana)

Water facility

Electricity availability

Toilets

Teacher count

Enrollment

Geographic coordinates
Source: OpenCity – Telangana Anganwadi Dataset (KML → GeoDataFrame)

🛠️ Technologies & Tools

Python

Google Colab

Pandas & NumPy – Data cleaning & analysis

Matplotlib – Trend visualization

Scikit-learn – Machine Learning (Random Forest)

GeoPandas – Geospatial analysis

KML / GIS data – Telangana Anganwadi mapping

📊 Analysis Performed
✔ IMR Trend Analysis

India-level IMR decline over decades

State-wise comparison

Rural vs Urban IMR gap analysis

✔ Machine Learning Model

Model: Random Forest Classifier

Target: Low Birth Weight risk

Key contributing factors identified:

Gestation period

Maternal weight

Maternal age

Smoking status

✔ Telangana Anganwadi Risk Mapping

Converted infrastructure indicators (YES/NO) to numerical scores

Created an Infrastructure Risk Index

Generated a district-level geospatial risk map

Identified vulnerable Anganwadi centers based on:

Poor infrastructure

Lack of basic facilities

Sample Output

IMR trend plots (India & states)

Feature importance from ML model

Telangana Anganwadi Child Health Risk Heatmap
