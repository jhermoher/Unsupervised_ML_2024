# Unsupervised_ML_2024
## DETECCIÓN DE ANOMALIAS EN TRANSACCIONES DE TARJETAS DE CREDITO


### RESUMEN
Este proyecto hace uso de algortimos de Aprendizaje de Máquina No Supervisado para la detección de anomalías en transacciones con tarjetas de crédito. Mediante la detección de patrones inusuales, se pretenden identificar actividades que potencialmente sean fraude financiero.


### TABLA DE CONTENIDO
- [DATOS](#datos)
- [METODOLOGÍA](#metodología)
- [RESULTADOS](#resultados)


### DATOS
La fuente de los datos usados en este proyecto se encuentra disponible en https://www.openml.org/d/1597.  

Créditos:
**Andrea Dal Pozzolo, Olivier Caelen, Reid A. Johnson and Gianluca Bontempi**. Calibrating Probability with Undersampling for Unbalanced Classification. In Symposium on Computational Intelligence and Data Mining (CIDM), IEEE, 2015

La base de datos contiene transacciones hechas por medio de tarjetas  de crédito en Septiembre de 2013 por tarjertahabientes europeos. Las transacciones fueron registradas durante dos (2) días, con un resultado de 492 fraudes de un total de 284,807 transacciones. La base de datos es extremadamente desbalanceada con fraudes positivos (Clase 1) que representan tan solo un 0.172% de todos las transacciones registradas.

Para más detalles, refiérase al archivo ```data/README.md```


### METODOLOGÍA
El proyecto hace uso de los siguientes algoritmos de Aprendizaje de Máquina No Supervisado:
- Isolation Forest
- One-Class SVM

Para mas detalles, refiérase al archivo ```submittals/propuesta_inicial.pdf```.


### RESULTADOS
_por completar_

Los resultados de projecto se pueden consultar en el archivo ```notebooks/resultados.ipynb```.
