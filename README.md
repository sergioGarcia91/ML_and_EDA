#  Machine Learning y Análisis Exploratorio de Datos

Este repositorio contiene una colección de Notebooks desarrollados en [Google Colaboratory](https://colab.research.google.com). El propósito de estos Notebooks es ser una ayuda en el proceso de aprendizaje de Machine Learning (ML) y el Análisis Exploratorio de Datos (EDA, por sus siglas en ingles), en el lenguaje de programación de Python 3. 

>**Observación 01.** Los Notebooks estan organizados en una secuencia preliminar de trabajo. En general, encontrará que el conjunto de datos original se carga con un procesamiento simple. Por lo que los resultados no serían los óptimos o deseables en algunas ocasiones. Como parte de su proceso de aprendizaje, se sugiere replicar los procedimientos aplicados en los diferentes Notebooks para un único conjunto de datos ya ajustado o filtrado después de realizar el Análisis Exploratorio de Datos (EDA). Esto permitirá obtener un análisis más completo y detallado.

>**Observación 02:** El hecho de que el mismo valor de `random_state` no genere consistentemente el mismo modelo en ejecuciones múltiples podría atribuirse a diversas causas, como posibles cambios en los datos entre ejecuciones, actualizaciones en la biblioteca de aprendizaje automático, variaciones en el entorno de ejecución o sistema operativo. Más información: https://github.com/lmcinnes/umap/issues/153

## Objetivo

Proporcionar conocimientos básicos en ML y EDA. En el futuro, espero poder ofrecer Notebooks más avanzados.

## Características
- **Entorno:** Todos los Notebooks están diseñados para ejecutarse en Google Colab, un entorno basado en la nube que permite escribir y ejecutar código de Python de manera interactiva.

- **Estructura:** Los Notebooks están organizados secuencialmente. Algunos temas previamente abordados pueden no ser explicados o replicados nuevamente, por lo que puede repasar los Notebooks o hacer una consulta rápida en las respectivas librerías.

- **Código Comentado:** El código en los Notebooks está comentado en las partes necesarias, omitiendo algunas líneas en ocasiones para que usted llegue a sus propias conclusiones.


## Contenido actual:

Al hacer clic en el icono ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) ubicado al inicio del Notebook, se abrirá el Notebook en Google Colaboratory.

1. [01a_Sismos_EDA](https://github.com/sergioGarcia91/ML_and_EDA/blob/161ec77e98c36a8c34eb48343e1cad2d82e683ed/01a_Sismos_EDA.ipynb): Notebook introductorio al EDA para el Dataset de Sismos
2. [01b_Sismos_RegresionLineal](https://github.com/sergioGarcia91/ML_and_EDA/blob/ef1458fdae610ac1961d61f5cd55f956ddfa2db1/01b_Sismos_RegresionLineal.ipynb): Notebook donde se genera un modelo de regresión lineal simple y regresión lineal múltiple para el Dataset de Sismos
3. [01c_Sismos_DBSCAN](https://github.com/sergioGarcia91/ML_and_EDA/blob/c0059ec22d87e4f2dbc2689eaeade5e7ebc520c9/01c_Sismos_DBSCAN.ipynb): Notebook de clusterización utilizando el algoritmo DBSCAN para el catálogo sísmico.
4. [01d_Sismos_KMeans](https://github.com/sergioGarcia91/ML_and_EDA/blob/c0059ec22d87e4f2dbc2689eaeade5e7ebc520c9/01d_Sismos_KMeans.ipynb): Notebook de clusterización utilizando el algoritmo K-Means para el catálogo sísmico.
5. [02a_GeologiaMesa_MLPClassifier](https://github.com/sergioGarcia91/ML_and_EDA/blob/39b1d5e8f4a7052caeadf86da1ab4fe5424d8279/02a_GeologiaMesa_MLPClassifier.ipynb): Notebook de clasificación supervisada utilizando el Multi-layer Perceptron Classifier para el modelo geológico de la Mesa de Los Santos.
6. [03a_Precipitacion_RegresionLogistica](https://github.com/sergioGarcia91/ML_and_EDA/blob/ce7698d0c39bacf6c74bd5b0291a963e552a3084/03a_Precipitacion_RegresionLogistica.ipynb): Notebook para la predicción de probabilidades de lluvia en Bucaramanga (año 2020) mediante Logistic Regression.
7. [04a_PlugsMesa_MLPRegressor](https://github.com/sergioGarcia91/ML_and_EDA/blob/ae548e4471d7f3bbf7bc6372bb3194108516b06d/04a_PlugsMesa_MLPRegressor.ipynb): Notebook para la estimación de los valores de porosidad de las rocas aflorantes en la Mesa de Los Santos mediante el uso del Multi-layer Perceptron Regressor.
8. [04b_PlugsMesa_Bootstrapping](https://github.com/sergioGarcia91/ML_and_EDA/blob/ef138d6f158cca57187d83a9fd540236928880c1/04b_PlugsMesa_Bootstrapping.ipynb): Notebook sencillo del uso del Bootstrapping o remuestreo para los valores de porosidad del miembro superior de la Formación Los Santos, aflorante en la Mesa de Los Santos.
9. [05a_Fracturas_DecisionTreeRegressor](https://github.com/sergioGarcia91/ML_and_EDA/blob/17122fbf6896a27db109916a4480ff7b3a83337c/05a_Fracturas_DecisionTreeRegressor.ipynb): Notebook para predecir la orientación de las fracturas en la Mesa de Los Santos utilizando el algoritmo Decision Tree Regressor.
10. [06a_TREs_KNeighborsClassifier](https://github.com/sergioGarcia91/ML_and_EDA/blob/7bc79c9fc8a45744e8fb4222e9e7d87f1d168f4d/06a_TREs_KNeighborsClassifier.ipynb): Notebook de clasificación supervisada utilizando el K Neighbors Classifier para segmentar en categorías discretas los valores de resistividad eléctrica en siete Tomografías de Resistividad Eléctrica (TRE).
11. [07a_YOLOv8_Amonites_20240323](https://github.com/sergioGarcia91/ML_and_EDA/blob/4081aacb63afe9fe88db9c1beeb047cb519f9813/07a_YOLOv8_Amonites_20240323.ipynb): Notebook de detección de Amonites reentrenando una CNN correspondiente a YOLOv8.
12. [08a_MinimoLocal_MinimoGlobal](https://github.com/sergioGarcia91/ML_and_EDA/blob/f9e4c22888d4fe3a0e7a2aaa58bc0ba2549ebffa/08a_MinimoLocal_MinimoGlobal.ipynb): Notebook introductorio para entender el descenso del gradiente.
13. [09a_Afloramiento_MapaVariografico](https://github.com/sergioGarcia91/ML_and_EDA/blob/4cd584a79e00b0972ecae793dc64fa1d79876d12/09a_Afloramiento_MapaVariografico.ipynb): Notebook para entender qué es la semivarianza utilizando el mapa variográfico en una imagen de afloramiento.
14. ***En desarrollo ...*** :hourglass:

## Contribuciones

¡Las contribuciones y sugerencias son bienvenidas! Si encuentras errores o tienes ideas para mejorar los Notebooks, no dudes en informarlo. ¡Agradezco su colaboración!

¡Feliz aprendizaje de Machine Learnign :robot: y Exploratory Data Analysis :chart_with_upwards_trend:!
