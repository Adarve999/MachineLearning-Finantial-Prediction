# Machine Learning Practice: Financial Prediction using Linear Models, KNN, and Decision Trees

## Objective

The aim of this practice is to apply the concepts learned about constructing linear models, K-Nearest Neighbors (KNN), and decision trees to a dynamic prediction problem in a financial context. The student should be able to implement these Machine Learning models in Python, including the associated metrics and other analyses.

## Approach

This practice proposes the use and analysis of a Machine Learning model and illustrates how some Machine Learning models can be used in dynamic modeling problems, contextualizing the concepts seen. The student is also expected to develop a critical vision of the model.

The problem is a dynamic prediction problem. The student should use data from the S&P500 from Yahoo Finance:

[S&P500 Historical Prices](http://finance.yahoo.com/q/hp?s=%5EGSPC+Historical+Prices)

The student should use the quotations from the first day after January 1, 2021 (for example, January 4) to February 28, 2023, or the last day of February available before that date.

Once the quotations are obtained, the student must transform them into returns (yields) by taking the difference (from the second available day) of prices and dividing it by the previous price:

From these returns, the student should construct a matrix of dependent (rt) and independent variables considering the returns of the previous five days in addition to a vector of ones (1, rt-1,….,r t-5). It is only possible to construct this matrix from the SIXTH observation of returns (or SEVENTH of prices), discarding the incomplete rows.

## Code

The code for this practice is available in this repository. We invite you to explore it and to make any questions or suggestions you may have.

## Results

The results of our practice will be presented in the form of graphs and analysis in the corresponding notebook. This will include the evaluation of the fit quality and predictive ability of our Machine Learning model.

We hope you find this practice interesting and that it helps you better understand how Machine Learning models can be applied to real prediction problems in the field of finance.

# Práctica de Aprendizaje Automático: Predicción Financiera con Modelos Lineales, KNN y Árboles de Decisión

## Objetivo

El objetivo de esta práctica es aplicar los conceptos aprendidos sobre la construcción de modelos lineales, K-Vecinos más Cercanos (KNN) y árboles de decisión a un problema de predicción dinámica en un contexto financiero. El estudiante debería ser capaz de implementar estos modelos de Aprendizaje Automático en Python, incluyendo las métricas asociadas y otros análisis.

## Planteamiento

Esta práctica propone el uso y análisis de un modelo de Aprendizaje Automático e ilustra cómo algunos modelos de Aprendizaje Automático pueden ser utilizados en problemas de modelización dinámica, contextualizando los conceptos vistos. Se espera que el alumno desarrolle una visión crítica sobre el modelo.

El problema es un problema de predicción dinámica. El alumno deberá utilizar datos del S&P500 de Yahoo Finance:

[Precios Históricos del S&P500](http://finance.yahoo.com/q/hp?s=%5EGSPC+Historical+Prices)

El alumno deberá utilizar las cotizaciones desde el primer día después del 1 de enero de 2021 (por ejemplo, el 4 de enero) hasta el 28 de febrero de 2023, o el último día de febrero disponible antes de esa fecha.

Una vez obtenidas las cotizaciones, el alumno debe transformarlas en rentabilidades tomando la diferencia (a partir del segundo día disponible) de precios y dividiéndola por el precio anterior:

A partir de estas rentabilidades, el alumno deberá construir una matriz de variables dependientes (rt) e independientes considerando las rentabilidades de los cinco días anteriores además de un vector de unos (1, rt-1,….,r t-5). Solo es posible construir esta matriz a partir de la SEXTA observación de rentabilidades (o SEPTIMA de precios), debiendo descartar las filas no completas.

## Código

El código para esta práctica está disponible en este repositorio. Te invitamos a explorarlo y a hacer cualquier pregunta o sugerencia que puedas tener.

## Resultados

Los resultados de nuestra práctica se presentarán en forma de gráficos y análisis en el notebook correspondiente. Esto incluirá la evaluación de la calidad de ajuste y la capacidad predictiva de nuestro modelo de Aprendizaje Automático.

Esperamos que esta práctica te resulte interesante y que te ayude a entender mejor cómo se pueden aplicar los modelos de Aprendizaje Automático a problemas reales de predicción en el campo financiero.
