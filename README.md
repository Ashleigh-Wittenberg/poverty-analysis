Project 4 Proposal: Analyzing Poverty Levels in the U.S.
Completed by: Ashleigh Wittenberg, Lakia White, Tristan Perry, and Owen Pollard


Scope and Purpose:
This project aims to investigate the relationship between various socio-economic factors, including education attainment, regional area, and their impact on poverty levels in the United States. By leveraging data from the U.S. Census Bureau via their API and CSV files, we intend to analyze how these factors contribute to poverty rates over the years from 2012 to 2022, excluding the year 2020 to avoid data distortion due to Covid-19 pandemic.

Data of Interest:
Education Attainment: We will examine the correlation between education levels (e.g., high school diploma, bachelor's degree, advanced degrees) and poverty rates. This will involve categorizing individuals based on their highest level of education achieved and analyzing how it affects their likelihood of living in poverty.

Regional Area: Analyzing poverty rates across different geographic regions (e.g., states, urban vs. rural areas) to identify any disparities in poverty levels based on location. This could involve comparing poverty rates between states or between urban and rural areas.

Research Questions:
How does education attainment influence poverty levels in the U.S.?
Are there significant differences in poverty rates across various regional areas in the U.S.?

Data Sources:
This project utilizes two main sources of data for our analysis:

Census.gov API: We will leverage the U.S. Census Bureau's API to access real-time data on education attainment, marital status, regional demographics, and poverty rates.

U.S. Census Bureau CSV Files: Additionally, we will utilize historical census data in CSV format obtained from the U.S. Census Bureau website. These files will provide detailed socio-economic information, including education attainment, marital status, and poverty rates, spanning the years 2012 to 2022.

Expected Outcome:
By analyzing the interplay between education attainment, regional area, and poverty levels, we aim to gain insights into the socio-economic factors driving poverty in the United States. The findings from this analysis could inform policy decisions aimed at reducing poverty and promoting economic equality across different demographic groups and geographical regions.


![k_3_cluster](https://github.com/Ashleigh-Wittenberg/poverty-analysis/assets/152832328/ae9f3b47-f701-4ee5-85f5-3c51cb33c391)

Clustering with K=3

![k_2_cluster](https://github.com/Ashleigh-Wittenberg/poverty-analysis/assets/152832328/05adb7cc-aafe-4a9c-8d08-2b413a5db802)

Clustering iteration 2 with K=3

![PCA_cluster](https://github.com/Ashleigh-Wittenberg/poverty-analysis/assets/152832328/75816934-39b5-4fcf-ad9e-5134e605bc87)

Clustering iteration 3 with PCA

![best_kmeans_CM](https://github.com/Ashleigh-Wittenberg/poverty-analysis/assets/152832328/355e1bde-3733-45ca-b381-7fa1cfd09110)

Confusion Matrix (Logistic Regression using Kmeans labels)


![best_kmeans_LRM_coefficients](https://github.com/Ashleigh-Wittenberg/poverty-analysis/assets/152832328/eb66691f-8841-4666-bcf3-29885ec6234c)

Feature coefficients for Kmeans LRM


![best_kmeans_C_Report2](https://github.com/Ashleigh-Wittenberg/poverty-analysis/assets/152832328/a69836d8-f9cd-4efa-836a-a42631941544)

Classification Report for Kmeans LRM


![binned_sel_feat_report2](https://github.com/Ashleigh-Wittenberg/poverty-analysis/assets/152832328/67c2840e-f5eb-43f0-b700-f78db57fc956)

Binned Poverty LRM Report (selected features)


![binning_report2](https://github.com/Ashleigh-Wittenberg/poverty-analysis/assets/152832328/96900413-a870-4933-8400-2eade8a4c898)

Binned Poverty LRM (all features)


![NN_1_learn_curve](https://github.com/Ashleigh-Wittenberg/poverty-analysis/assets/152832328/cf956de2-c578-4355-97ad-56bbabbc8e7d)

Iteration 1 Neural Network Learning Curve


![NN_1_PvsA](https://github.com/Ashleigh-Wittenberg/poverty-analysis/assets/152832328/2a9cf38f-61e1-46e6-a468-899c95d21037)

Iteration 1 Neural Network Predicted vs Actual values


![NN_1_PvA_Dist](https://github.com/Ashleigh-Wittenberg/poverty-analysis/assets/152832328/01da969d-f11e-4ff0-9a13-33e2ebcf4f4d)

Iteration 1 Neural Network Predicted vs Actual value distribution


![NN_2_learn_curve](https://github.com/Ashleigh-Wittenberg/poverty-analysis/assets/152832328/4caacb0a-5895-4e28-8eae-07908ef6a677)

Iteration 2 Neural Network Learning Curve


![NN_2_PvsA](https://github.com/Ashleigh-Wittenberg/poverty-analysis/assets/152832328/7af6d429-55d2-4685-962d-35bad7ccba3f)

Iteration 2 Neural Network Predicted vs Actual values


![NN_2_PvA_Dist](https://github.com/Ashleigh-Wittenberg/poverty-analysis/assets/152832328/233999a0-87f4-420f-b7fb-1b9f9f295999)

Iteration 2 Neural Network Predicted vs Actual value distribution




In conclusion, while our models have demonstrated a commendable level of accuracy, it's essential to recognize the nuanced nature of the data at hand. Although there appears to be a correlation between education attainment and poverty rates, it's crucial to acknowledge the multitude of other factors that can influence economic circumstances. Factors such as systemic inequalities, access to resources, and regional disparities can significantly impact poverty levels and may not be fully captured by our models. Therefore, while education attainment can provide valuable insights into socioeconomic outcomes, a comprehensive understanding of poverty requires consideration of a broader range of variables. Moving forward, it's imperative to continue refining our analyses and approaches to better account for the complexity of poverty dynamics and ensure more accurate and meaningful insights.
