# CNN

# Proyecto de Clasificación de Dígitos en Tiempo Real

Este repositorio documenta el desarrollo de un sistema capaz de reconocer dígitos escritos a mano mediante redes neuronales convolucionales (CNN). El proyecto incluye el entrenamiento de varios modelos, su evaluación y una implementación para realizar clasificación en tiempo real usando la cámara.
Para ello se entrenaron diferentes arquitecturas CNN ajustando filtros, profundidad de red, optimizadores, tasas de aprendizaje y dropout. Después se seleccionó el modelo con mejor desempeño y se aplicó en un sistema capaz de reconocer dígitos mediante la cámara en tiempo real.

Se utilizó un dataset generado en clase de Inteligencia Artificial, dividido en conjunto de entrenamiento y prueba, compuesto por imágenes capturadas y etiquetadas por los estudiantes.


## Contenido del repositorio

### 1. Notebook de Entrenamiento (`modelos_entrenamiento.ipynb`) + Versión HTML

Incluye:

* Preparación del dataset
* Entrenamiento de múltiples modelos variando arquitecturas e hiperparámetros
* Comparación de desempeño
* Guardado de modelos y de los historiales de entrenamiento

### 2. Notebook de Clasificación en Tiempo Real (`clasificacion_tiempo_real.ipynb`) + Versión HTML

Incluye:

* Carga del modelo final
* Preprocesamiento de imágenes capturadas
* Uso de la cámara para predicciones en tiempo real

---

## Librerías necesarias

Para ejecutar los notebooks se requiere instalar o tener disponibles las siguientes librerías principales:

* **TensorFlow / Keras**
  Entrenamiento, definición y guardado de modelos.

* **NumPy**
  Manejo de arreglos y procesamiento de datos.

* **Matplotlib**
  Visualización de métricas e imágenes.

* **scikit-learn**
  Métricas de evaluación como matriz de confusión y clasificación.

* **OpenCV (cv2)**
  Captura de video desde la cámara y preprocesamiento en tiempo real.

* **Seaborn**
  Visualización avanzada (matriz de confusión, heatmaps).


