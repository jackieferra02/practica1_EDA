# Conclusiones finales

A lo largo del análisis del conjunto de datos Bank Account Fraud (BAF) publicado en NeurIPS 2022, 
se realizaron diversos pasos detallados de análisis exploratorio de datos (EDA) 
que permitieron transformar y preparar adecuadamente los datos. Este conjunto de datos, con su estructura tabular sintética,
 proporciona una base sólida para evaluar técnicas de machine learning y ML justo, siendo esencial para investigar fraudes en cuentas bancarias.

En primer lugar, se llevó a cabo una exploración general del conjunto de datos, 
identificando las principales características y distribuciones de las variables. 
Este análisis inicial incluyó un tratamiento exhaustivo de la variable objetivo, fundamental para comprender los patrones de fraude. 
Se seleccionaron umbrales por filas y columnas para eliminar valores missing,
lo que fue crucial para limpiar el conjunto de datos y eliminar registros incompletos sin perder información relevante.

Se distinguieron las variables categóricas de las numéricas, 
permitiendo aplicar técnicas específicas de preprocesamiento. Durante esta fase, se transformaron algunas variables, 
estandarizando sus formatos y preparando el terreno para análisis más profundos. Se gestionaron adecuadamente los valores missing y los outliers, 
minimizando su impacto y asegurando la integridad del conjunto de datos. Además, se realizaron análisis de correlaciones entre variables, 
destacando relaciones significativas que podrían influir en el comportamiento de la variable objetivo.

Para las variables categóricas, se utilizaron técnicas de One-Hot Encoding y Target Encoding, transformándolas en un formato numérico adecuado 
para futuros modelos de machine learning. Paralelamente, se aplicó escalado a las variables numéricas, normalizando sus valores para que todas 
contribuyeran de manera equitativa en el modelado. Este preprocesamiento cuidadoso permitió preparar un dataset limpio y estructurado, 
listo para ser utilizado en las etapas subsecuentes del análisis.

Aunque no se aplicaron modelos predictivos en esta etapa, el EDA nos permitió llegar a importantes conclusiones preliminares. 
El análisis reveló ciertos patrones y características comunes entre los clientes que podrían estar más propensos a no devolver un préstamo. 
Estas observaciones incluyen que los clientes más propensos a no devolver un préstamo son aquellos con puntajes más bajos en la variable EXT_SOURCE_1, 
que tienden a tener un mayor riesgo de incumplimiento de pagos. Los "Cash loans" (préstamos en efectivo), que son más comunes que los "Revolving loans", 
también presentan un mayor retraso en los pagos, posiblemente debido a que estos préstamos suelen ser por montos más grandes. Además, 
los individuos con niveles de educación más bajos muestran una mayor tendencia a retrasar los pagos. Asimismo, 
aquellos que han estado empleados por menos tiempo tienen una mayor probabilidad de incumplir con sus pagos. 
Los clientes con créditos más bajos (AMT_CREDIT) y menores ingresos (AMT_INCOME_TOTAL) son más propensos a tener dificultades de pago. 
Finalmente, aquellos que viven en "Rented apartment" o "With parents" tienen una mayor probabilidad de no cumplir con sus obligaciones de pago, 
sugiriendo menor estabilidad financiera.

Lo anterior, señala que factores demográficos, tipos de ingresos y comportamientos financieros, son elementos fundamentales por analizar, 
para la construcción de modelos predictivos precisos y justos en futuras fases del proyecto.

Por último es oportuno señalar que, este análisis exploratorio ha sido clave para establecer una base sólida que posibilite 
la implementación de modelos de machine learning eficientes, orientados a la detección y prevención del fraude en cuentas bancarias. 
Consideramos que continuar con este enfoque metodológico garantizará resultados coherentes y una mejor comprensión del comportamiento 
de los clientes respecto a la devolución de préstamos.