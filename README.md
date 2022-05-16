## Implementación de un modelo de predicción de temperatura

Proyecto realizado para la clase de Big Data de la Maestría en Ciencia de Datos de la Universidad de Sonora.
Tiene como principal objetivo el uso de herramientas de Big Data como Spark, Apache Superset y ML-Flow.

### Introducción

Sabemos que la predicción climática es un problema bastante complejo y aun no resuelto por completo, existen algunas soluciones que nos ofrecen aproximaciones bastance aceptables y que actualmente son usadas globalmente, entre ellas esta WRF (Weather Research and Forecasting), ECMWF (European Centre for Medium-Range Weather Forecast), RAP (Rapid-Refresh) entre otros.

### Planteamiento del problema

Si bien es cierto que los modelos de predicción antes mencionados ofrecen resultados aceptables por la comunidad estos requieren de bastante tiempo y poder de cómputo para procesarse en un tiempo razonable. Esto implica invertir una fuerte cantidad de dinero en recursos de hardware y personal calificado para su implementación.

### Propuesta de solución

Proponemos implementar un modelo de regresión para predecir la temperatura para la región noroeste de México utilizando el modelo WRF como nuestro conjunto de entrenamiento. La idea es entrenar un modelo para obtener el mismo pronóstico utilizando los mismos datos de entrada pero en un tiempo bastante corto y con la misma precisión. En un trabajo futuro se podria aplicar tambien algun tipo de corrección utilizando mediciones reales de las diferentes estaciones del pais.

### ¿Cómo funciona el modelo WRF?

<img src="https://github.com/danielmc81/temp_forecast/blob/b0b423c8c2df9e64331e30764a451380b432882d/imagenes/wrf-flow.jpg" width=600 alt="hola">
https://www.j-kosham.or.kr/journal/view.php?doi=10.9798/KOSHAM.2018.18.2.445 




