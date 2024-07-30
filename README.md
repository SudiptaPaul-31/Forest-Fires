
# Forest Fire Wheather Index(FWI)

This project is designed to predict the Forest Fire Weather Index (FWI) values using a machine learning model. The FWI system is a comprehensive tool used worldwide to assess the risk of forest fires based on various meteorological parameters.


Key Features
Machine Learning Model: The project utilizes a Ridge Regression model to make predictions. This model has been trained on historical data to understand the relationship between the input parameters and the FWI values.

Data Preprocessing: The input data is scaled using a StandardScaler to ensure that all features contribute equally to the model’s predictions. This preprocessing step is crucial for improving the model’s accuracy.

Web Application: A user-friendly web interface has been developed using Flask. This allows users to input the necessary parameters and receive predictions seamlessly.

Form Validation: The web application includes form validation to ensure that users provide all required inputs correctly. This helps in maintaining the integrity and reliability of the predictions.

Deployment: The Flask application is designed to run on a server, making it accessible to users from anywhere.


## Deployment

To deploy this project run

```bash
  python application.py
```


## Dataset

[Dataset](https://www.kaggle.com/datasets/elikplim/forest-fires-data-set)

