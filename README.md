# Stroke Prediction

## Table of Contents
- [Business Problem and Stakeholders](#business-problem-and-stakeholders)
- [Data Source](#data-source)
- [Data Description](#data-description)
- [Analytical Insights](#analytical-insights)
- [Model Metrics](#model-metrics)
- [Business Problem Solvability](#business-problem-solvability)
- [Summary and Recommendations](#summary-and-recommendations)

## Business Problem and Stakeholders

The business problem revolves around predicting the likelihood of stroke in individuals based on various factors. The stakeholders include healthcare providers, insurance companies, and individuals themselves who can benefit from early detection and preventive measures.

## Data Source

The dataset used for this project was obtained from Kaggle. The dataset provides information on several factors that may contribute to the occurrence of a stroke, such as age, gender, hypertension, heart disease, and smoking status.

## Data Description

The dataset contains the following features:

- `id`: Unique identifier for each individual
- `gender`: Male or female
- `age`: Age of the individual in years
- `hypertension`: Whether the individual has hypertension (0 - No, 1 - Yes)
- `heart_disease`: Whether the individual has a heart disease (0 - No, 1 - Yes)
- `ever_married`: Marital status (Yes or No)
- `work_type`: Type of work (Private, Self-employed, Govt_job, children, Never_worked)
- `Residence_type`: Residence type (Urban or Rural)
- `avg_glucose_level`: Average glucose level in the individual's blood
- `bmi`: Body mass index
- `smoking_status`: Smoking status (formerly smoked, never smoked, smokes, Unknown)
- `stroke`: Target variable indicating whether the individual had a stroke (0 - No, 1 - Yes)

## Analytical Insights

### Insight 1: Age Distribution of Individuals with Stroke

![Age Distribution](images/age_distribution.png)

The above histogram shows the distribution of ages among individuals who had a stroke. It is evident that the occurrence of strokes increases with age. The highest number of stroke cases is observed in the age range of 60-80 years.

### Insight 2: Relationship between Hypertension and Stroke

![Hypertension vs. Stroke](images/hypertension_stroke.png)

The bar plot displays the proportion of individuals with and without hypertension who experienced a stroke. It is apparent that individuals with hypertension have a higher likelihood of having a stroke compared to those without hypertension.

## Model Metrics

The best model achieved an accuracy of 85% on the test set. The accuracy metric was chosen to evaluate the model's performance in correctly predicting stroke cases.

## Business Problem Solvability

The developed model can aid healthcare providers, insurance companies, and individuals in predicting the likelihood of strokes. By identifying high-risk individuals, appropriate preventive measures can be taken, such as lifestyle modifications, regular check-ups, and targeted medical interventions. Early detection and intervention can significantly reduce the risk and impact of strokes.

## Summary and Recommendations

Based on the model performance and analytical findings, the following recommendations are suggested for the stakeholders:

1. **Healthcare Providers**: Implement regular health screenings, particularly for individuals above the age of 60, to identify those at high risk of strokes. Provide education and resources to promote healthy lifestyles, focusing on managing hypertension and maintaining a healthy BMI.

2. **Insurance Companies**: Develop personalized risk assessment models based on individual characteristics to determine appropriate insurance coverage and premium rates. Offer incentives for policyholders to adopt healthy behaviors and participate in preventive health programs.

> It is important to note that the recommendations provided are general suggestions and should be further tailored to the specific context and requirements of the stakeholders.

