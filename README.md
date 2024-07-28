# Project-Repo
Study on factors affecting power output of a combined cycle power plant and prediction based on data.


- A combined cycle power plant is one of the most efficient power plants that uses both gas and steam turbines to produce 50% more electricity than what a traditional simple cycle plant produces.
- The main aim of this paper is to predict the output of the combined cycle power plant using several machine learning algorithms.
- Predicting the full load electric power is extremely instrumental in order to maximize the profit from the available megawatt hours.
- The base load operation of this power plant is affected by four main factors:
  - Ambient temperature
  - Atmospheric pressure
  - Relative humidity
  - Exhaust steam pressure
- The power output, which is influenced by these factors, is considered as the target variable.
- This paper consists of a detailed study of the data available and assesses which machine learning algorithm works the best in examining the factors and predicting the output.
- The most accurate machine learning algorithm is found using various accuracy metrics.

## Linear Regression Accuracy Metrics

| Metric                  | Value                  |
|-------------------------|------------------------|
| R2 Score                | 0.9278034642596562     |
| Mean Absolute Error     | 3.6374586763847        |
| Mean Squared Error      | 20.95100810799155      |
| Root Mean Squared Error | 4.577227119992141      |

## Polynomial Regression Accuracy Metrics

| Metric                  | Value                  |
|-------------------------|------------------------|
| R2 Score                | 0.9416201631798347     |
| Mean Absolute Error     | 3.2051238883549265     |
| Mean Squared Error      | 16.941483715527134     |
| Root Mean Squared Error | 4.116003366802211      |

## Decision Tree Regression Accuracy Metrics

| Metric                  | Value                  |
|-------------------------|------------------------|
| R2 Score                | 0.8593733120875664     |
| Mean Absolute Error     | 5.106282749531314      |
| Mean Squared Error      | 40.80903395766401      |
| Root Mean Squared Error | 6.388194890394627      |

## Random Forest Regression Accuracy Metrics

| Metric                  | Value                  |
|-------------------------|------------------------|
| R2 Score                | 0.9395235633502752     |
| Mean Absolute Error     | 3.2388779030504384     |
| Mean Squared Error      | 17.549904598577477     |
| Root Mean Squared Error | 4.189260626718929      |

## Files

- **Decision Tree.ipynb**: Jupyter notebook for Decision Tree Regression.
- **Folds5x2_pp.csv**: Dataset used for training and testing the models.
- **Linear Regression.ipynb**: Jupyter notebook for Linear Regression.
- **Polynomial Regression.ipynb**: Jupyter notebook for Polynomial Regression.
- **Project Report.pdf**: Detailed report of the project.
- **Project Summary.pdf**: Summary of the project.
- **README.md**: This file.
- **Random Forest.ipynb**: Jupyter notebook for Random Forest Regression.
- **analysis-and-prediction-of-power.ipynb**: Jupyter notebook for the overall analysis and prediction of power output.
- **final_prepared.xlsx**: Excel file containing prepared data.
