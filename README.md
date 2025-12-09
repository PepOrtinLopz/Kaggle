# Car Price Prediction - Kaggle

### Prerequisites
- An IDE like IntelliJ IDEA, Visual Studio Code.

## 📄 Project Report 

# Dataset
The dataset used in this project is: # Price Prediction Model 

## Authors
| **Name**              | **NIU**   |
|-----------------------|-----------|
| Arnau Muñoz Barrera   | 1665982   |
| José Ortín López      | 1667573   |

## Objective

This project has the objective of creating a machine learning model to predict car prices based on various features. This project is based on the Kaggle Car Price Prediction Challenge dataset from Kaggle.

## Database

To access the source Database: [Link to Database](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data)

This dataset contains most recent and relevant information that Craiglist provides on car sales including 22 columns. This data is scraped every few months.

- **Target:** Price
- **Features:** year, model, manufacturer, condition, fuel, cylinders, transmission, etc.

# Objectives

Beyond the final, material objective, which is to create a machine learning model capable of predicting car prices based on a set of characteristics, there is the objective of learning how to structure a machine learning project. To do this, we have divided the project into four phases:

**1. EDA (Exploratory Data Analysis):** In this first phase, we observed the fields and data contained in this dataset. The main objective was to make initial contact with the dataset to understand all the fields it contained and how the data had been stored in it.

**2. Preprocessing:** Once we were familiar with the dataset, we made the relevant changes we considered necessary to the data. The objective of this second phase was to prepare the data so that it could be analyzed with the models. We made the following changes to the data: elimination of columns with excessive numbers of NaNs, normalization, PCA, etc.

**3. Selection of metrics:** In this phase, we trained a regression model and calculated a set of metrics to then analyze which metric is most appropriate for the problem. This phase is essential for choosing the set of metrics we will use to decide which model best fits our dataset.

**4. Model selection:** In this phase, we will use the metric or set of metrics chosen in the previous phase to choose the best model. We trained different models with all the hyperparameter configurations.

**5. Final analysis:** Last but not least, we used the best-perfomance model with unseen data and we analyzed the results obtained and we helped us with graphical visualizations.

# Model & Results

The model with the best performance metricas was RandomForestRegressor with n_estimators=296 and max_depth=17.
The results obtained were:

| Metric | Train Set | Test Set |
|--------|-----------|----------|
| MAE    | 0.000134  | 0.000544 |
| R²     | 00.999992 | 0.999792 |
### Setup

**Clone the repository and go to the directory**:
```sh
git clone https://github.com/PepOrtinLopz/Kaggle.git
cd Kaggle
```

**Install the requiremnts file (mandatory)**:
<<<<<<< HEAD
```bash
pip install -r requirements.txt
```
=======
    ```pip install -r requirements.txt

    ```
>>>>>>> 9da8f62e2d64d0214cb1b35e95caa1db04244ede


