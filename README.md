# Clasificación de Planes de Megaline

---

## 📖 Descripción del Proyecto
Este proyecto tiene como objetivo desarrollar un modelo predictivo que recomiende uno de los planes nuevos de Megaline (**Smart** o **Ultra**) basado en el comportamiento mensual de los clientes. Utilizando técnicas de aprendizaje automático, se analizó información sobre llamadas, mensajes y uso de Internet para optimizar la asignación de planes y aumentar la satisfacción del cliente. Este proyecto se realizo con TripleTen.

---

## 💻 Funcionalidades
- **Limpieza y Preparación de Datos**: Procesamiento de datos y segmentación en conjuntos de entrenamiento, validación y prueba.
- **Modelos Predictivos**: Implementación de tres modelos de clasificación:
  - DecisionTreeClassifier
  - RandomForestClassifier
  - LogisticRegression
- **Optimización de Hiperparámetros**: Ajuste de parámetros para maximizar la exactitud del modelo de bosque aleatorio (RandomForestClassifier).

---

## 🛠 Tecnologías Utilizadas
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📊 Resultados
- **Mejor Modelo**: RandomForestClassifier
  - Hiperparámetros óptimos: `n_estimators: 200`, `max_depth: 30`, `min_samples_split: 2`.
  - Exactitud del modelo en conjunto de prueba: **80%**.
- El modelo superó el umbral requerido del **75%**, demostrando ser confiable para recomendaciones automatizadas.

---

## ✨ Conclusiones
- **Impacto del Proyecto**:  
  Este modelo puede transformar cómo Megaline gestiona sus planes, optimizando la asignación de productos y personalizando la experiencia del cliente. Al automatizar la recomendación de planes, la empresa puede reducir costos operativos y aumentar la retención de clientes.

- **Simplicidad y Escalabilidad**:  
  Aunque este modelo fue diseñado con un dataset limitado, puede escalarse fácilmente incorporando más variables, como datos demográficos o históricos de consumo.

- **Beneficios Clave**:  
  La adopción de este modelo no solo mejora la toma de decisiones internas, sino que también fortalece la relación entre la empresa y sus clientes al garantizar que cada usuario reciba un plan acorde a su comportamiento.

---
