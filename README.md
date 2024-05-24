# The Objective
Supervised learning techniques are used to automate the credit card approval process for banks.

Data is preprocessed and supervised learning techniques are applied to find the best model and parameters for the task. The ultimate goal is to find the accuracy score of the best model as a numerical variable, best_score. The target is an accuracy score of at least 0.75.

#El Objetivo
Se utilizan técnicas de aprendizaje supervisado para automatizar el proceso de aprobación de tarjetas de crédito para bancos.

Previamente se procesan los datos y se aplican técnicas de aprendizaje supervisado para encontrar el mejor modelo y parámetros para el trabajo. El objetivo final es encontrar la puntuación de precisión del mejor modelo como una variable numérica, best_score. Se apunta a una puntuación de precisión de al menos 0,75.

### Strategy
* Preprocess the data
* Prepare the data for modeling
* Train the model
* Find the best scoring model
### Estrategia
* Preprocesar los datos
* Preparar los datos para modelar
* Entrenamiento del modelo
* Encontrar el mejor modelo
* Requirements

### Make sure you have the following libraries installed:

* pandas
* numpy
* scikit-learn

Installation
Clone the repository and navigate to the project directory:

bash

Copiar código

git clone https://github.com/dmcarrera/Credit-Approval-Predictionl.git

cd Credit-Approval-Predictionl

### Usage
Run the Jupyter Notebook to see the data preprocessing, model training, and evaluation steps:

bash

Copiar código

jupyter notebook CreditApp.ipynb

Data Preprocessing

### The data preprocessing steps include:

* Handling missing values
* Encoding categorical variables
* Scaling numerical features
* Model Training
* Several supervised learning models are trained and evaluated to find the best performing model. Techniques such as cross-validation and grid search are used to optimize hyperparameters.

### Finding the Best Model
The model with the highest accuracy score is selected as the best model. The goal is to achieve an accuracy score of at least 0.75.

### Results
The final model's performance is evaluated, and the accuracy score is reported. Additional evaluation metrics such as confusion matrix, precision, recall, and F1 score can also be included.

### Contributing
Feel free to fork this repository and make improvements. Pull requests are welcome.

