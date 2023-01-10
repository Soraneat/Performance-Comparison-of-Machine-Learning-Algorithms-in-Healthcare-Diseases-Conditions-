# Performance-Comparison-of-Machine-Learning-Algorithms-in-Healthcare-Diseases-Conditions-
ML Classification Algorithms for Investigation in Chronic Diseases (Diabetes, Kidney, Heart, and Asthma Diseases) During the Coronavirus Pandemic Era

## Dataset
The community data source for the Behavioral Risk Factor Surveillance System (BRFSS), a yearly survey conducted by the Centers for Disease Control and Prevention (CDC) using telephone interviews, was used as the dataset for this study. For more than 30 years, BRFSS has been regarded as one of the most reliable sources of self-selected health data surveys. The major objective of BRFSS is to gather standard state-specific information on risk behaviors, chronic diseases and conditions, access to healthcare, and usage of preventive health services in relation to the country's leading deaths and disablers. Every year in the United States, all 50 states, including the District of Columbia, Guam, and Puerto Rico, have data collected through phone surveys.

The investigation included the material source of the 2020 BRFSS, the most recent data at the time. The original dataset overall concluded 279 variables with a number of 401,958 records. In BRFSS, there is a data survey every year that completes more than 400,000 adult interviews. The data collection will end in December of each year. In the COVID era, the content of BRFSS 2020 serves as the source, as COVID-19 started at the beginning of 2020 and the virus's exploitation globally reached the US in March.
 
https://www.cdc.gov/brfss/annual_data/annual_2020.html

## Abstract
The healthcare sector comprises the protection, detection, and treatment of illnesses as well as both physical and mental health. And it has emerged as a crucial global issue as the coronavirus epidemic is currently in its third year. In particular, this problem could have a strong impact on human lives while COVID-19 can be risky for people who have chronic diseases. Therefore, the early detection whether they have healthcare chronic conditions is a key point to decreasing and preventing human life danger. The modern technology of Machine Learning (ML) is a great direction to solve this problem by predicting the diseases conditions based on data. However, there are previous studies in the literature that a lack of research on the situation of main chronic diseases in the coronavirus pandemic era.

This dissertation provides a comparison investigation in four main risky healthcare disease conditions that include diabetes, kidney, heart, and asthma diseases. The research's goal is to determine the best machine learning model and the data train-test method that could provide great performance. The project demonstrates the two types of cross-validation between leave-one-out (LOOCV) and k-fold cross-validation. Following that, the implementation uses six different classification algorithms that include Random Forest (RF), Decision Tree (DT), Logistic Regression (LR), K-Nearest Neighbors (KNN), Gradient Boosting (GB), and Gaussian Naïve Bayes (GNB), which are illustrated by the metrics of accuracy, precision, recall, and F-score.

In addition, the study concludes with an interesting finding due to the large data size issue, the solution of using the clustering technique. The K-mean clustering algorithm is applied as a method to get representative data from cluster groups, which is divided by the data point similarity. Finally, according to the research study results, the Random Forest algorithm in leave-one-out cross-validation represents outstanding performance by reaching over a 0.9600 accuracy rate in each disease prediction study in this project.
