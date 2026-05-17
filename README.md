# PROYECTO 6 - Análisis de Ventas de Videojuegos

## Descripción del proyecto

En este proyecto se realizó un análisis exploratorio y estadístico sobre las ventas de videojuegos en distintas regiones del mundo con el objetivo de identificar patrones de éxito y detectar factores que puedan ayudar a proyectar campañas publicitarias para el año 2017.

El análisis incluye información histórica de videojuegos, plataformas, géneros, reseñas de usuarios y críticos, clasificaciones ESRB y ventas globales.

---

## Objetivo

Identificar:
- Las plataformas con mayor potencial de crecimiento
- Los géneros más rentables
- Las diferencias entre regiones
- El impacto de las reseñas en las ventas
- Tendencias útiles para campañas y estrategias comerciales

---

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

## Proceso realizado

### 1. Carga y exploración de datos
Se cargó el dataset principal de videojuegos y se revisó:
- Tipos de datos
- Valores ausentes
- Estructura general del dataset

### 2. Limpieza y transformación de datos
- Conversión de nombres de columnas a minúsculas
- Conversión de tipos de datos
- Reemplazo de valores "tbd"
- Manejo de valores ausentes
- Creación de columna `total_sales`

### 3. Análisis exploratorio
Se analizaron:
- Juegos lanzados por año
- Ventas por plataforma
- Ciclo de vida de plataformas
- Plataformas relevantes para 2017
- Distribución de ventas
- Relación entre reseñas y ventas
- Juegos multiplataforma
- Ventas por género

### 4. Perfil de usuario por región
Se compararon:
- Plataformas más populares por región
- Géneros más populares
- Clasificaciones ESRB más vendidas

Regiones analizadas:
- Norteamérica
- Europa
- Japón

### 5. Pruebas de hipótesis
Se realizaron pruebas estadísticas para comprobar:
- Diferencias de calificaciones entre Xbox One y PC
- Diferencias entre géneros Acción y Deportes

---

## Principales conclusiones

- PS4 fue la plataforma con mayor crecimiento y potencial hacia 2017.
- Los géneros Acción, Shooter y Deportes dominaron el mercado.
- Japón mostró preferencias muy distintas frente a Norteamérica y Europa.
- Las reseñas de críticos tienen mayor relación con las ventas que las reseñas de usuarios.
- Las diferencias culturales impactan directamente las ventas de videojuegos.

---

## Datasets
games.csv
