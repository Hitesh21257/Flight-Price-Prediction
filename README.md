# Flight-Price-Prediction

## Project Overview
This project, undertaken by Group 3 for our ML course, aims to predict flight prices using machine learning techniques. We developed a model that helps travelers make informed decisions by forecasting flight costs based on various factors.


## Table of Contents
1. [Motivation](#motivation)
2. [Literature Review](#literature-review)
3. [Dataset Description](#dataset-description)
4. [Methodology](#methodology)
5. [Results and Analysis](#results-and-analysis)
6. [Timeline](#timeline)
7. [Contribution](#contribution)

## Motivation
Flight prices vary significantly due to multiple factors such as airlines, destinations, and departure schedules. This variability makes it challenging for travelers to make cost-effective decisions. Our project seeks to leverage machine learning to build a model that accurately predicts flight prices, helping users optimize their travel plans and reduce costs.

![Motivation Image](path/to/motivation_image.png)

## Literature Review
### Research Paper 1
[Flight Price Prediction](https://www.ijraset.com/research-paper/flight-price-prediction) (IJRASET, 2022)

This paper discusses a project by students of Guru Nanak Institute of Technology that uses Decision Trees, Random Forests, and XGBoosts for predicting flight prices. They achieved the best results with Decision Trees, showing 78% accuracy.

### Research Paper 2
[A Framework for Airfare Price Prediction: A Machine Learning Approach](https://www.researchgate.net/publication/335936877_A_Framework_for_Airfare_Price_Prediction_A_Machine_Learning_Approach)

This paper presents a comprehensive approach to airfare price prediction using machine learning.

## Dataset Description
The dataset includes features such as:

| Feature            | Description                                           |
|--------------------|-------------------------------------------------------|
| Airline            | Name of the airline                                   |
| Flight             | Flight number                                         |
| Source_City        | Departure city                                        |
| Departure_Time     | Time of departure                                     |
| Stops              | Number of stops                                       |
| Arrival_Time       | Time of arrival                                       |
| Destination_City   | Destination city                                      |
| Class              | Seat class (economy/business)                         |
| Duration           | Total flight duration                                 |
| Days_left          | Days left for the flight                              |
| Price              | Flight price                                          |

![Dataset Visualization](path/to/dataset_visualization.png)

## Methodology
1. **Data Collection**
2. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical features
   - Normalizing numerical features
   - Bootstrapping to balance the dataset
3. **Feature Engineering**
4. **Modeling**
   - Training and testing various models
5. **Evaluation**

![Methodology Diagram](path/to/methodology_diagram.png)

## Results and Analysis
We evaluated multiple models:

| Model                  | Results |
|------------------------|---------|
| Linear Regression      | [Results Image](path/to/linear_regression_results.png) |
| Lasso Regularization   | [Results Image](path/to/lasso_regularization_results.png) |
| Ridge Regularization   | [Results Image](path/to/ridge_regularization_results.png) |
| SGD Regressor          | [Results Image](path/to/sgd_regressor_results.png) |
| Naive Bayes            | [Results Image](path/to/naive_bayes_results.png) |
| SVM                    | [Results Image](path/to/svm_results.png) |
| Decision Tree          | [Results Image](path/to/decision_tree_results.png) |
| Random Forest          | [Results Image](path/to/random_forest_results.png) |
| Polynomial Regression  | [Results Image](path/to/polynomial_regression_results.png) |

## Timeline
- **Week 1**: Data Preprocessing
- **Week 2**: Data Visualization & Feature Engineering
- **Week 3-4**: Model Training and Optimization
- **Week 5**: Front-End Ideation and Application
- **Week 6**: Model Evaluation and Fine-Tuning

## Contribution
### Akshat and Pratham
- Data Preprocessing and Exploration
- Feature Engineering and Selection

### Hitesh and Harsh
- Model Selection and Training
- Model Evaluation and Fine-Tuning

### All Members
- Comprehensive documentation of the entire project

---

Feel free to replace the image paths with the actual paths to your images.
