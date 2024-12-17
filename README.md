# Predicting Student Success Based on Stress Levels

## Overview  
This research investigates the impact of **stress levels** on academic performance among university students. By leveraging **Deep Neural Networks (DNN)** and **Gradient Boosting** models on a dataset sourced from Kaggle, the study identifies significant correlations between stress and academic outcomes. The final Gradient Boosting model achieved an impressive **accuracy of 93.18%**, highlighting stress as a key determinant.

---

## Objectives  
1. Evaluate the capability of **Deep Neural Networks (DNN)** and **Gradient Boosting** in predicting students' academic success.  
2. Quantify the impact of **stress levels** on academic performance.  
3. Identify key determinants that influence students' academic outcomes.  
4. Provide actionable insights for educators and administrators.

---

## Tools & Technologies Used  
- **Programming Language**: Python  
- **Libraries**: Pandas, Seaborn, Matplotlib, Scikit-learn  
- **Models**: Deep Neural Networks (DNN), Gradient Boosting  
- **Data Source**: Kaggle dataset on student stress factors  

---

## Methodology  
1. **Data Collection**:  
   - **Primary Data**: Interviews with experts, including a psychologist and an AI instructor, to identify key stress factors.  
   - **Secondary Data**: Kaggle dataset containing features like stress levels, sleep quality, and academic performance.  

2. **Data Preprocessing**:  
   - Standard scaling for feature normalization.  
   - Addressed class imbalance using **SMOTE** oversampling.  

3. **Model Development**:  
   - Built and tested **Deep Neural Networks** and **Gradient Boosting** models.  
   - Hyperparameter tuning for Gradient Boosting using Grid Search.  

4. **Evaluation Metrics**:  
   - Accuracy, Precision, Recall, and F1 Score.

---

## Results  
- **Gradient Boosting Model**:  
   - **Accuracy**: 93.18%  
   - **Precision**: 93.21%  
   - **Recall**: 93.18%  
   - **F1 Score**: 93.17%  

- **Key Insights**:  
   - Higher stress levels negatively impact academic performance (correlation: **-0.72**).  
   - Features like **sleep quality** (+0.67), **teacher-student relationships** (+0.67), and **bullying** (-0.67) also significantly influence academic success.

---

## Insights from Expert Interviews  
1. **Common Stressors**:  
   - Academic demands, relationships, and personal life factors.  
2. **Impact of Stress**:  
   - Affects sleep, mood, and classroom engagement.  
3. **Recommendations**:  
   - Utilize **Explainable AI (XAI)** for better model transparency.  
   - Address stress through targeted interventions and mental health support.

---

## Key Contributions  
- Developed a predictive model with **93.18% accuracy** to identify stress as a critical factor affecting academic success.  
- Combined **qualitative insights** (expert interviews) with **quantitative data analysis** (Kaggle dataset).  
- Proposed actionable recommendations for educators to enhance student well-being.

---

## Future Work  
1. Expand dataset by collecting primary data via surveys targeting a broader student population.  
2. Explore additional machine learning techniques like **Random Forests** and **Support Vector Machines**.  
3. Implement **Explainable AI** methods to improve model interpretability.  
4. Conduct longitudinal studies to analyze trends over time.

## Acknowledgments
Special thanks to **Dr. Waleed Sarhan (Psychologist)** and **Dr. Rami Al-Ouran (AI Instructor)** for their valuable insights and guidance.

## Contact  
For inquiries or collaboration, feel free to reach out:  

- **Name**: Mousa Aricat  
- **Email**: [mousa_arikat@outlook.com](mailto:mousa_arikat@outlook.com)  
- **LinkedIn**: [Mousa Aricat](https://linkedin.com/in/mousa-aricat-5847a2241/)  
