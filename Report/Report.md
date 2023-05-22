# Project Report
## Aim
The main aim of this project is to predict the correct concrete compressive strength using machine learning techniques. Concrete compressive strength is a highly nonlinear function of age and ingredients.

## Introduction
Concrete is the most important material in civil engineering, and its compressive strength is a critical property for assessing its quality and durability. The compressive strength of concrete depends on various factors, including the age of the concrete and the proportions of different ingredients used in its composition.

##### The ingredients considered in this project are:

1. Cement
2. Blast furnace slag
3. Fly ash
4. Water
5. Superplasticizer
6. Coarse aggregate
7. Fine aggregate


We will utilize the given information about these ingredients to predict the different cement compressive strengths.

Project Timeline
1. Data Analysis: In this phase, we will explore and analyze the available data to gain insights into its structure and characteristics.
2. Data Preprocessing: Here, we will preprocess the data, which may involve handling missing values, scaling features, or encoding categorical variables.
3. Feature Engineering: We will extract and engineer relevant features from the available data to enhance the model's predictive power.
4. Model Building using Deep Learning: We will use the Keras Sequential model to develop a predictive model for cement compressive strength based on the given ingredients.
# Results
After training the model, we obtained the following metrics:

- Loss: 276.3860
- Mean Absolute Error (MAE): 13.1677

The range of ingredient values and the concrete compressive strength in the dataset are as follows:

- Cement: Min - 102.0, Max - 540.0
- Blast furnace slag: Min - 0.0, Max - 359.4
- Fly ash: Min - 0.0, Max - 200.1
- Water: Min - 121.8, Max - 247.0
- Superplasticizer: Min - 0.0, Max - 32.2
- Coarse aggregate: Min - 801.0, Max - 1145.0
- Fine aggregate: Min - 594.0, Max - 992.6
- Age: Min - 1, Max - 365
- Concrete compressive strength: Min - 2.33, Max - 82.6
## Conclusion

In this project, we successfully built a machine learning model using the Keras Sequential model to predict the cement compressive strength based on the given ingredients. The model achieved reasonable performance, as indicated by the obtained metrics.

Overall, this project demonstrates the application of machine learning techniques in predicting concrete compressive strength, which can be valuable in civil engineering applications and decision-making processes.

Note: This report is based on the information provided in the given context. Further details, analyses, and discussions can be included depending on the specific requirements and findings during the project execution.