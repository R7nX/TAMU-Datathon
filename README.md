# TAMU-Datathon
## Inspiration
The initial code produced low accuracy, primarily attributed to data and model imperfections. Consequently, we embarked on a journey to explore various methods to enhance the model's performance.

## What it does
Our projects determine the top 10 contributing factors that determine the live status of a person. Also, we optimize a training model to predict the probability of death of a person.   

## How we built it
We built this project by initially preprocessing the data, including addressing missing values, encoding categorical features, and standardizing the dataset. Following that, we employed label encoding to convert categorical data into numerical format, making it compatible with machine learning models. We performed correlation analysis to determine the ten most influential factors correlated with the "death" outcome variable. This analysis provided valuable insights into the main drivers of survival. Subsequently, we developed and trained four distinct models: a Neural Network, Linear Regression, and Random Forest Classifier, XGBoost. Lastly, we harnessed the power of multithreading to concurrently experiment with different data preprocessing techniques, enabling us to enhance model accuracy and gain a deeper understanding of the factors impacting survival rates.

## Challenges we ran into
Data preprocessing was challenging in this problem. One of the main issues we faced was the handling of missing values, with some columns containing up to 40% null data. Furthermore, the 'sex' column contained unstructured data, including unique values like 'male,' 'm,' '1,' and 'female.' To address this, we needed to transform this unstructured data into binary values (0 or 1). Additionally, we had to convert categorical values into numerical format to make them compatible with the model.

## Accomplishments that we're proud of
We're proud of overcoming data preprocessing challenges, achieving valuable insights through correlation analysis, and optimizing model accuracy with multithreading. Our ability to convey the significance of early diagnosis is a standout accomplishment.

## What we learned
Throughout our project, we explored various data preprocessing techniques to address data quality issues and employed multiple modeling approaches. Among the top 10 factors influencing an individual's survival, time known was interesting: an extended duration of disease knowledge correlates with a significant decrease in the likelihood of mortality. This highlights the critical significance of early diagnosis and timely medical intervention for patients.

## What's next for Optimizing the model using multiple methods
In the future, we'll focus on fine-tuning the XGBoost model by optimizing its settings for even better results. We'll also explore more ways to enhance our feature engineering to improve accuracy. Plus, we'll test the model on a wider range of healthcare data to make sure it works well in various real-world scenarios.
