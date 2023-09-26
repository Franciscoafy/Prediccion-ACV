Proyecto de Machine Learning para la Evaluación de Patologías Médicas

Este proyecto se centra en la generación y evaluación de modelos de Machine Learning para predecir patologías médicas en pacientes utilizando árboles de decisión y Random Forest. El objetivo principal es identificar y evaluar la presencia de enfermedades como la hipertensión en función de características médicas y de salud de los pacientes.

Descripción del Proyecto
Conjunto de Datos
Se utiliza un conjunto de datos con 4900 filas que contiene información sobre pacientes y diversas características médicas, incluyendo:

Hipertensión
Tipo de trabajo
Hábito de fumar
Índice de Masa Corporal (BMI)
Otros problemas de salud
Proceso de Desarrollo
El proyecto sigue los siguientes pasos:

Exploración de Datos: Se realiza una exploración inicial del conjunto de datos para comprender sus características y distribuciones. Se identifican posibles desequilibrios en las clases.

Preprocesamiento de Datos:

Se realiza el rebalanceo de clases para abordar desequilibrios.
Se aplica codificación one-hot a las variables categóricas.
Entrenamiento de Modelos:

Se generan modelos de árboles de decisión y Random Forest utilizando el conjunto de datos preprocesado.
Evaluación de Modelos:

Se evalúan los modelos utilizando métricas como precisión, recall, F1-score y matriz de confusión.
Ajuste de Hiperparámetros:

Se ajustan los hiperparámetros de los modelos para optimizar su rendimiento.
Despliegue y Uso:

Se selecciona el modelo con mejor rendimiento para su despliegue y uso en aplicaciones de detección de patologías médicas.


Estructura del Repositorio

dataset/: Carpeta que contiene el conjunto de datos original.
notebooks/: Carpeta con los Jupyter Notebooks que contienen el código para la exploración de datos, preprocesamiento y entrenamiento de modelos.
models/: Carpeta que almacena los modelos entrenados.
README.md: Este archivo que proporciona información general sobre el proyecto.
scripts/: carpeta donde estan las funciones utilizadas en el procesamiento y exploracion de los datos 
requeriments/:bibliotecas utilizadas para el desarrollo del proyecto 

Instrucciones de Uso

Clona el repositorio en tu entorno local.

Instala las bibliotecas necesarias utilizando pip install -r requirements.txt.

Ejecuta los Jupyter Notebooks en la carpeta notebooks/ para explorar y replicar el análisis y entrenamiento de modelos.

Utiliza el modelo entrenado seleccionado para realizar predicciones en tu aplicación.

Resultados y Conclusiones

El proyecto tiene como objetivo generar modelos de Machine Learning para la detección de patologías médicas, específicamente hipertensión, a partir de características médicas y de salud de los pacientes. Los modelos se evalúan de manera exhaustiva y se selecciona el modelo con el mejor rendimiento para su posible despliegue en aplicaciones de atención médica.