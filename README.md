# Netflix Data Analysis – Exploratory Data Analysis (EDA)

Este proyecto es un análisis exploratorio de un dataset público que contiene información sobre el catálogo de Netflix. Fue realizado como práctica para reforzar habilidades aprendidas en la carrera de Data Science de Henry.

## Dataset

El dataset contiene 8807 registros y 12 columnas con información sobre:

-Tipo de contenido (Movie / TV Show)
-Título
-Director y reparto
-País de origen
-Fecha en que se agregó a Netflix
-Año de lanzamiento
-Rating
-Duración
-Géneros
-Descripción

## Tecnologías utilizadas

-Python
-Pandas
-Matplotlib / Seaborn
-Jupyter Notebook

## 1. Limpieza y preparación de datos

Conversión correcta de la columna date_added a formato datetime.
Extracción de added_year para análisis temporal.
Separación y conteo de géneros en listed_in.
Manejo de valores nulos.
Normalización de columnas tipo string.

## 2. Análisis exploratorio
### Distribución por años de lanzamiento

El catálogo contiene títulos desde 1925 hasta 2021, con un crecimiento marcado a partir de los 2000 y un pico alrededor de 2018–2020.

### Movies vs TV Shows

Movies: 6131
TV Shows: 2676

- El catálogo se compone mayormente de películas.

### Top 10 géneros

Los géneros más frecuentes incluyen:

International Movies
Dramas
Comedies
International TV Shows
Documentaries

### Top países productores

Los países con más contenido en Netflix son:

Estados Unidos
India
Reino Unido
Canadá
Francia
(entre otros)

### Títulos agregados por año

Se observa un crecimiento significativo entre 2015 y 2019, coincidiendo con la expansión global de la plataforma.

## 3. Conclusiones

- Netflix tiene un catálogo predominantemente moderno, con fuerte crecimiento de títulos recientes.
- El contenido proviene de una gran variedad de países, demostrando la vocación global de la plataforma.
- Las películas superan ampliamente a las series, reflejando estrategias de adquisición previas al auge de producciones originales.
- Los géneros más populares indican un enfoque en contenidos internacionales, dramas y comedias, complementado por documentales y producciones independientes.

## 4. Próximos pasos

- Opcionalmente, el proyecto podría ampliarse con:
- Modelos predictivos (por ejemplo, predicción de popularidad por género/país).
- Sistema de recomendación simple basado en contenido.
- Dashboard interactivo (Streamlit o Power BI).

## Autor

Proyecto realizado por Malena Sosa como práctica de Data Science.





