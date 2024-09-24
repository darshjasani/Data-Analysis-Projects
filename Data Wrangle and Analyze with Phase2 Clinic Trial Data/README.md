## Data Wrangling and Analysis: Phase II Clinical Trial Dataset

This project involves the cleaning and exploratory data analysis (EDA) of a Phase II clinical trial dataset. The dataset includes demographic, medical, and trial-specific information about patients involved in the study. The primary objective of this project is to clean the raw data, handle inconsistencies, and perform meaningful analyses that reveal insights into the clinical trial participants and outcomes.

# DISCLAIMER: This Data Isn't "Real"
The Auralin and Novodra are not real insulin products. This clinical trial data was fabricated for 
the sake of this project. When assessing this data, the issues detected (and later cleaned) 
are meant to simulate real-world data quality and tidiness issues.


# Key Features of the Project

1) Data Cleaning:

The raw dataset contained missing values, erroneous data points, and inconsistencies in various fields such as patient demographic data, birthdates, and BMI (Body Mass Index).
This notebook employs different strategies such as:
Removal of duplicated entries.
Standardization of addresses and phone numbers.
Correction of missing or invalid entries in important columns such as weight, height, and birthdates.

2) Exploratory Data Analysis (EDA):

Post cleaning, several key aspects of the dataset were explored, including patient demographics (e.g., age, sex, BMI), geographical distribution, and more.
Insights were gathered on the characteristics of the patient group involved in the trial, including:
Distribution of patients by sex and age group.
BMI categorization and its impact on trial outcomes.
Trends in geographical data related to trial sites and patient residences.

3) Visualization:

The cleaned dataset was visualized to gain insights into the relationships between various factors:
Histograms for age and BMI distribution.
Bar charts representing the distribution of assigned sexes among trial participants.
Scatter plots showing the correlation between BMI and other variables such as weight and height.
Geographical visualization to map out the spread of trial participants across different cities and states.

# Key Insights

1) Demographic Breakdown:
The dataset revealed a near-even distribution of assigned sexes, with a small skew toward male participants.
The average age of participants was concentrated around mid-50s, with a few older and younger outliers.

2) BMI and Health Factors:
Most participants fell within the normal BMI range, with a smaller percentage classified as underweight or overweight.
Height and weight correlations were explored to verify the consistency of BMI calculations.

3) Geographical Trends:
The majority of the participants were clustered in a few key cities, suggesting the trial may have been concentrated in specific regions.

4) Data Cleaning Impact:
Cleaning significantly improved the accuracy of the dataset, especially with respect to BMI values and demographic fields like birthdates and addresses. Removing outliers and correcting invalid data points provided a clearer picture of the overall trends.

5) Visualizations
Histograms to understand the distribution of patient age and BMI.Scatterplots to visualize correlations between height, weight, and BMI.Bar charts for categorical distributions, such as assigned sex.Geographical plots to showcase the geographic spread of participants.

## Insights and Future Work
This project highlighted the importance of data cleaning and visualization when working with medical and trial datasets. For future work:

Additional analysis could focus on the outcomes of the trial, comparing how different demographic groups responded to the treatment. Incorporating external data, such as environmental or socioeconomic factors, might reveal new insights into the trial's effectiveness across different populations.
