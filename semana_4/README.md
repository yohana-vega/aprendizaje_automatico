# Clasificación con Regresión Logística

- Se creó la variable binaria **hipertensión (≥130 mmHg)** para convertir el problema en clasificación.  
- El modelo de **Regresión Logística** se entrenó correctamente y se comparó con un baseline.  
- Los resultados mostraron **accuracy alto (95%)**, pero el modelo no detecta los casos positivos por el desbalance de datos.  
- La **curva ROC (AUC = 1.0)** indica que el modelo distingue bien entre clases, aunque el umbral por defecto no clasifica positivos.  
- Según los coeficientes, los factores que más aumentan la probabilidad de hipertensión son **estrés, peso y edad**, mientras que **horas de ejercicio e ingresos** la reducen.  
