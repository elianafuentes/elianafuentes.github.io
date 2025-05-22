# Predicción del Precio de Bitcoin con Modelos de Machine Learning

Este proyecto tiene como objetivo desarrollar un sistema de predicción para la variación del precio del Bitcoin utilizando técnicas avanzadas de aprendizaje automático aplicadas a series temporales financieras.

A partir de una base de datos histórica con resolución de 15 minutos, se aplicaron transformaciones temporales relevantes, se diseñaron pliegues de validación cruzada tipo rolling window, y se evaluaron múltiples modelos de regresión.

Los algoritmos analizados incluyen regresiones lineales regularizadas (Ridge y Lasso), árboles de decisión (Random Forest y XGBoost), métodos basados en similitud (KNN), máquinas de soporte vectorial (SVR), y un modelo ensemble optimizado que combina las fortalezas de varios enfoques.

Cada modelo fue evaluado con métricas estándar como RMSE, MAE, SMAPE y R², además de pruebas estadísticas sobre los residuos (Ljung-Box y Jarque-Bera) para validar su comportamiento.

El modelo final propuesto —un ensemble de Ridge, Random Forest y XGBoost— logra un equilibrio entre precisión y robustez, demostrando su potencial para generalizar en escenarios de alta volatilidad como el mercado de criptomonedas.


