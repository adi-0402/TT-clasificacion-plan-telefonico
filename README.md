# Clasificación de Planes de Megaline
![GitHub](https://img.shields.io/badge/GitHub-Repository-lightgrey)
![Estado](https://img.shields.io/badge/Estado-Terminado-brightgreen)

## 📖 Descripción del Proyecto
El objetivo de este proyecto es desarrollar un modelo de clasificación que ayude a una compañía móvil a recomendar uno de sus planes nuevos (Smart o Ultra) basado en el comportamiento del cliente. Los datos utilizados incluyen información mensual de los suscriptores sobre el uso de llamadas, mensajes y tráfico de Internet. Este proyecto se realizo con Tripleten.

## 💻 Funcionalidades
- `Limpieza y Preparación de Datos`: Procesamiento y segmentación de los datos en conjuntos de entrenamiento, validación y prueba.
- `Modelos de Clasificación`: Se implementaron tres modelos de aprendizaje automático: DecisionTreeClassifier, RandomForestClassifier y LogisticRegression.
- `Optimización de Hiperparámetros`: Se iteró sobre diferentes hiperparámetros (n_estimators, max_depth, min_samples_split) para mejorar el desempeño de RandomForestClassifier.

## 🛠 Tecnologías Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## ✨ Conclusiones
- `Segmentación de Datos`: Los datos de comportamiento de los usuarios se dividieron en un 60% para el entrenamiento, 20% para la validación y 20% para la prueba.
- `Evaluación de Modelos`: Se evaluaron tres modelos de clasificación, siendo el **RandomForestClassifier** el que presentó mejor desempeño.
- `Optimización y Mejora`: El mejor modelo resultó con los siguientes hiperparámetros: n_estimators: 200, max_depth: 30, y min_samples_split: 2.
- `Desempeño del Modelo`: La exactitud del modelo alcanzó aproximadamente un **80%**, superando el umbral requerido de exactitud mínima del 75%.
