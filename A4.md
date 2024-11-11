# A4 Final Project Proposal: Identifying Risk Factors for Asthma Development

## Motivation and Problem Statement

Asthma is a chronic respiratory condition that impacts millions globally, leading to substantial health care costs and a reduced quality of life for those affected. Identifying the factors that contribute to asthma development is crucial for preventive measures, especially among high-risk populations. Inspiration for this project comes from  my asthma experience after developing pet allergy. This analysis aims to examine data related to asthma patients to determine and prioritize the risk factors most associated with asthma onset. From a scientific and human-centered perspective, understanding these risk factors can enhance screening processes and support the development of preventive strategies.

This project will explore correlations between variables like demographics, medical history, and environmental exposure, all available in the chosen dataset. By conducting this analysis, I hope to gain insights into key predictors of asthma, which could inform public health initiatives and individual preventive efforts.

## Data Selected for Analysis

- **Dataset:** [Asthma Disease Dataset on Kaggle](https://www.kaggle.com/datasets/rabieelkharoua/asthma-disease-dataset)
- **Description:** This dataset includes patient demographic data, medical histories, and treatment information for asthma patients. Key fields cover age, gender, family history, environmental exposures, allergy, and other medical conditions, all essential for analyzing factors related to asthma development.
- **License:** [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)
- **Ethical Considerations:** Since this dataset contains health-related information, it is crucial to handle the data responsibly, with respect to privacy and ethical guidelines, ensuring all analyses are conducted within the data usage terms provided by Kaggle.

## Unknowns and Dependencies

The project depends on the quality and completeness of the data. Missing or inconsistent values could lead to bias. Additionally, some risk factors may be underrepresented or absent, affecting the comprehensiveness of the analysis. Access to supplementary data may be necessary if critical variables are lacking, which could add dependencies outside my control. 

## Overview and Research Questions (or Hypotheses)

This project aims to identify and prioritize risk factors associated with asthma development by analyzing patient demographic data, medical histories, and environmental exposures. By understanding these correlations, I hope to provide actionable insights that can aid in developing preventive healthcare measures and screening processes for individuals at risk.

**Research Questions:**
1. What demographic factors (e.g., age, gender, family history) are associated with an increased risk of asthma development?
2. How do environmental exposures (e.g., pollution levels, allergens) correlate with asthma onset?
3. Is there a significant association between pre-existing medical conditions and the likelihood of developing asthma?
4. Can we identify a predictive model to quantify the impact of specific risk factors on asthma development?

**Hypotheses:**
- Individuals with a family history of asthma are more likely to develop asthma.
- Exposure to high levels of pollution is associated with an increased risk of asthma.
- Pre-existing respiratory conditions correlate with a higher likelihood of asthma development.

## Background and Related Work

Asthma has been widely studied in medical literature, with known risk factors including genetic predisposition, environmental exposures, and pre-existing health conditions. Research has shown that air pollution, especially in urban areas, can exacerbate respiratory issues and lead to asthma onset ([WHO, 2020](https://www.who.int/)). Studies also indicate that individuals with a family history of asthma or other respiratory conditions are at a higher risk ([American Lung Association, 2018](https://www.lung.org/)). This project builds on these findings by integrating multiple factors to create a more comprehensive risk profile.

Prior studies have primarily focused on isolated risk factors, but few studies have combined demographic, environmental, and medical data into a single predictive model. My approach draws on this literature, aiming to validate and expand on these findings by applying machine learning techniques to predict asthma onset based on a broader range of variables.

## Methodology

To answer the research questions, I plan to perform a combination of statistical analysis and machine learning modeling on the dataset because data are well classified.

1. **Data Preprocessing:** I plan to clean the dataset by addressing missing values and inconsistencies. I will also standardize or encode variables as needed for analysis.
   
2. **Statistical Analysis:** Using correlation matrices and regression analyses, I will examine the relationships between demographic, environmental, and medical variables with asthma onset.

3. **Modeling Techniques:** I will review logistic regression and random forest models to predict asthma risk. Logistic regression will help determine the strength of individual risk factors, while random forests will allow for the exploration of interactions between multiple variables. I will use cross-validation to validate the models.

4. **Visualization:** Data visualizations, such as bar charts for categorical variables (and heatmaps maybe) for correlations, will help visualize the findings. I will also present model coefficients and feature importances to highlight the most significant predictors.

5. **Evaluation:** Model performance will be evaluated using metrics such as accuracy, precision, recall. Feature importance will be ranked to prioritize risk factors for asthma development.

The combination of statistical and machine learning methods will provide a comprehensive understanding of the data, ensuring solid findings that can inform preventive measures and public awareness in asthma care. 

