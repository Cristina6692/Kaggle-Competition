# Kaggle-Competition: Predicting Diamonds Prices

## ¡¡¡Empieza la competición!!! 

 Para poder obtener el mejor modelo de predicción de precios de diamantes hemos seguido los siguientes pasos:

- **1.** Descargamos los archivos *Diamonds_train.csv* y *Diamonds_test.csv* con los que vamos a trabajar para entrenar nuestros modelos

- **2.** Hacemos varios tipos de limpieza y tratado de datos como *normalizar y estandarizar*, *get_dummies*, *borrado de columnas* entre otros.

- **3.** Entrenamos nuestros modelos. En este caso hemos utilizado:  
         - sklearn.ensemble.RandomForestRegressor.  
         - sklearn.linear_model.LinearRegression.  
         - sklearn.ensemble.GradientBoostingRegressor.  
         Primero hemos entrenado con *diamonds_train.csv* dividido en 80% train y 20% test y despues con el 100% como train.  
         
- **4.** Por último aplicamos a nuestro modelo entrenado *diamonds_test.csv* tratado de la misma forma que *diamonds_train.csv*. Hacemos la predicción del precio, lo convertimos a csv y lo subimos a Kaggle para ver si nuestros resutados son los esperados.

## Carpetas:

- **Inputs**: encontramos los archivos.csv.  
- **src**: archivo jupyter notebook con el código.  
- **Outputs**: los archivos.csv con los resultados de las predicciones.
