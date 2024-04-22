#  Classification algorithm

Supervised learning is when an algorithm learns patterns from labeled data. Training the algorithm is done with inputs (predictors) that are associated with the correct output (targets). The algorithm can then be used to classify new observations.

We can distinguish between regression (predicting a number) and classification (predicting a category, or class). 

The goal of classification is to accurately predict the target class for each case in the data. For example, a classification algorithm will learn from a dataset where the emails are labeled as "spam" or "not spam", and then classify a new email into one of those categories.

For this project we use a dataset with general information of different subjects to train different models that use classification algorithms to identify if a subject have diabetes or not.

# Metadata
THe dataset consists of the following metadata:

- Diabetes_012: Three categories indicating the diabetes status: 0 for no diabetes, 1 for pre-diabetes, and 2 for diabetes.

- HighBP: Indicates whether the patient has high blood pressure (1) or not (0).

- HighChol: Indicates whether the patient has high cholesterol levels (1) or not (0).

- CholCheck: Indicates whether the patient has had a cholesterol check in the past 5 years (1) or not (0).

- BMI: Body Mass Index, a measure of body weight relative to height.

- Smoker: Indicates whether the person has smoked more than 100 cigarettes in their lifetime (1) or not (0).

- Stroke: Indicates whether the person has ever had a stroke (1) or not (0).

- HeartDiseaseorAttack: Indicates whether the person has had coronary heart disease or a myocardial infarction (1) or not (0).

- PhysActivity: Indicates whether the person has engaged in physical activity in the past 30 days (1) or not (0).

- Fruits: Indicates whether the person eats more than one piece of fruit per day (1) or not (0).

- Veggies: Indicates whether the person eats more than one piece of vegetables per day (1) or not (0).

- HeavyAlcoholConsumption: Indicates whether the person consumes more than a certain amount of alcohol per week, depending on gender.

- AnyHealthcare: Indicates whether the person has health insurance (1) or not (0).

- NoDocbcCost: Indicates whether the person had to see a doctor in the past year but avoided it due to costs (1) or not (0).

- GenHlth: Allows the person to assess their overall health on a scale of 1 to 5.

- MentHlth: Indicates whether the person has had mental health issues, and if so, how many days in the past 30 days.

- PhysHlth: Indicates whether the person has had physical health issues, and if so, how many days in the past 30 days.

- DiffWalk: Indicates whether the person has difficulty walking/climbing stairs (1) or not (0).

- Sex: Gender of the person, where 0 represents female and 1 represents male.

- Age: Age of the person.

## Requirements

The requirements to run this project are:

- matplotlib==3.8.1
- numpy==1.26.4
- pandas==2.2.2
- plotly==5.18.0
- scikit_learn==1.3.2
- seaborn==0.13.2

## Authors

- [@JorgeVC17](https://github.com/JorgeVC17)


## License

[MIT](https://choosealicense.com/licenses/mit/)

- Education: Level of education, on a scale of 1 to 6.

- Income: Income, based on different income levels.
