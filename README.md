# HerHealth_task

# Endometriosis Diagnosis and Patient Information Analysis

## Overview

This repository contains an analysis of a dataset related to **endometriosis diagnosis** and various **patient characteristics**. The dataset includes key demographic features such as **age**, **marital status**, **income**, and whether the individual has been diagnosed with **endometriosis**. The purpose of this analysis is to explore potential patterns, correlations, and insights that may help healthcare professionals or researchers understand the factors associated with **endometriosis diagnosis**.

The analysis also suggests that in the future, incorporating more granular **National Cancer Institute  (NIC)** data could further enhance the predictive power of models aimed at diagnosing **endometriosis**.

### Dataset Source

The dataset used in this analysis is sourced from **Kaggle**. You can find it [https://www.kaggle.com/](https://www.kaggle.com/datasets/somewhatrandomdata/random-medical).

## Dataset Description

The dataset includes the following columns:

- **age**: Age of the individual.
- **sex**: Gender of the individual (1 = Female, 0 = Male).
- **marital**: Marital status of the individual (1 = Married, 0 = Not Married).
- **income**: Income level of the individual.
- **endometriosis**: Whether the individual has been diagnosed with **endometriosis** (1 = Diagnosed, 0 = Not Diagnosed).

### Data Processing

- **Filtering**: Only **females** (sex == 1) were considered for this analysis since **endometriosis** predominantly affects women.
- **Missing Data**: No missing values were found in the dataset, so no imputation was required.
- **Feature Selection**: Focused on key demographic features: **age**, **marital status**, **income**, and **endometriosis diagnosis**.

## Objective

The main objectives of this analysis are:

1. **Examine the relationship** between **endometriosis diagnosis** and demographic features like **age**, **marital status**, and **income**.
2. **Identify significant patterns** and correlations in the data to better understand the factors contributing to a diagnosis of **endometriosis**.
3. **Generate insights** that could inform healthcare professionals and data scientists working on **endometriosis** and related health issues.

## Exploratory Data Analysis (EDA)

### 1. Summary Statistics

The following summary statistics provide an overview of the dataset:

- **Age**: The dataset includes females aged between **18 and 99** years, with an average age of **58.5 years**.
- **Income**: The average income is approximately **139,520**, with a range from **30,004 to 249,999**.
- **Marital Status**: About **30%** of the females in the dataset are **married**, while the rest are **unmarried**.
- **Endometriosis Diagnosis**: Approximately **30%** of females in the dataset have been diagnosed with **endometriosis**.

### 2. Key Findings

#### Age and Endometriosis Diagnosis
- **Endometriosis diagnosis** is **more prevalent in younger age groups**, particularly in the **18-29** age range.
- This aligns with clinical knowledge that **endometriosis** is most commonly diagnosed in younger women, particularly those within their reproductive years.

#### Marital Status vs Endometriosis Diagnosis
- A surprising pattern was observed: **non-married** females have a **higher diagnosis rate** for **endometriosis** compared to **married** females. This could be explained by several factors:
  - **Age differences**: Younger females who are not married may be more likely to seek diagnosis or treatment for **endometriosis**.
  - **Healthcare access**: Unmarried individuals might have different healthcare-seeking behaviors or access to medical services.

#### Income and Endometriosis Diagnosis
- **Income** did not show any significant correlation with the likelihood of being diagnosed with **endometriosis**. 
- This suggests that factors such as **age** or **marital status** might play a larger role in diagnosis than income level, at least within this dataset.

### 3. Visualizations

The following visualizations were created to better understand the relationships between **endometriosis diagnosis** and other key variables:

1. **Age Distribution**: A **histogram** and **density plot** show the distribution of **age** among those diagnosed with **endometriosis**.
2. **Marital Status vs Endometriosis Diagnosis**: A **countplot** was generated to visualize how **marital status** correlates with the likelihood of a diagnosis.
3. **Income vs Endometriosis Diagnosis**: A **bar plot** was used to compare the average **income** of individuals diagnosed with **endometriosis** to those who are not diagnosed.

### 4. Correlations and Insights

#### **Age**: 
- The highest percentage of **endometriosis diagnoses** is found in the **18-29 age group**. This is consistent with existing clinical data, which suggests that **endometriosis** is most commonly diagnosed during the reproductive years.

#### **Marital Status**:
- **Non-married** females show a higher **endometriosis diagnosis** rate compared to **married** females. This may be explained by:
  - A younger average age among non-married individuals.
  - Potential differences in healthcare access and healthcare-seeking behaviors between married and non-married females.

#### **Income**:
- There is **no significant correlation** between **income** and **endometriosis diagnosis** in this dataset. It appears that **socioeconomic factors** such as income do not strongly influence the likelihood of being diagnosed with **endometriosis**.

## Key Insights

1. **Age**: **Endometriosis** is more prevalent in younger females (18-29 years), confirming the clinical understanding that the condition is most commonly diagnosed during the reproductive years.
   
2. **Marital Status**: The relationship between **marital status** and **endometriosis diagnosis** is complex. **Non-married** females tend to show a higher diagnosis rate. This may reflect differences in **age** and **healthcare seeking behaviors**.
   
3. **Income**: The lack of a correlation between **income** and diagnosis suggests that factors like **age** and **marital status** might be more predictive of **endometriosis diagnosis** in this dataset.

## Future Steps

1. **Age and Marital Status Analysis**:
   - Further analysis could explore how **age** interacts with **marital status** to influence the likelihood of **endometriosis diagnosis**.
   - Investigating **age distributions** across **marital status** categories could clarify any confounding effects.

2. **Health Behavior and Conditions**:
   - Future studies should consider incorporating other health conditions (e.g., **obesity**, **diabetes**, **asthma**) to see how they influence the likelihood of **endometriosis diagnosis**.

3. **Incorporating NIC Data**:
   - In future research, we can integrate **National Cancer Institute  (NIC)** data for more detailed health information, such as medical history, genetic factors, and lifestyle choices. This could lead to the development of more robust **predictive models** for **endometriosis diagnosis**.
   - By leveraging **machine learning** techniques, we could train models to predict the likelihood of **endometriosis** diagnosis based on comprehensive data, helping healthcare professionals make informed decisions.

## Files in this Repository

- **random_medical_data.csv**: Contains the dataset.
- **Herhealth.ipynb**: Jupyter notebook containing the code for data preprocessing, exploratory analysis, and visualizations.
- **README.md**: This file.

## Conclusion

This analysis highlights significant patterns in the **diagnosis of endometriosis**, particularly the high diagnosis rate in younger women. The relationship between **marital status** and **diagnosis** was an unexpected finding and warrants further investigation. No strong correlation was found between **income** and diagnosis, suggesting that **age** and **marital status** are more important factors in this context.

In the future, incorporating **National Cancer Institute  (NIC)** data will provide a more comprehensive dataset, allowing for the development of predictive models that can assist healthcare providers in identifying women at risk for **endometriosis**.

