<h1 align="center"> Predict Donor Behavior </h1>
<h2 align="center"> Deep Learning </h2>

<div align="center">
	<img src="conversion.png">
</div>

## Project Collaborators 
- Caleb Cuterer
- Shannon Hoffman
- Krishna Pandari
- Jim Pieper  
- Walgama Jayasekara

## Introduction.
The purpose of this project is to analyze and predict donor behavior using machine learning techniques, 
specifically deep learning. By understanding patterns in donor activity, we aim to help nonprofit 
organizations optimize their fundraising strategies and improve donor engagement. The focus will 
be on identifying key factors that influence donor retention, donation frequency, and donation amounts.

## Data and Field of Interest.
- Field: Nonprofit and Charity Organizations – higher education
- Data: The project will utilize a dataset containing donor information, donation history, demographic data, and engagement metrics. The data may include variables such as donation amounts, donation frequency, donor age, location, and communication history.
- Potential Data Sources:
- Kaggle datasets related to donor behavior and charity donations
- Publicly available datasets from nonprofit organizations or research institutions
- Data provided by a partnering nonprofit organization

## Research Questions.
The project will focus on the following key questions:

- What are the main factors that influence donor retention?
- Can we predict which donors are likely to make repeated donations?
- How can we segment donors based on their behavior and preferences?
- What patterns exist in donation amounts over time?
- How can we identify potential major donors from the existing donor base?

## Methodology.
- Data Preprocessing: Clean the dataset by handling missing values, encoding categorical variables, and normalizing numerical features.
- Exploratory Data Analysis (EDA): Perform EDA to identify trends, correlations, and outliers in the data. Visualizations will be used to illustrate key findings.
- Model Development: Implement a deep learning model using TensorFlow/Keras to predict donor behavior. The model may include:
  - Input Layer: All relevant features
  - Hidden Layers: Multiple layers with ReLU activation functions
  - Output Layer: A sigmoid or softmax layer for binary/multiclass classification
- Model Evaluation: Evaluate the model using accuracy, precision, recall, F1 score, and AUC-ROC. Cross-validation and hyperparameter tuning will be conducted to optimize performance.
- Donor Segmentation: Use clustering techniques (e.g., K-means) to segment donors based on their behavior and model predictions.

## Expected Outcomes.
- A predictive model that identifies donors likely to make repeat donations.
- Insights into key factors influencing donor retention and donation amounts.
- Segmentation of donors into different categories based on behavior, which can be used for targeted marketing and engagement strategies.
- Recommendations for nonprofit organizations on how to improve donor retention and increase donations.

## Potential Challenges.
- Availability of high-quality, relevant data.
- Complexity in model training due to imbalanced classes (e.g., more one-time donors than repeat donors).
- Interpreting deep learning models for actionable insights.

## Summary
- Key Insights and Next Steps.
  - Donor Engagement: The data highlights that involvement in campus activities, such as Student Organizations, Arts, Fraternal Organizations, and Athletics, influences the likelihood of alumni giving. Age also emerged as an important factor in donor behavior.
  - Targeted Campaigns: By focusing on these key donor attributes, the institution can tailor campaigns to specific donor groups, leading to more sustained and impactful support.

## Strategies to consider.
- Target Alumni :  Aged 40-60 who participated in campus activities for a focused engagement campaign
- Target Mid-Career Alumni: The data suggests that donors aged 40-60 are the most engaged group. This cohort is likely at a point in their careers where they have the financial means to contribute, making them an ideal group for targeted fundraising campaigns.
- Leverage Student and Cultural Groups: Since Student/Fraternal Organizations and Arts have high participation rates, marketing efforts for donations should emphasize the legacy of these groups and how donations can help support them for future students.
- Athletics Appeal: Alumni who participated in athletics may be more likely to contribute to sports-focused fundraising efforts, such as facility upgrades or team sponsorships.
- Gratitude from Scholarship Recipients: Since a significant portion of donors were scholarship recipients, highlighting the impact of scholarships in campaigns can encourage more giving from alumni who benefited from similar programs
- Monitor and Adjust: Regularly monitor the effectiveness of the strategies and adjust based on new data, feedback, and results.
  
## Misc. Recommendations:
- Data Gaps: Address missing or incomplete data (e.g., age and donor attributes) to enhance the accuracy of future models.
- Data Cleanup: Refine and update the dataset, then rerun the analysis to improve model performance.
- Ongoing Updates: Regularly refresh models as new or updated data becomes available to ensure strategies remain aligned with current trends.

## Folder Structure and Description 
- Project Proposal : Include the project proposal.
- Master Data : This folder contains the master data and the data dictionary before the cleaning.
- Final_presentation : Include the final presentation.
- Shannon: Code base and visuals related to the "Alumni Fund"
- Krishna : Code base for exploratory Data Analysis of Donors and Non-Donors to better understand insights into the composition and their engagement in different campus activities such as 'Student Organizations', 'Arts', 'Fraternal Organizations',  athletics, and age group.
- Caleb : 
- Jim : Tableau visualization of the data insights and patterns. 
- Walgama : Code base and visuals related to the "Non Donors features"



