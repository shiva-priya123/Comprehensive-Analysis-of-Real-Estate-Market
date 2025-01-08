
# Comprehensive Analysis of Real Estate Market

## Executive Summary
The “Comprehensive Analysis of Real Estate Market” project examines factors influencing residential property prices, focusing on the impact of COVID-19. Utilizing the CAMA dataset and CRISP-DM methodology, the project built linear regression models, achieving an R-squared of 0.6539. Key findings highlight the influence of property characteristics like bedrooms, bathrooms, and gross building area. The pandemic increased demand for larger homes, driving up prices and sales volume. AWS tools (S3, Athena, Glue, and SageMaker) supported data processing and modeling, offering actionable insights for real estate stakeholders.

---

## Abstract
This project aims to understand residential property price fluctuations, emphasizing COVID-19's effects. Using the CAMA dataset and CRISP-DM methodology, predictors such as bedrooms, bathrooms, and property condition were analyzed. The study achieved a strong predictive model with an R-squared of 0.6539. It revealed that the pandemic shifted buyer preferences toward larger homes and suburban living. AWS tools streamlined data handling, ensuring efficient analysis and deployment. The results provide valuable insights for developers, investors, and policymakers.

---

## Methodology

### CRISP-DM Framework
1. **Business Understanding**:
   - Identify factors influencing property prices.
   - Examine changes in trends pre-, during, and post-COVID.
   - Assess how features like bedrooms, bathrooms, and gross building area impact prices.

2. **Data Understanding**:
   - Analyze the CAMA dataset for property characteristics and market trends.

3. **Data Preparation**:
   - Use AWS Glue for data cleaning and schema preparation.

4. **Modeling**:
   - Build and evaluate linear regression models in AWS SageMaker.

5. **Evaluation**:
   - Analyze model performance (R-squared: 0.6539, MSE: 212,482,373,114).

6. **Deployment**:
   - Deploy models via AWS EC2 and visualize results.

---

## Key Findings

1. **COVID-19 Impact**:
   - Price and sales volume increased during and after COVID-19.
   - Shifts in preferences for larger homes and suburban properties.

2. **Model Insights**:
   - Predictors like bedrooms, bathrooms, property condition, and gross building area significantly affect prices.

3. **Trends**:
   - Segmented analysis of pre-COVID, during COVID, and post-COVID periods revealed dynamic shifts in market demands.

---

## Data Engineering Pipeline

1. **Data Ingestion**:
   - Data sourced and stored in Amazon S3.
   
2. **Data Storage**:
   - Querying through Amazon Athena.

3. **Data Processing**:
   - Cleaning and transforming via AWS Glue.

4. **Model Development**:
   - Machine learning with AWS SageMaker.

5. **Visualization**:
   - Insights presented through visualized trends and metrics.

---

## Results

### Model Performance:
- Independent Variables: `bathrm`, `bedrm`, `grade`, `heat`, `cndtn`, `gba`
- Dependent Variable: `price`
- **R-squared**: 0.6539
- **Coefficients**: `[45474.65, -72781.65, 221173.80, 857.97, 257221.10, 434.47]`

---

## Discussion

- **Segmented Periods**:
  - Pre-COVID: January 2019 – February 2020.
  - During COVID: March 2020 – July 2021.
  - Post-COVID: August 2021 – December 2022.

- **Key Observations**:
  - Increased demand for larger homes.
  - Suburban and better-conditioned properties saw higher price gains.

---

## Conclusion
The project highlights how COVID-19 reshaped the real estate market. Key property features and changing buyer preferences were identified as major drivers. AWS tools enabled efficient processing and deployment of machine learning models. These findings empower stakeholders to adapt strategies in a shifting market.

---

## Contributions & References

1. Dabreo, S., et al. (2021). Real estate price prediction. *IJERT, 10*(4). [Link](https://www.ijert.org/research/real-estate-price-prediction-IJERTV10IS040322.pdf)
2. Babu, A., & Chandran, A. S. (2019). Real estate value prediction using ML. *IJCSMA, 7*(3).
3. Géron, A. (2019). *Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow* (2nd ed.). O’Reilly Media.
4. Duca, J. V., & Murphy, A. (2021). Housing price surge during COVID-19. *Federal Reserve Bank of Dallas*.
5. Schwartz, A. E., & Wachter, S. (2022). COVID-19’s impacts on housing markets. *Journal of Housing Economics*.
