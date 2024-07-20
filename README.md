# Uso de algoritmos de clasificacion para prediccion de lluvias

### Proyecto destinado al uso de algoritmos de clasificacion para predecir precipitaciones en base a observaciones de variables del clima. Se utilizan diferentes algortimos de clasificacion como *regresion lineal*, *KNN*, *arboles de decision*, *regresion logistica* y *SVM*, los cuales se comparan utilizando diferentes metricas para evaluar los modelos (Accuracy score, Jaccard index, F1-Score, MAE, MSE, entre otros) y obtener una comparativa entre los mismos. 

## Conocimientos aplicados:
* Importar datos y trabajar con dataframes
* Realizar analisis exploratorio de los datos, identificando correlaciones, comportamientos y patrones de interes.
* Aplicar transformaciones sobre los datos
* Uso de tecnicas de IA
* Uso de metricas de evaluacion de rendimiento
* Analisis de rendimiento de los modelos aplicados

### Uso de Python Pandas, Numpy, Matplotlib, SciKit Learn, Seaborn y Jupyter

La fuente original de los datos a utilizar es de la Oficina de Meteorología del Gobierno de Australia, la cual puede obtenerse a traves del siguiente link: http://www.bom.gov.au/climate/dwo/.

El conjunto de datos que se utilizará tiene columnas adicionales como 'RainToday' y la variable objetivo es 'RainTomorrow', que se recopiló del Rattle en: https://bitbucket.org/kayontoga/rattle/src/master/data/weatherAUS.RData

Las definiciones de columnas fueron obtenidas de http://www.bom.gov.au/climate/dwo/IDCJDW0000.shtml

El proyecto desarrollado forma parte de la formacion *Machine Learning with Python* un curso en línea autorizado por IBM y ofrecido a través de Coursera

## Resultados obtenidos

![descarga](https://github.com/user-attachments/assets/d38e5522-824f-44fd-ac6d-87580850ab3f)

### En base a estas métricas, el modelo de regresión logística (LR) parece tener el mejor rendimiento general, ya que tiene la precisión, el índice de Jaccard y el F1 Score más altos entre los modelos evaluados. Además, el modelo LR es el único que proporciona un valor de LogLoss, lo que sugiere que tiene una mejor calibración de las probabilidades predichas. Por lo tanto, en este caso, el modelo de regresión logística podría considerarse como el mejor modelo de los evaluados. 
