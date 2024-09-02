### METODOLOGIA:
La metodología propuesta para acometer el proyecto se resume a continuación:

5.1 Exploración y Preprocesamiento de los Datos:
Mediante un análisis descriptivo de los datos, obtener previamente características que permitan su comprensión y que puedan afectar su modelamiento y los resultados. Por ejemplo, la presencia de datos faltantes, el desbalance de las clases, el rango de los valores, entre otros. 

Respecto a preprocesamiento, estandarizar las variables requeridas, determinar el número de componentes de acuerdo con un porcentaje de varianza explicada, eliminar duplicaciones, balancear las clases, entre otros, que puedan aplicar para acondicionar los datos como prerrequisito para la implementación de los modelos.

5.2 Implementación de los Modelos:
Para la detección de anomal’as se escogieron preliminarmente, dos algoritmos de aprendizaje no supervisado: ISOLATION FOREST y ONE CLASS SVM.

El primero, se basa en el principio de que las anomalías son pocas y diferenciables, haciéndolas fáciles de identificar y aislar de las observaciones normales. Tiene ventajas al ser computacionalmente eficiente en bases de datos con una gran cantidad de dimensiones al no basarse en métricas de distancias o densidades. Una desventaja, es la selección adecuada del Parámetro de Contaminación para un modelo de predicción efectivo.

El segundo, se basa en el aprendizaje de una frontera de decisión hiperesférica que determina como anomalía las observaciones que se ubican fuera de ella. Al igual que el algoritmo ISOLATION FOREST, es eficiente en bases de datos con una gran cantidad de dimensiones, sin embargo, es exigente computacionalmente en bases de datos con numerosas observaciones, adem‡s de que su efectividad está supeditada a selección adecuada del kernel y sus par‡metros.

5.3 Comparación del Desempeño de los Modelos:
Para la comparaci—n de los modelos, o la determinación de un modelo conjunto, se determinan previamente las métricas adecuadas como PRECISION, RECALL, o F1-SCORE para medir el desempeño de estos. El análisis de las métricas junto con la curva ROC y el valor AUC ser‡n usadas para medir el desempeño de los modelos.

5.4 Evaluación de los Modelos:
La evaluación de los modelos se determinar‡ calculando el impacto financiero de predicciones incorrectas como el costo de falsos positivos (transacciones legítimas consideradas como fraude).

5.5 Visualización de las Anomalías:
Los resultados se acondicionaron para su visualización apropiada mediante la reducci—n de las dimensiones, por ejemplo, t-SNE, PCA, etc. en gráficas bidimensionales o tridimensionales.
