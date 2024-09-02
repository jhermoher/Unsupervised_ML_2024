METODOLOGIA:
La metodolog’a propuesta para acometer el proyecto se resume a continuaci—n:

5.1 Exploraci—n y Preprocesamiento de los Datos:
Mediante un an‡lisis descriptivo de los datos, obtener previamente caracter’sticas que permitan su comprensi—n y que puedan afectar su modelamiento y los resultados. Por ejemplo, la presencia de datos faltantes, el desbalance de las clases, el rango de los valores, entre otros. 

Respecto a preprocesamiento, estandarizar las variables requeridas, determinar el nœmero de componentes de acuerdo con un porcentaje de varianza explicada, eliminar duplicaciones, balancear las clases, entre otros, que puedan aplicar para acondicionar los datos como prerrequisito para la implementaci—n de los modelos.

5.2 Implementaci—n de los Modelos:
Para la detecci—n de anomal’as se escogieron preliminarmente, dos algoritmos de
aprendizaje no supervisado: ISOLATION FOREST y ONE CLASS SVM.

El primero, se basa en el principio de que las anomal’as son pocas y diferenciables, haciŽndolas f‡ciles de identificar y aislar de las observaciones normales. Tiene ventajas al ser computacionalmente eficiente en bases de datos con una gran cantidad de dimensiones al no basarse en mŽtricas de distancias o densidades. Una desventaja, es la selecci—n adecuada del Par‡metro de Contaminaci—n para un modelo de predicci—n efectivo.

El segundo, se basa en el aprendizaje de una frontera de decisi—n hiperesfŽrica que determina como anomal’a las observaciones que se ubican fuera de ella. Al igual que el algoritmo ISOLATION FOREST, es eficiente en bases de datos con una gran cantidad de dimensiones, sin embargo, es exigente computacionalmente en bases de datos con numerosas observaciones, adem‡s de que su efectividad est‡ supeditada a selecci—n adecuada del kernel y sus par‡metros.

5.3 Comparaci—n del Desempe–o de los Modelos:
Para la comparaci—n de los modelos, o la determinaci—n de un modelo conjunto, se determinan previamente las mŽtricas adecuadas como PRECISION, RECALL, o F1-SCORE para medir el desempe–o de estos. El an‡lisis de las mŽtricas junto con la curva ROC y el valor AUC ser‡n usadas para medir el desempe–o de los modelos.

5.4 Evaluaci—n de los Modelos:
La evaluaci—n de los modelos se determinar‡ calculando el impacto financiero de
predicciones incorrectas como el costo de falsos positivos (transacciones leg’timas
consideradas como fraude).

5.5 Visualizaci—n de las Anomal’as:
Los resultados se acondicionaron para su visualizaci—n apropiada mediante la reducci—n de las dimensiones, por ejemplo, t-SNE, PCA, etc. en gr‡ficas bidimensionales o tridimensionales.
