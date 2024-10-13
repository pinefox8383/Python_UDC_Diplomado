# Modulo 7 - Caso Práctico Python

Análisis de la Tasa de Mortalidad de Adultos 2019-2021


## Objetivo del Análisis

Analizar la tasa de mortalidad de adultos y la relación con distintos factores como el el PIB promedio del país y la Inversión en Salud. Realizar regresiones con un modelo XG-Boost para entrenar los datos con un 70% y predecir la Tasa Global de Mortalidad de Adultos.
Herramientas: Google Colab (Python) Librerías: seaborn, pandas, matplotlib, numpy, Scikit-learn


## Hipótesis
Se cree que debe haber una relación muy marcada entre la tasa de mortalidad promedio(Average_CDR) y el PIB_promedio del país en Millones de Dolares(Average_GDP(M$)) ?
También que debe haber una relación muy evidente entre la inversión en salud con respecto de la Tasa de Mortalidad  (Average_CDR) vs (Average_HEXP($))



## Resultados del Análisis

Respondiendo a la hipótesis planteada se logró determinar que la variable objetivo "Tasa de Mortalidad", es poco impactada por lo factores elegidos en la hipótesis como: PIB del Pais e Inversión en Salud ya que los datos registrados en el dataset realmente están muy dispersos o aleatorios.
La correlación con las otras variables es muy baja, entendiendo que cada país por cuestiones de cultura, nivel de desarrollo económico, idiosincrasia , desarrollo social es diferente en cada uno de éstos y evidentemente causaran una aleatoriedad en la Tasa de Mortalidad
Quizá se lograría un resultado más certero haciendo predicciones de la tasa de mortalidad, con registros del mismo país durante varios años para poder tener una correlación con más impacto entre las otras variables factores.





