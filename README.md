# ThePower_Proyecto_final
Proyecto final Data &amp; Analytics V3.

# 📊Análisis exploratorio de datos y dashboard de Airbnb en París
El proyecto se centra en un EDA y Dashboard de un conjunto de datos de libre elección. El proyecto final, publicado en este repositorio de GitHub, cuenta con los siguientes requisitos:
1. Dos conjuntos de datos en bruto.
2. Un conjunto de datos final sobre el que hayas hecho las transformaciones que estimes necesarias.
3. Un análisis exhaustivo del conjunto de datos final
4. Un dashboard operativo de los datos finales que aporte valor al análisis realizado.
5. Un informe del análisis realizado.
6. Archivo README.md, que recoja los pasos seguidos durante el proyecto y el informe de tú análisis. 
7. El repositorio debe contar con una buena organización y sistema de carpetas.
# 💻 Requisitos mínimos del conjunto de datos:
- Tener mínimo dos conjuntos de datos(excel, csv, bbdd de SQL) que provengan de dos fuentes distintas que se deben unir para trabajar de forma conjunta. Estos datos iniciales deberán adjuntarse en el repositorio.
- El conjunto de datos final, después de unir las dos fuentes, debe tener una extensión mínima de 50.000 filas y 20 columnas.
- Los datos que elegidos tienen que permitir cubrir los requisitos del proyecto: hacer limpieza y transformación de los mismos, hacer análisis estadísticos, hacer un dashboard que aporte valor, etc.
# 🎯 Requerimientos/Conocimientos aplicados
Este proyecto demuestra el manejo de los siguientes conceptos:
1. Transformación y limpieza de los datos
2. Análisis descriptivo de los datos
3. Análisis estadístico de los datos
4. Visualización de los datos
5. Dashboard operativo
6. Informe explicativo del análisis
# 📂 Datos utilizados
Fuente Listings: Información sobre los anuncios y sus características. Finalidad: Analizar precios, ubicación, capacidad, tipo de alojamiento y anfitriones
Fuente Review: Información relacionada con las reseñas. Finalidad: Estudiar la actividad de reseñas y su relación con las características de los alojamientos

Consideración metodológica: el análisis se refiere a los alojamientos incluidos en la muestra y con reseñas observadas. El número de reseñas se utiliza como indicador indirecto de popularidad, no como una medida directa de reservas u ocupación.

# 📦Proyecto_final
```
ThePower_Proyecto_final/
│
├── data (subidos zip a web ThePower)/
│   ├── raw/
│   │   ├── listings.xlsx
│   │   └── reviews.xlsx
│   │
│   └── processed/
│       └── listings_review_merged.xlsx
│
├── notebooks/
│   └── Proyecto_final.ipynb.ipynb
│
├── results/
│   ├── Informe_Y_Análisis explorario_Airbnb_Paris.pdf
│   └── Dashboard_Airbnb.xlsx
│
└── README.md    
```
# 🔎 Metodología de trabajo

El proyecto se desarrolla en las siguientes fases:

1. Recopilación e integración de datos
  -  Carga de los archivos originales.
  -  Revisión de la estructura y las variables disponibles.
  -  Identificación de las claves de relación entre las fuentes.
  -  Integración de los conjuntos de datos.

2. Limpieza y transformación
  - Revisión de valores ausentes y registros duplicados.
  - Corrección de tipos de datos y formatos.
  - Detección de posibles inconsistencias y valores atípicos.
  - Preparación de variables para el análisis.
  - Validación del dataset final.

3. Análisis exploratorio de datos (EDA)
  - Análisis de la estructura y calidad del conjunto de datos.
  - Estadísticos descriptivos de las variables numéricas y categóricas.
  - Distribución de precios y valoraciones.
  - Análisis de los tipos de alojamiento y su capacidad.
  - Comparación de resultados por barrio.
  - Estudio de la relación entre precios, reseñas y características de los anuncios.

4. Visualización y dashboard

5. Informes finales
   - Elaboración de un informe ejecutivo que recoge el enfoque metodológico, los resultados más relevantes, su interpretación y las limitaciones del análisis.
   - Elaboración de un análisis exploratorio. 

💡 Principales líneas de análisis

El análisis se centra en cuatro cuestiones:
  -  Precios: cómo varían según la capacidad, el número de dormitorios y el barrio.
  -  Popularidad aproximada: cómo se distribuyen las reseñas entre alojamientos y barrios.
  -  Valoraciones: qué puntuaciones presentan los anuncios.
  -  Relaciones entre variables: qué asociaciones aparecen entre precios, características de los alojamientos, reseñas y valoraciones.
Las relaciones identificadas son descriptivas y no permiten establecer causalidad. Además, el número de reseñas puede depender del tiempo de exposición del anuncio y no equivale al número de reservas.

# 🛠 Tecnologías
Excel
Python: 3.13.11
Editor: Visual Studio Code
Módulos y librerías utilizados: Pandas, NumPy, Matplotlib, Jupyter Notebook, json

# ⚠️ Limitaciones
Los resultados dependen de las fuentes, el periodo y los registros incluidos en la muestra.
- El número de reseñas no mide directamente las reservas ni la ocupación.
- Las valoraciones observadas pueden no representar a todos los alojamientos.
- Las asociaciones estadísticas son descriptivas y no demuestran relaciones causales.
- La ausencia de anuncios sin reseñas limita el análisis de la probabilidad de recibir una primera reseña.
- Información hasta 2021 y centrada solo en París. Futuros análisis recomiendan ampliar a más regiones y países con información más actualizada. 


# 👤 Autora
Teresa Hidalgo (https://github.com/hidalbaila)
