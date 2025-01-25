# Energy Prediction

This repository contains a course project focused on comparing different machine learning methods for energy prediction on multiple datasets. The project aims to evaluate the performance of various algorithms in predicting energy consumption, using data from different time intervals and sources.

## Datasets

The project uses multiple datasets with different time intervals and sources. The main datasets are:

- Half-year data
- Yearly data

## Machine Learning Methods

The following machine learning algorithms were used and compared in this project:

- HistGradientBoostingRegressor (HGBR)
- RandomForestRegressor
- AdaBoostRegressor
- CatBoostRegressor
- Support Vector Regressor (SVR)
- KMeans for clustering

## Results

The results of the comparison showed that the HistGradientBoostingRegressor (HGBR) performed the best on the half-year data, providing high accuracy, low training time, and low data dispersion. The yearly data showed a linear increase in errors, indicating potential underfitting.

## Conclusion

The project demonstrates the effectiveness of different machine learning algorithms for energy prediction. The HGBR model was found to be the most suitable for high availability systems with many clients, especially when using data with 5-minute intervals. Future improvements could include adding more parameters, such as weather conditions and specific industrial processes, to enhance model accuracy.

## References

1. [Energy Consumption Prediction by using Machine Learning Case Study Malaysia](https://www.researchgate.net/publication/347479213_Energy_Consumption_Prediction_by_using_Machine_Learning_for_Smart_Building_Case_Study_in_Malaysia)
2. [Kaggle](https://www.kaggle.com/datasets/csafrit2/steel-industry-energy-consumption)
3. [HistGradientBoostingRegressor](https://scikit-learn.org/1.5/modules/generated/sklearn.ensemble.HistGradientBoostingRegressor.html)
4. [RandomForestRegressor](https://scikit-learn.org/1.5/modules/generated/sklearn.ensemble.RandomForestRegressor.html)
5. [AdaBoostRegressor](https://scikit-learn.org/1.5/modules/generated/sklearn.ensemble.AdaBoostRegressor.html)
6. [CatBoostRegressor](https://catboost.ai/docs/en/concepts/python-reference_catboostregressor)
7. [SVR](https://scikit-learn.org/1.5/modules/generated/sklearn.svm.SVR.html)
8. [KMeans](https://scikit-learn.org/1.5/modules/generated/sklearn.cluster.KMeans.html)
9. [GridSearchCV](https://scikit-learn.org/1.5/modules/generated/sklearn.model_selection.GridSearchCV.html)

## Usage

To run the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/TihomirGalov/energy-prediction.git
   cd energy-prediction
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebooks in the `notebooks/` directory to see the analysis and results.

4. Use the scripts in the `scripts/` directory for data preprocessing, model training, and evaluation.