# Machine Learning ZoomCamp: Session - Car Price Prediction Model

## 01 Introduction

This session focuses on a hands-on project to implement a car price prediction model. This addresses the scenario introduced in Session 1, where the goal is to help users of online classified websites determine the best price for their cars.

### Problem Definition

**Problem:** Users want to sell their cars but need assistance in determining a fair and competitive price.

**Solution:** Develop a machine learning model that predicts car prices based on various features.

### Data Collection

**Dataset:**  We will use a dataset from Kaggle containing [car prices and features](https://www.kaggle.com/datasets/CooperUnion/cardataset).

**Dataset Features:** The dataset includes various car characteristics as follows:

| Variable Name     | Description                                  | Data Type | Notes/Constraints                        |
|-------------------|----------------------------------------------|-----------|------------------------------------------|
| Make              | Car manufacturer                             | String    |                                          |
| Model             | Specific model of the car                    | String    |                                          |
| Year              | Year of manufacture                          | Integer   | Range: 1908-present                      |
| Engine Fuel Type  | Type of fuel used by the engine              | String    | e.g., "premium unleaded (required)"      |
| Engine HP         | Horsepower of the engine                     | Integer   | Positive values                          |
| Engine Cylinders  | Number of cylinders in the engine            | Integer   | Typically 3-12                           |
| Transmission Type | Type of transmission                         | String    | e.g., "MANUAL", "AUTOMATIC"              |
| Driven_Wheels     | Which wheels are powered                     | String    | e.g., "rear wheel drive", "all wheel drive" |
| Number of Doors   | Number of doors on the vehicle               | Integer   | Typically 2-5                            |
| Market Category   | Categories the car falls into                | String    | Multiple categories separated by commas  |
| Vehicle Size      | General size category of the vehicle         | String    | e.g., "Compact", "Midsize", "Large"      |
| Vehicle Style     | Body style of the vehicle                    | String    | e.g., "Coupe", "Sedan", "SUV"            |
| highway MPG       | Miles per gallon fuel efficiency on highway  | Integer   | Positive values                          |
| city mpg          | Miles per gallon fuel efficiency in city     | Integer   | Positive values                          |
| Popularity        | Popularity score of the car make             | Integer   | Meaning/scale needs clarification        |
| MSRP              | Manufacturer's Suggested Retail Price        | Integer   | In USD, positive values                  |
