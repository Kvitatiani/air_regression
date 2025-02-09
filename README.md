# Air Quality Regression Project🌿

This project focuses on predicting air pollutant levels using sensor data collected over a year in a polluted area of an Italian city. The dataset contains sensor readings and reference values for pollutants like CO, Benzene, and NOx, offering a great opportunity to explore regression techniques.  

---

## 🚀 Key Features & Learnings
- **Data Preprocessing:**  
  - Cleaned and handled missing values in sensor data.  
  - Addressed sensor cross-sensitivities and drift challenges.  

- **Modeling:**  
  - Implemented multiple linear regression.  
  - Added **polynomial features** to capture non-linear relationships.  
  - Applied **Lasso and Ridge regularization** to avoid overfitting.  

- **Results:**  
  - Achieved accurate predictions by fine-tuning models.  
  - The titania and NOx/NO2 sensors were the most reliable predictors for benzene levels.  

---

## 💡 Future Improvements
- Test seasonal and rush hour effects on pollutant levels.  
- Create new features by categorizing time periods (rush vs. regular hours) and seasonal splits.  
- Assess potential multicollinearity introduced by these features.  

## **About the Dataset**

Main link: https://archive.ics.uci.edu/ml/datasets/Air+Quality#

Data Set Information: The dataset contains 9358 instances of hourly averaged responses from an array of 5 metal oxide chemical sensors embedded in an Air Quality Chemical Multisensor Device. The device was located on the field in a significantly polluted area, at road level,within an Italian city. Data were recorded from March 2004 to February 2005 (one year)representing the longest freely available recordings of on field deployed air quality chemical sensor devices responses. Ground Truth hourly averaged concentrations for CO, Non Metanic Hydrocarbons, Benzene, Total Nitrogen Oxides (NOx) and Nitrogen Dioxide (NO2) and were provided by a co-located reference certified analyzer. Evidences of cross-sensitivities as well as both concept and sensor drifts are present as described in De Vito et al., Sens. And Act. B, Vol. 129,2,2008 (citation required) eventually affecting sensors concentration estimation capabilities. Missing values are tagged with -200 value. This dataset can be used exclusively for research purposes. Commercial purposes are fully excluded.

Attribute Information:

* Date (DD/MM/YYYY)
* Time (HH.MM.SS)
* True hourly averaged concentration CO in mg/m^3 (reference analyzer)
* PT08.S1 (tin oxide) hourly averaged sensor response (nominally CO targeted)
* True hourly averaged overall Non Metanic HydroCarbons concentration in microg/m^3 (reference analyzer)
* True hourly averaged Benzene concentration in microg/m^3 (reference analyzer)
* PT08.S2 (titania) hourly averaged sensor response (nominally NMHC targeted)
* True hourly averaged NOx concentration in ppb (reference analyzer)
* PT08.S3 (tungsten oxide) hourly averaged sensor response (nominally NOx targeted)
* True hourly averaged NO2 concentration in microg/m^3 (reference analyzer)
* PT08.S4 (tungsten oxide) hourly averaged sensor response (nominally NO2 targeted)
* PT08.S5 (indium oxide) hourly averaged sensor response (nominally O3 targeted)
* Temperature in Â°C
* Relative Humidity (%)
* AH Absolute Humidity

Target - C6H6(GT) -200 indicates missing values
