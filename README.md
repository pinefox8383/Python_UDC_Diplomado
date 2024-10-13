# Modulo 7 - Caso Práctico Python

Análisis de la Tasa de Mortalidad de Adultos 2019-2021

Repositorio auxiliar de archivos del proyecto en Google Drive

https://drive.google.com/drive/folders/1vx1ERxeEpqyxxXN5_NLXCJpFrSQc9KKN?usp=drive_link


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



### Análisis Exploratorio
Histográma de todas las columnas numéricas
![image](https://github.com/user-attachments/assets/28c275c8-a333-41af-92d0-1a3c0a26703b)

Gráfico scatterplot  entre la variabe Objetivo: Tasa de Mortalidad y la Variable factror Inversión en Salu
![image](https://github.com/user-attachments/assets/16245e03-4a8a-4aef-a372-bdf527f6402e)

Gráficos de dispersión entre todas las columnas y distribuciones
![image](https://github.com/user-attachments/assets/bc96fda3-71a8-46d8-8552-a73d1b7ad6c6)

Estadística de los datos
![image](https://github.com/user-attachments/assets/611d2d95-7b49-4c4d-bf74-9c8b72b70c4f)




### Resultados de la Evaluación del Modelo
![image](https://github.com/user-attachments/assets/888a87f7-8c21-4416-b05b-62e91c7f0708)

### Visualización de Resultados
Graficando Dispersión de la Predicción
![image](https://github.com/user-attachments/assets/aa759502-7b82-4363-b20b-a77976b727c3)

Graficando en Barras la Predicción
![image](https://github.com/user-attachments/assets/03f6dbcc-edd3-466b-9d92-fc575441af00)

Comparativo de los datos de prueba con los datos de la predicción
![image](https://github.com/user-attachments/assets/fc61e219-11d7-4d14-b065-ccb9c2c6fec4)






