# Project Summary

---

**Project Title:** Predicting Urban Tree Health

**Objective:**  
- Develop a machine learning model to predict urban tree health with at least 75% accuracy.
- Identify the top 5 factors influencing urban tree health.

**Dataset:**  
- Source: [2015 Street Tree Census Tree Data](https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/uvpi-gqnh/about_data)

**Methodology:**
1. **Data Collection:**
   - Imported the dataset containing 683,788 entries and 45 columns with various features related to tree health and location.

2. **Data Preprocessing:**
   - Handled missing values using mean imputation and forward fill techniques.
   - Dropped any remaining rows with NaN values to ensure data integrity.
   - Encoded categorical variables for compatibility with machine learning algorithms.

3. **Model Development:**
   - Split the data into training and testing sets.
   - Used a Random Forest Classifier to train the model.
   - Evaluated model performance using accuracy score and classification report.

4. **Results:**
   - Achieved a prediction accuracy of over 75%.
   - Identified the top 5 factors influencing tree health: tree diameter, species, location, presence of physical problems, and surrounding environmental conditions.

**Tools and Libraries Used:**
- Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SciPy

**Conclusion:**
This project successfully demonstrated the application of machine learning in urban environmental management. The model's predictions can assist in proactive tree maintenance and urban planning, contributing to healthier urban ecosystems.

---

Thank you for reading about my journey in this exciting project. Feel free to reach out if you'd like to discuss the project in more detail or collaborate on future endeavors!
