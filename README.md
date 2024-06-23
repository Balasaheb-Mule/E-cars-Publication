
# Research Publication Details
International Conference on Transportation and Development 2023, held in Austin, Texas, June 14–17, 2023.
## Research Topic

Identification of Factors Influencing the Adoption and Use of Electric Cars on Indian Roads Based on Public Perception

## Introduction
India’s electric vehicle (EV) market penetration is relatively low compared to its counterparts. An online questionaries survey was done by adopting the unified theory of acceptance and use of technology (UTAUT) model, which included socio-demographic traits and public perception. Cluster analysis was done using hierarchical cluster analysis (HCA) with multiple correspondence analysis (MCA) on socio-demographic data, and factor analysis was conducted for perception-related variables that affect e-cars’ adoption. Kaiser-Meyer Olkin (KMO) measure of sample adequacy test was done. From the relation between socio-demographic and other influencing factors, the economy was a dominant factor for the elder age and middle to the low-income groups. Battery concerns were prevalent for the young-age, low-income group, while performance features with infrastructure facilities were essential for the high-income group. Moreover, public paid interest on the availability of facilities such as battery swap technology, charging facilities, or incentives which may boost the demand for e-cars.
## About Dataset
### Data Collection
Past studies have developed several models and theories with the objective of elucidating public attitudes toward the adoption of new technology as well as the variables that can affect this behaviours.  The most notable amongst transport literature (particularly relating to autonomy) is The Unified Theory of Acceptance and Use of Technology Model – UTUAT. This study utilized the UTAUT model to structure the online survey questionnaire by including the aspects contributing to the adoption of new technologies or new vehicle type such as Electric car. 
Data used in this study was collected through a questionnaire that was prepared using a wide spectrum of questions to collect the maximum possible relevant information from the respondents. It was circulated among people of different backgrounds to create a diverse sample size. The questionnaire consisted a total of 27 questions, including socio-demographic data (age, gender, occupation, annual income, hometown, number of members in the family), number of family members driving personal vehicle(s), driving frequency, driving experience, regular trip area, distance covered as a commuter and respondents’ perception on E-car

## Methodology

![Screenshot 2024-06-24 002537](https://github.com/Balasaheb-Mule/E-cars-Publication/assets/138377175/349fc419-049d-402f-9b20-9a90844acfe5)

### 1. Multiple Correspondence Analysis 
Multiple correspondence analysis is a method for examining the relationship between two or more categorical variables. In this study, MCA was carried out to convert categorical data into continuous data for hierarchical clustering. The number of dimensions to be employed is often decided based on the analysis being done, however two-dimensional comparison is seen to be sufficient for simple visualization 


### 2. Hierarchical Cluster Analysis
In order to get a better understanding of the collected data and extract useful conclusions, hierarchical cluster analysis was conducted on the data obtained from MCA. Ward’s method and square Euclidean distance were used to check the similarity and measure the distance between the clusters. The user responses were clustered into groups sharing similar characteristics based on their socio-demographics. The optimal numbers of clusters were determined using the silhouette score plot (the degree to which each point in a cluster is closer to points in neighbouring clusters) and Dendrogram.

![Screenshot 2024-06-24 003730](https://github.com/Balasaheb-Mule/E-cars-Publication/assets/138377175/a4e9fc19-40b2-4e9e-9658-aefe9e27147f)

### Factor Analysis
Factor Analysis
Factor Analysis (FA) was performed on the remaining data set to reduce the number of involved variables into limited factors that can be meaningfully analyzed. Each option in the multiple-choice questions were divided into individual questions in the dataset for easier interpretability. 
Kaiser-Meter-Olkin (KMO) test is conducted to check the factorability of the dataset. The KMO test score was found to be 0.535 which are considerably above the acceptable value of 0.5 (Field, 2017). The number of factors to be formed were determined using the Kaiser criterion, wherein eigenvalues were used to determine the percentage of variance explained by the factors. For the given dataset, there were five factors with eigenvalues more than 1. Factor Analysis was carried out using the ‘factor analyzer’ package in Python 3.10. The variables were then divided into “five” factors depending on the maximum factor loading. Based on the similarity of the variables within a factor, each factor was assigned a name for proper data interpretation. Approximately 55% cumulative variance was explained by these five factors.
In order to find relations between socio-demographic and perception data, each factor was assigned a score depending on the variables explained by that factor. For example, if a respondent selected ‘yes’ for 2 out of 4 questions (variables) within a factor, that factor was assigned a score of 2/4, i.e., 0.5. The average of these scores was calculated for each cluster and the maximum score was given to the respective cluster.

## Model Evaluation Matrix
The performance of the trained regression model of headway prediction was evaluated using various metrics, including R-squared (R2) score, adjusted R-squared score, mean squared error (MSE), root mean squared error (RMSE), and mean absolute error (MAE), mean absolute percentage error (MAPE). MAPE provides insights into the percentage deviation between predicted and actual values, offering a measure of the model's accuracy in predicting bus bunching instances. Additionally, the model's performance was assessed on the entire dataset to evaluate its generalization ability.
## Analysis & Results
This is the first study where public perception is observed exclusively on electric car as a private transport mode. In the research field of electric car, the study made a first attempt to utilize “The Unified Theory of Acceptance and Use of Technology Model – UTUAT” to design the questionnaire survey. This study establishes the link between public socio-demography and their perception towards adopting electric cars with attention to personal usage in urban areas. The economy was found to be the dominant factor for the elder age and middle to the low-income group. Battery concerns were dominant for the young age and low-income group while performance features with infrastructure facilities were dominant for the high-income group. Moreover, the public shows interest in the availability of facilities such as battery swap technology, charging facilities, or incentives. Hence, improvement of these facilities would boost the demand for E-cars. Several interesting findings were portrayed from the present work, which will be advantageous for vehicle manufacturers and policymakers to make new generation E-cars and different policies more attractive to Indian commuters. The study will help policymakers and traffic engineers to select the most appropriate infrastructure for increasing Electric car adoption and use. It will help think tank bodies and the government to prioritize investment in incentives and infrastructural growth for Electric cars based on public perception.


## Detailed Thesis Report
The comprehensive published research paper can be accessed via the online library of  American Society of Civil Engineers (ASCE) using following link for detailed clarification :
https://ascelibrary.org/doi/abs/10.1061/9780784484883.023
