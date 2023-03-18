# MachineLearning

El resumen del proyecto o los pasos explicados serian los siguientes:
(que habria que hacer)

1.- Preparacion de datos:
-Cargar el conjunto de datos en un DataFrame de Pandas.\n
-Eliminar cualquier columna que no sea relevante para el problema o que tenga muchos valores nulos.
-Completar los valores nulos en las columnas restantes con una estrategia apropiada, como el promedio o la mediana.
-Separar las características del objetivo (el precio en este caso) en diferentes conjuntos de datos.
-Dividir los datos en conjuntos de entrenamiento y prueba usando una proporción adecuada (por ejemplo, 70% de entrenamiento y 30% de prueba).

2.- Analisis exploratorio:
(Pasos o steps)
-Calcular estadísticas descriptivas básicas para cada variable, como la media, la mediana, la desviación estándar, etc.
-Visualizar la distribución de cada variable usando histogramas, diagramas de caja, gráficos de densidad, etc.
-Identificar y eliminar valores atípicos o errores en los datos.
-Identificar y tratar los valores nulos o faltantes en los datos.
-Realizar un análisis de correlación entre las variables y el objetivo (el precio en este caso) para identificar posibles relaciones. (seaborn o matriz de correlacion)

3.- Preprocesamiento:
-Eliminar variables irrelevantes o redundantes que no aportan información útil al modelo.
-Manejar valores faltantes, ya sea eliminándolos, imputándolos o utilizando técnicas más avanzadas como imputación por modelo.
-Escalar o normalizar variables para garantizar que las variables de diferentes magnitudes no tengan un efecto desproporcionado en el modelo.
-Manejar variables categóricas, que pueden requerir una codificación especial para ser utilizadas en un modelo de machine learning.
-Manejar variables con valores extremos o atípicos, que pueden afectar negativamente la precisión del modelo.
-Reducir la dimensionalidad de las variables, lo que puede ser útil cuando se tienen muchas variables o cuando algunas variables están altamente correlacionadas.

4.- Categorizacion de variables
-Identificar todas las variables categóricas en el conjunto de datos. 
-Convertir las variables categóricas en variables numéricas
-Elegir la técnica de codificación adecuada para cada variable categórica
-Analizar la relación entre las variables categóricas y el objetivo (el precio en este caso) para identificar posibles relaciones y patrones.

5.- Modelado
-Selección de características: conjunto de características para incluir en el modelo. 
-Selección de modelo: seleccione un modelo de machine learning para ajustar a los datos.
-Entrenamiento del modelo: Ajustar el modelo a los datos de entrenamiento. El objetivo es minimizar la diferencia entre las predicciones del modelo y los valores reales en el conjunto de entrenamiento.
-Validación del modelo: Ver el rendimiento del modelo utilizando un conjunto de datos de validacion
-Evaluación final: evalúe el rendimiento del modelo en el conjunto de prueba para asegurarse de que el modelo generaliza bien a datos nuevos y no vistos.

-Conclusiones
Se evaluan los modelos de ML mirando el error obtenido

