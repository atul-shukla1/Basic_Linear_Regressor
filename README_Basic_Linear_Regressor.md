
![Logo](https://github.com/atul-shukla1/Basic_Linear_Regressor/blob/main/ML%20Readme%20Logo.jpg)


# Basic Linear Regression model

A basic linear Regression model to predict the housing prices in California

## Authors

- [Atul Shukla](github.com/atul-shukla1)



## Implementation Details

- Dataset: California Housing Dataset (view below for more details)
- Model: [Linear Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)
- Input: 8 features (as given below)
- Feature Selection Prcocess - Domain Expertise 
- Train Test Split - 80:20
- Output: Predicted Housing Price

## Dataset Details

This dataset was obtained from the StatLib repository ([Link](https://www.dcc.fc.up.pt/~ltorgo/Regression/cal_housing.html))

This dataset was derived from the 1990 U.S. census, using one row per census block group. A block group is the smallest geographical unit for which the U.S. Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people).

A household is a group of people residing within a home. Since the average number of rooms and bedrooms in this dataset are provided per household, these columns may take surprisingly large values for block groups with few households and many empty houses, such as vacation resorts.

It can be downloaded/loaded using the sklearn.datasets.fetch_california_housing function.

- [California Housing Dataset in Sklearn Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html)
- 20640 samples
- 8 Input Features: 
    - MedInc median income in block group
    - HouseAge median house age in block group
    - AveRooms average number of rooms per household
    - AveBedrms average number of bedrooms per household
    - Population block group population
    - AveOccup average number of household members
    - Latitude block group latitude
    - Longitude block group longitude
- Target: Median house value for California districts, expressed in hundreds of thousands of dollars ($100,000)

## Evaluation and Results

The model has R2 score of 0.60 and Mean Square Error of 0.54. This signifies a good fit and the model can accurately predict the housing prices in California.

| Metric        | Value         |
| ------------- | ------------- |
| R2 Score      | 0.60          |
| MSE           | 0.54          |

## How to Run

The code is built on Google Colab on an iPython Notebook. 

## Key Takeaways

Being a beginer in Python, it was a good exercise to learn and implement the ML concepts, while taking the project to completion.

## Future Roadmap

- Incorporating feature selection methods 
- Evaluating other models 
- Exploring better accuracy rates

## Libraries 

**Language:** Python

**Packages:** Sklearn, Matplotlib, Pandas

## Contact

If you have any feedback/are interested in collaborating, please reach out to me at github.com/atul-shukla1 


## License

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
.
