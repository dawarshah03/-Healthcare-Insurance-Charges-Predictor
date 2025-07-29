# Healthcare-Insurance-Charges-Predictor

I used linear regression to predict insurance charges based on Age, BMI, Children, Smoker, Gender and Region.

I used SkLearn Library for Linear Regression.

We did hot encoding because some data like gender, smoker and region were in string (like "male", "yes", etc) but the model only understands numbers.
So we converted them into 0 and 1 format. That’s called hot encoding.

For example, sex_male = 1 means its male, 0 if its female.
smoker_yes = 1  means its a smoker, 0 if not.
region was also split into region_northwest, region_southeast, region_southwest, etc.

Example:
Givin Data:

| Age | BMI  | Children | Smoker (Yes=1) | Male (1) | Region_NW | Region_SE | Region_SW  |
|-----|------|----------|----------------|----------|-----------|------------|-----------|
| 30  | 28.5 |    2     |       1        |     0    |     0     |     1      |     0     |

# It predicted the output: 19280.45$

Complete Code file and Dataset is also Available in the repository.
