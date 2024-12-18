# Housing Price Predication Steps

### Overview

This project involves predicting housing prices using various machine learning models. The analysis uses structured data to train and test models, providing insights into the most influential factors affecting housing prices. The project includes data preprocessing, feature engineering, model training, and evaluation.

### Goals
- Predict housing prices based on given features.
- Compare the performance of different regression models.
- Understand the importance of various features in determining housing prices.

----
### Libraries Used

- The following Python libraries were utilized in this project:
- pandas: For data manipulation and analysis.
- numpy: For numerical operations.
- matplotlib: For data visualization.
- seaborn: For advanced visualization.
- scikit-learn: For machine learning models and preprocessing.

    ```python
        import pandas as pd
        import numpy as np
        import matplotlib.pyplot as plt
        from sklearn.model_selection import train_test_split
        import seaborn as sns
        from sklearn.preprocessing import MinMaxScaler
        from sklearn.linear_model import LinearRegression
        from sklearn.metrics import mean_squared_error, r2_score, mean_absolute_error
        from sklearn.ensemble import GradientBoostingRegressor
    ```

----
### Dataset

https://www.kaggle.com/datasets/nachiket195/housing-price 
