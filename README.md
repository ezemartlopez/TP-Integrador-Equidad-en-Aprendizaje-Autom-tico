# TP-Integrador-Equidad-en-Aprendizaje-Automatico

## Enunciado

Este trabajo práctico grupal tiene como objetivo poner en práctica los conceptos vistos en la clase. La idea será trabajar sobre el conjunto de datos “German Credit Data”, que cuenta con información acerca de datos bancarios de personas y crear un modelo que prediga si una persona debe aprobarse un préstamo bancario.

La idea es generar un clasificador inicial, evaluarlo de manera agregada y también haciendo un analisis de equidad con especial foco en la asignación de creditos a personas de distintos géneros. Luego, se exploraran técnicas de mitigación de sesgos y se crearan nuevos modelos, los cuales se evaluarán y compararán con el modelo inicial.

## Pasos

### 1) Conjunto de datos

✅ Obtener el conjunto de datos desde el repositorio UCI [Dataset](https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data)

🔲 Buscar información en fuentes confiables y contestar las preguntas propuestas en el trabajo *Datasheets for Datasets* para conocer mejor el conjunto de datos:

  - 🔲 **Motivación:**  
    ¿Con qué propósito se creó el conjunto de datos? ¿Era para una tarea específica? ¿Había una brecha específica que necesitaba ser cubierta? Proporcionar una descripción.  
    ¿Quién creó el conjunto de datos (equipo, grupo de investigación) y en nombre de qué entidad?

  - 🔲 **Composición:**  
    ¿Qué representan las instancias del conjunto de datos? ¿Hay varios tipos de instancias? Proporcionar una descripción.

  - 🔲 **Proceso de recopilación:**  
    ¿Cómo se adquirieron los datos? ¿Fueron observados directamente, informados por sujetos o derivados? ¿Fueron validados o verificados?

  - 🔲 **Preprocesamiento/limpieza/etiquetado:**  
    ¿Se realizó algún preprocesamiento o limpieza? Proporcionar detalles o indicar si no aplica.

  - 🔲 **Usos:**  
    ¿Se ha utilizado el conjunto de datos para alguna tarea? ¿Existe un repositorio o sistema que lo utilice? Proporcionar enlaces si existen.

🔲 Realizar un análisis exploratorio del conjunto de datos, Por ejemplo, explorar distribución de etiquetas, edades, géneros, etc.  
🔲 Identificar posibles sesgos (por ejemplo, representación de género en préstamos aprobados).

---

### 2) Creación de un modelo inicial

🔲 Elegir un modelo clásico de clasificación (ejemplo: Random Forest o Regresión Logística).

🔲 Entrenar y evaluar el modelo usando métricas clásicas: precisión, recall, accuracy, f1-score.

🔲 Crear la matriz de confusión.

🔲 Interpretar los resultados obtenidos.

🔲 Justificar cuál error es más grave para el banco (maximizar personas que paguen el préstamo).

---

### 3) Evaluación de equidad del modelo inicial

🔲 Describir cómo se interpretan en este contexto los criterios de fairness vistos en clase:  
  - Statistical Parity  
  - Equalized Odds  
  - Equal Opportunity  
  - Predictive Parity

🔲 Analizar si el modelo inicial es fair para cada definición, usando la medida de disparidad y un umbral definido.

🔲 Justificar cuál criterio de fairness es más relevante para el banco.

---

### 4) Mitigación de sesgos

🔲 Seleccionar al menos 2 técnicas de mitigación de sesgos vistas en clase.

🔲 Entrenar el modelo ajustado con dichas técnicas.

🔲 Evaluar la performance del modelo ajustado con las métricas clásicas y matriz de confusión.

🔲 Evaluar la equidad del modelo ajustado usando las mismas métricas y criterios del paso 3.

---

### 5) Conclusiones

🔲 Comparar resultados entre el modelo original y el ajustado.

🔲 Discutir mejoras en fairness y métricas de performance.

🔲 Reflexionar sobre el impacto de estos cambios en aplicaciones reales y la importancia de la equidad en machine learning.

---

## Referencias