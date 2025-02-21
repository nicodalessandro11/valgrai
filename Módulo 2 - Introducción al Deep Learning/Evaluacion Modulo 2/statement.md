# 📝 Evaluacion del Modulo 2 - "IA para profesionales TIC – 3ª edición"

## 📝 Statement

### 🎯 Objetivo

El objetivo de este ejercicio es construir y entrenar una red neuronal convolucional (CNN) para clasificar imágenes de rostros humanos según las emociones que muestran. Los estudiantes aprenderán a trabajar con un dataset de imágenes, a construir y entrenar un modelo de CNN utilizando TensorFlow y Keras, y a evaluar su desempeño.

Podéis hacer uso de ChatGPT, Gemini, Github Copilot o cualquier otra herramienta, con un uso adecuado y siempre entendiendo lo que hacéis, y lo que el código hace.

Descripción del Ejercicio

En este ejercicio, utilizarás el dataset FER-2013 (Facial Expression Recognition) disponible en Kaggle. Este dataset contiene imágenes de rostros etiquetados con diferentes emociones (felicidad, tristeza, enojo, sorpresa, etc.). Tu tarea es entrenar una CNN para clasificar las imágenes de rostros en las categorías de emoción correctas.

### 🪜 Pasos a Seguir

#### 1. Preparación del Entorno:

- Abre un nuevo notebook en Google Colab.
- Asegúrate de tener instaladas las bibliotecas necesarias: TensorFlow, Keras, y otras bibliotecas auxiliares.

#### 2. Carga y Exploración del Dataset:

- Descarga el dataset FER-2013 desde Kaggle.
- Carga el dataset en tu notebook y explora las imágenes y sus etiquetas.

#### 3.Preprocesamiento de Datos:

- Realiza el preprocesamiento necesario de las imágenes, como el cambio de tamaño, la normalización y la división en conjuntos de entrenamiento y validación.

#### 4.Construcción del Modelo:

- Define una arquitectura de red neuronal convolucional utilizando Keras. Puedes empezar con una arquitectura simple y luego experimentar con arquitecturas más complejas.
- Compila el modelo especificando el optimizador, la función de pérdida y las métricas de evaluación.

#### 5. Entrenamiento del Modelo:

- Entrena tu modelo con el conjunto de entrenamiento.
- Evalúa el desempeño del modelo en el conjunto de validación.

#### 6. Evaluación y Mejora:

- Analiza los resultados y ajusta la arquitectura y los hiperparámetros del modelo para mejorar su precisión.
- Realiza predicciones sobre nuevas imágenes de rostros, busca rostros y ajústalos a lo que pide el modelo, y verifica su exactitud.

#### 7. Desafío Extra:

- Crear una visualización interactiva que muestre las emociones detectadas en tiempo real usando la webcam del ordenador (Google Colab, si buscáis, lo permite).

#### 8. A entregar en un .zip con vuestro nombre:

- Documenta todo el proceso en el notebook.
- Incluye gráficos de precisión y pérdida durante el entrenamiento.
- Muestra ejemplos de imágenes correctamente clasificadas y mal clasificadas.
- Comenta sobre los resultados obtenidos y las posibles mejoras o lo que consideres en un PDF.

### 🧪 Evaluación

La evaluación se basará en:

- La correcta implementación del modelo de CNN.
- La claridad y detalle en la documentación del proceso.
- La precisión del modelo en el conjunto de validación.
- La creatividad en la mejora del modelo y en el uso de técnicas de aumento de datos.
