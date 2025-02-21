# Clientes-en-Riesgo-de-Cancelaci-n-de-Suscripci-n-en-una-Empresa-de-Telecomunicaciones
Modelo predictivo con el objetivo de identificar clientes que probablemente cancelen su suscripción a un servicio de telecomunicaciones.

El proyecto se centra en la detección de clientes en riesgo de cancelar su suscripción a un servicio de telecomunicaciones. Se desarrolló un modelo predictivo utilizando técnicas de aprendizaje automático para identificar patrones en los datos de clientes que podrían indicar una posible cancelación.

El código implementado incluye un análisis exploratorio detallado y un preprocesamiento robusto de los datos, utilizando múltiples modelos de clasificación como Regresión Logística, Random Forest, LGBM y Gradient Boosting. Se optimizaron los hiperparámetros mediante RandomizedSearchCV y se evaluaron los modelos utilizando métricas clave como precisión, F1 y ROC AUC.

Los resultados mostraron que la Regresión Logística fue el modelo más efectivo, alcanzando una métrica ROC AUC de 0.75 y una exactitud de 0.74 en el conjunto de prueba. Esto sugiere que el modelo tiene una buena capacidad para distinguir entre clientes que cancelan y los que no.

Se puede inferir que, aunque la Regresión Logística se destacó, otros modelos como Gradient Boosting también mostraron un rendimiento sólido, lo que indica que hay características en los datos que pueden ser capturadas eficazmente por modelos más complejos. Estos hallazgos permiten a la empresa implementar estrategias de retención más efectivas, dirigiendo esfuerzos específicos hacia los clientes en riesgo de cancelación.

Uno de los aspectos más complejos del código para mi fue la implementación de la técnica de sobremuestreo SMOTE para abordar el desbalanceo en las clases, lo que requiere un entendimiento profundo de cómo afecta a la calidad del modelo. Realizar este tipo de proyectos es emocionante porque combina análisis de datos, modelado predictivo y la oportunidad de impactar directamente en la estrategia empresarial, mejorando la retención de clientes y, en última instancia, la rentabilidad de la empresa.
