# Unsupervised_ML_2024
## DETECCIÓN DE ANOMALIAS EN TRANSACCIONES DE TARJETAS DE CRÉDITO


### RESUMEN
Este proyecto hace uso de algoritmos de Aprendizaje de Máquina No Supervisado para la detección de anomalías en transacciones con tarjetas de crédito. Mediante la detección de patrones inusuales, se pretende identificar actividades que potencialmente estén relacionadas con fraude financiero.


### TABLA DE CONTENIDO
- [DATOS](#datos)
- [METODOLOGÍA](#metodología)
- [RESULTADOS](#resultados)


### DATOS
La fuente de los datos usada en este proyecto se encuentra disponible en $https://www.openml.org/d/1597$.  

Créditos:
**Andrea Dal Pozzolo, Olivier Caelen, Reid A. Johnson and Gianluca Bontempi**. Calibrating Probability with Undersampling for Unbalanced Classification. In Symposium on Computational Intelligence and Data Mining (CIDM), IEEE, 2015

La base de datos para el entrenamiento de los modelos contiene transacciones realizadas por medio de tarjetas de crédito en Septiembre de 2013 por titulares europeos. Las transacciones fueron registradas durante dos (2) días, con un resultado de 492 fraudes de un total de 284,807 transacciones. La base de datos es extremadamente desbalanceada con fraudes positivos (Clase 1) que representan tan solo un 0.172% de todos las transacciones registradas.

Para más detalles, refiérase al archivo ```data/README.md```


### METODOLOGÍA
El proyecto utiliza los siguientes algoritmos de Aprendizaje de Máquina No Supervisado para el modelo de detección de anomalías:
- Isolation Forest
- One-Class SVM

Para más detalles, refiérase al archivo ```submittals/propuesta_inicial.pdf```.


### RESULTADOS
El modelo logró una detección de anomalias del #% con un porcentaje de falsos positivos de tan solo #%. El impacto en el 

Los resultados de proyecto se pueden consultar en el archivo ```notebooks/resultados.ipynb```.
