# AICTE | IBM SkillsBuild Data Analytics with AI Internship Project
## Title: Precision Agri-Analytics: AI-Driven Soil Health & Crop Recommendation System

### 1. Project Overview
This project leverages Machine Learning to predict the most suitable crop based on chemical soil parameters and meteorological factors. The objective is to optimize agricultural productivity, reduce input waste, and prevent soil degradation.

### 2. Dataset Information
* **Source:** Kaggle Crop Recommendation Dataset
* **Records:** 2,200 observations
* **Features:**
  * Nitrogen (N), Phosphorus (P), Potassium (K) ratio in soil
  * Environmental temperature (°C), Relative Humidity (%)
  * Soil pH level
  * Rainfall (mm)
  * Target: 22 distinct crops (Rice, Maize, Chickpea, Cotton, Coffee, etc.)

### 3. Methodology & Algorithms
* **Exploratory Data Analysis (EDA):** Correlation heatmaps, nutrient frequency distributions, and feature importance analysis.
* **Models Trained:** Decision Tree Classifier and Random Forest Classifier.
* **Best Performer:** Random Forest Classifier achieving >99% predictive accuracy.

### 4. Setup & Execution
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
