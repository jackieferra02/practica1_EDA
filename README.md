# Machine Learning

# Práctica realizada por: Jacqueline Fernández Ramírez, Jazmín Fernández Ramírez y Nina Odoux.

# Correos electrónicos:
* jazmin.fernandez@cunef.edu
* j.fernandezramirez@cunef.edu
* nina.odoux@cunef.edu

# Ruta al repositorio: https://github.com/jackieferra02/practica1_EDA.git

# Curso: Aprendizaje Automático, CUNEF Universidad.

### Proyecto

Este proyecto utiliza el aprendizaje automático para predecir el riesgo de impago de un préstamo bancario, ayudando así a los bancos a optimizar su proceso de toma de decisiones.

### *Introducción*

El conjunto de datos *Bank Account Fraud (BAF)*, publicado en NeurIPS 2022, contiene 6 conjuntos de datos sintéticos sobre fraudes en cuentas bancarias. Este proyecto tiene como objetivo usar estos datos para desarrollar un modelo predictivo que ayude a detectar solicitudes de préstamo fraudulentas. La idea es construir un sistema que permita identificar, de manera justa, a los solicitantes con riesgo de fraude sin rechazar injustamente a quienes son capaces de pagar el préstamo.

---

### *Definición del problema*

El reto principal de este proyecto es detectar y reducir el riesgo de fraude en las solicitudes de préstamos bancarios. Usando el conjunto de datos *BAF*, se busca desarrollar un modelo capaz de diferenciar entre quienes podrán pagar el préstamo y quienes podrían cometer fraude o tener problemas financieros para cumplir con sus compromisos.

El objetivo es identificar patrones que puedan indicar comportamientos fraudulentos y, a la vez, evitar que personas confiables sean rechazadas por error.

---

### *Objetivos*

Este proyecto tiene como objetivo aplicar *Análisis Exploratorio de Datos (EDA)* para comprender los patrones en el conjunto de datos *BAF*. A través de este análisis, se busca ayudar a los bancos a tomar decisiones más informadas y detectar posibles fraudes al evaluar las solicitudes de crédito.

Los pasos incluyen analizar los datos, tratar valores perdidos y atípicos, aplicar técnicas de codificación para variables categóricas y escalar las variables para mejorar el rendimiento del modelo.

*Ejecución del modelo:* El modelo se ejecutará cuando se solicite un préstamo, por lo que solo se usarán datos disponibles en ese momento.


---



- src/          # archivo de funciones útiles para el proyecto.
- data/         # datos brutos y  preprocesados (pasados al .gitignore por propositos de entrega).
- models/       # modelo elegido guardado en formato pickle.
- reports/      # conclusion general a la pregunta planteada en la practica 1 (EDA).
- env/          # librerias y dependencias del entorno (requirements.txt).
- notebooks/    # cuadernos de jupyter ordenados.



# Notebook 00: Exploración general. 
# Notebook 01: Tratamiento, correlaciones, missing y outlier.
# Notebook 02: Codificación de variables categóricas y escalado.
# Notebook 03: Variable Selección y Feature Engineering.
# Notebook 04: Evaluación de modelos, selección.
# Notebook 05: Explicabilidad.