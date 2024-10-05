
# Medical Insurance Cost Prediction

# PROJECT OVERVIEW
Health insurance costs have risen dramatically over the past decade in response to the rising cost of health care services and are determined by a multitude of factors. Let's look at the cost of healthcare for a sample of the population given age, sex, bmi, number of children, smoking habits, and region.

The purpose of this project is to determine the contributing factors and predict health insurance cost by performing exploratory data analysis and predictive modeling on the Health Insurance dataset. This project makes use of Numpy, Pandas, Sci-kit learn, and Data Visualization libraries.

<b>Overview:</b> <br>
• Seek insight from the dataset with Exploratory Data Analysis <br>
• Performed Data Processing, Data Engineering and Feature Transformation to prepare data before modeling <br>
• Built a model to predict Insurance Cost based on the features <br>
• Evaluated the model using various Performance Metrics like RMSE, R2, Testing Accuracy, Training Accuracy and MAE <br>

# DATA DESCRIPTION
age: age of primary beneficiary
sex: insurance contractor gender, female, male
bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9
children: Number of children covered by health insurance / Number of dependents
smoker: Smoking
region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest
charges: Individual medical costs billed by health insurance

Data source : https://www.kaggle.com/mirichoi0218/insurance

## EXPLORATORY DATA ANALYSIS (EDA)
• Feature sex, region has an almost balanced amount, meanwhile most people are non smoker & obese <br>
![image](https://github.com/dsaini21/MEDICAL_INSURANCE_COST_ANALYSIS/blob/main/images/4_Countplot_output.png)

• A person who smoke and have BMI above 30 tends to have a higher medical cost <br>
![image](https://github.com/dsaini21/MEDICAL_INSURANCE_COST_ANALYSIS/blob/main/images/5_Scatterplot_output.png)

• Older people who smoke have more expensive charges <br>
![image](https://github.com/dsaini21/MEDICAL_INSURANCE_COST_ANALYSIS/blob/main/images/6_Scatterplot_output.png)

• People who smoke and obese have the highest average charges compared to others <br>
![image](https://github.com/dsaini21/MEDICAL_INSURANCE_COST_ANALYSIS/blob/main/images/barplot.png)
## INSIGHTS
The insights drawn by performing `Exploratory Data Analysis` (EDA) are:

- Most people are a non smokers & obese.
- Feature sex, region has an almost balanced amount.
- People who smoke & have a higher BMI, has higher medical charges.
- Older people who smoke have more expensive charges.
- An obese person who smokes have higher charges.
