# CO2 Emissions Prediction with Green Energy Transition
## Overview
This repository houses machine learning models developed to predict CO2 emissions based on the transition to green energy. By leveraging artificial intelligence, specifically machine learning, the project analyses energy consumption and emissions data, identifies patterns, and offers future predictions.

## Models
Two predictive models were developed:
1. A comprehensive model analyzing the entire dataset.
2. An optimized model focusing on specific features to ensure efficiency, interpretability, and prevention of overfitting.
At its core, the primary model uses a Decision Tree Regressor. This model was further fine-tuned using feature selection techniques and GridSearchCV for hyperparameter tuning. As an additional perspective, a Random Forest Regressor was incorporated, which showcased superior performance.

## Key Findings
- The Random Forest Regressor, especially post-optimization, exhibited a notable performance enhancement over the Decision Tree Regressor.
- The ensemble methods, specifically the Random Forest, reduced the RMSE significantly from 6.393 to 5.840.
- The study confirmed the correlation between the adoption of green energy and a reduction in CO2 emissions.

## Limitations and Future Work
While promising, this study has its limitations:
- The dataset's relatively small size.
- Omission of some variables, such as climate patterns.

### For future work:
1. It's recommended to leverage larger and more comprehensive datasets.
2. Exploration of other machine learning techniques, like gradient boosting, could be considered to further improve the model's robustness and accuracy.
3. Evaluating the biases of the Decision Tree Regressor and computational overheads of GridSearchCV could provide directions for alternative optimization techniques.

## Usage
Clone the repository and follow the Jupyter notebook for a step-by-step guide on the development, tuning, and evaluation of the models.

## Licensing
This work is not licensed for any use. If you wish to use this project, please contact me.
