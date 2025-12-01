**1.** Para este caso el modelo que se uso fue de regresión porque la variable objetivo a predecir es (la tasa de producción de arena en kg/día) ya que es una variable numérica continua. 



**2.** Variables más influyentes:

Los modelos de Random Forest y XGBoost identificaron que la permeabilidad, la resistencia a la compresión, la cohesión y el tamaño de grano son las variables más relevantes para predecir la tasa de producción de arena.



**3**. Transformaciones y limpieza:

Eliminar outliers  y aplicar la transformación logarítmica a la variable objetivo mejoró notablemente el desempeño de los modelos, acercando el R² a valores más altos y reduciendo el error cuadrático medio.



**4**. Modelos predictivos:



El modelo OLS (regresión lineal) mostró una capacidad limitada para capturar la complejidad de la relación entre variables.

Los modelos Random Forest y XGBoost, especialmente tras la optimización de hiperparámetros y la limpieza de datos, lograron R² elevados (cercanos a 0.9), lo que indica una excelente capacidad predictiva.

El uso de pipelines y GridSearchCV permitió encontrar configuraciones óptimas para los modelos, maximizando el poder explicativo.



**5.** Importancia de la ingeniería de variables:

La selección adecuada de variables y el tratamiento de las variables categóricas y numéricas fueron clave para mejorar los resultados de los modelos.



**6.** Aplicabilidad:

Los modelos desarrollados pueden ser utilizados para estimar la producción de arena en nuevos pozos, ayudando a la toma de decisiones operativas y de diseño.





