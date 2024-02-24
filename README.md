# PROYECTO_FINAL_BREAST_CANCER

## 1) Preprocesamiento de datos.
El preprocesamiento consiste en las siguientes tareas:

a) Carga de Datos: Utilizar Pandas para leer los archivo de origen.

b) Exploración y Limpieza: Verificar valores faltantes y realiza cualquier limpieza necesaria.

c) Codificación de Etiquetas: Convertir las etiquetas de clasificación de texto a números.

d) Normalización: Escalar las características numéricas para mejorar la convergencia del modelo.

## 2) Proceso de modelamiento.

e) Selección de modelos: Utilizar modelos que sean efectivos en problemas de clasificación.

f) Entrenamiento del modelo: Entrenar el modelo usando datos de entrenamiento; el modelo aprenderá patrones y relaciones entre las características y las etiquetas.

g) Predicción del modelo: Realizar predicciones con los datos de prueba.

h) Evaluación del modelo: Utilizar el conjunto de prueba para evaluar el rendimiento del modelo.

## 3) Selección de modelos.
Los siguientes modelos seleccionados para el dataset de cáncer de mama de Wisconsin son adecuados debido a sus características únicas y efectividad en problemas de clasificación:

a) Regresión Logística: Es un modelo lineal que funciona bien para problemas de clasificación binaria, como determinar si un tumor es benigno o maligno. Es sencillo, rápido y proporciona una buena línea base para la evaluación del rendimiento.

b) SVM (Support Vector Machine): Es eficaz en espacios de alta dimensión como este dataset, donde cada muestra tiene muchas características. SVM es conocido por su capacidad para manejar datos no lineales y proporcionar límites de decisión complejos.

c) Random Forest: Es un modelo basado en árboles que funciona bien para la clasificación en datasets con múltiples características. Puede manejar características no lineales y proporciona una evaluación de la importancia de las características, lo cual es útil para la interpretación del modelo.

Estos modelos ofrecen un buen punto de partida para comparar diferentes enfoques de aprendizaje automático en tareas de clasificación y son capaces de capturar complejidades en los datos a través de sus respectivos mecanismos.

## 4) Resumen
En base a la tabla resumen obtenida, podemos resumir que los tres modelos de clasificación evaluados en el conjunto de datos: Regresión Logística, SVM y Random Forest; muestran una eficacia notablemente alta. La Regresión Logística y el SVM alcanzan idénticas métricas de rendimiento, destacando su precisión y capacidad para equilibrar la sensibilidad y la especificidad, como lo indica su elevado AUC de 0.997380. El Random Forest, aunque ligeramente inferior en todas las métricas, también demuestra un rendimiento excepcional, con un AUC de 0.996888, lo que sugiere una mínima diferencia en la capacidad de discriminación entre los modelos.

         Modelo           Accuracy   Precision  Recall   F1-Score    AUC
    Logistic Regression   0.973684   0.973719  0.973684  0.973621  0.997380
          SVM             0.973684   0.973719  0.973684  0.973621  0.997380
     Random Forest        0.964912   0.965205  0.964912  0.964738  0.996888
