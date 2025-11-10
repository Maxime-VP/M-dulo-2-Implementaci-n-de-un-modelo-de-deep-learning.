# Módulo-2-Implementación-de-un-modelo-de-deep-learning.
 (Portafolio Implementación)

El proyecto está dividido en tres secciones, una de extracción, una de entrenamiento y otra de predicciones. Cada una de estas carpetas incluye los archivos que se generan. Los archivos generados en la extracción se emplean tanto en la sección de entrenamiento como en la de predicciones, los modelos generados en el entrenamiento también deben emplearse para realizar las predicciones.

Mapa del github:
Módulo-2-Implementación-de-un-modelo-de-deep-learning/
│

Módulo-2-Implementación-de-un-modelo-de-deep-learning/
│
├── Entrenamiento del modelo/
│   ├── (Entrenamiento)_Módulo_2_Implementación_de_un_modelo_de_deep_learning.ipynb
│   ├── Link al colab de entrenamiento
│   └── Modelos creados/
│       ├── model_clasico.keras
│       ├── model_combinado_embed.keras
│       └── model_videojuegos_embed.keras
│
├── Extracción de datos/
│   ├── (Extracción)_Módulo_2_Implementación_de_un_modelo_de_deep_learning.ipynb
│   ├── Link al colab de extracción
│   └── Archivos generados/
│       ├── clasico_notas.npy
│       ├── clasico_notas_unicas.json
│       ├── clasico_secuencias_datos.npz
│       ├── combinado_notas.npy
│       ├── combinado_notas_unicas.json
│       ├── combinado_secuencias_datos.npz
│       ├── videojuegos_notas.npy
│       ├── videojuegos_notas_unicas.json
│       └── videojuegos_secuencias_datos.npz
│
└── Realizar Predicciones/
    ├── (Predicción)_Módulo_2_Implementación_de_un_modelo_de_deep_learning.ipynb
    ├── Link al colab de predicciones
    └── Música generada/


Cómo correr cada programa: (descargar el .pynb o acceder al link de Google Colab)

- (Extracción): solo se requiere ejecutar el código, las canciones se extraen de una biblioteca y de bitmidi.com por lo que no es necesario cargar nada manualmente.
  
- (Entrenamiento): ejecutar las primeras tres celdas para generar los directorios, cargar en /content/melody_project/data los archivos generados en (Extracción), también pueden descargar dichos archivos desde la carpeta "Archivos generados" dentro de la carpeta "Extracción de datos" del repositorio.
  
- (Predicción): ejecutar las primeras dos celdas para generar los directorios, cargar en /content/melody_project/data los archivos generados en (Extracción), en /content/melody_project/models cargar los tres modelos generados en (Entrenamiento) o descargados de la carpeta de "Modelos creados" dentro de la carpeta "Entrenamiento del modelo" del repositorio.
