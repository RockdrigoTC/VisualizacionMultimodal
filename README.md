## Desarrollo de métodos de visualización para análisis de información multimodal

Este repositorio contiene el código y los recursos utilizados en el proyecto de investigación "Desarrollo de métodos de visualización para análisis de información multimodal". A continuación, se proporciona una breve descripción de los componentes y herramientas utilizadas en este proyecto.

### Contenido del Repositorio

1. **Código del Colab**: El archivo `Vizualizacion_Contenido_Multimodal.ipynb` es un cuaderno de colab que contiene el código utilizado para realizar el análisis y la visualización de datos multimodales. Este cuaderno se ejecutó en el entorno de Google Colab y contiene las etapas del proyecto.

2. **Reporte Técnico**: Este informe proporciona una descripción de los métodos utilizados, los resultados obtenidos y las conclusiones del proyecto.

3. **Características Extraídas de los Videos**: Los archivos de características de los videos se almacenan en el directorio `Caracteristicas/`. Estos archivos contienen las características extraídas de los videos, incluidos los datos RGB, Flow y Speech.

### Herramientas y Modelos Utilizados

El proyecto hace uso de varias herramientas y modelos para el análisis y la visualización de datos multimodales:

- **Google Colab**: El entorno de Google Colab se utiliza para ejecutar el código y realizar análisis interactivos.

- **Python**: El lenguaje de programación principal utilizado para el análisis de datos y la implementación de algoritmos.

- **Librerías de Python**: Varias librerías de Python se utilizan para el análisis de datos, incluyendo numpy, pandas, matplotlib, sklearn, y más.

- **K-Means Clustering**: El algoritmo de clustering K-Means se utiliza para agrupar características de videos en clústeres con el fin de identificar patrones y similitudes en los datos.

- **t-SNE (t-distributed Stochastic Neighbor Embedding)**: Se aplica t-SNE para reducir la dimensionalidad de las características y visualizar los clústeres en un espacio bidimensional.

- **Anaconda y Miniconda**: Se utiliza Anaconda y Miniconda para gestionar el entorno de Python y las dependencias del proyecto.

- **VGGish**: Es un modelo que transforma señales de audio, tales como las provenientes de un flujo de video, en representaciones numéricas que capturan atributos acústicos significativos.

- **I3D (Inflated 3D Convnet)**: Es un modelo el cual ha sido pre-entrenado en conjuntos de datos visuales de gran envergadura. El propósito principal de I3D es discernir información relevante de los fotogramas de video, incluyendo la detección de objetos, movimiento y atributos visuales diversos. 
