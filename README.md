# Visualización de Datos para Consultoría de Migración Canadiense

Este cuaderno de Jupyter presenta un proyecto de consultoría enfocado en la visualización de datos de migración hacia Canadá, con un énfasis particular en clientes colombianos y otros países sudamericanos. A lo largo de este proyecto, se aplican diversas técnicas y bibliotecas de visualización de datos en Python para explorar, analizar y comunicar patrones migratorios.

## Objetivos de Aprendizaje y Temas Cubiertos:

Este curso se ha diseñado para desarrollar habilidades en visualización de datos, cubriendo los siguientes puntos:

*   **Creación de Gráficos con Matplotlib**: Dominio de la biblioteca fundamental para la creación de visualizaciones estáticas.
*   **Entendimiento de Figuras y Ejes (Matplotlib)**: Comprensión profunda de la estructura de los gráficos de Matplotlib para un control total sobre las visualizaciones.
*   **Uso de Seaborn**: Exploración de esta biblioteca para gráficos estadísticos atractivos y complejos.
*   **Creación de Gráficos Interactivos con Plotly**: Generación de visualizaciones dinámicas que permiten la exploración interactiva de los datos.
*   **Personalización de Visualizaciones**: Aplicación de diversos colores, estilos, anotaciones y otros elementos para mejorar la claridad y el impacto de los gráficos.
*   **Buenas Prácticas para la Elaboración de Gráficos**: Adhesión a principios de diseño para crear visualizaciones efectivas y comprensibles.

## Contenido del Cuaderno:

### 1. Preparación de Datos
*   Carga del conjunto de datos de inmigrantes de Canadá (`inmigrantes_canada.csv`) utilizando `pandas`.
*   Exploración inicial del DataFrame (`df.head()`, `df.shape`, `df.info()`).
*   Establecimiento de 'Pais' como índice para facilitar el acceso a los datos.
*   Extracción y preparación de datos específicos para Colombia (`datos_col`).

### 2. Visualización con Matplotlib
*   **Análisis de Inmigración Colombiana**: Creación de gráficos de línea y boxplots para visualizar la tendencia de inmigración de Colombia a Canadá entre 1980 y 2013.
*   **Personalización Avanzada**: Aplicación de estilos, colores, marcadores y ajustes de títulos/etiquetas para mejorar la estética y legibilidad de los gráficos.
*   **Gestión de Estilos**: Demostración de cómo aplicar y gestionar estilos de Matplotlib globalmente o en contextos específicos (ej. 'fivethirtyeight').
*   **Comparación de Países Sudamericanos**: Uso de `subplots` para comparar las tendencias de inmigración de Colombia, Brasil, Argentina y Perú.
*   **Gráficos de Barras**: Visualización de la inmigración total de países sudamericanos con gráficos de barras horizontales, destacando a Colombia.
*   **Exportación de Gráficos**: Guardado de visualizaciones en formatos de imagen (PNG).

### 3. Visualización con Seaborn
*   **Configuración de Tema**: Uso de `sns.set_theme()` para mejorar la apariencia general de los gráficos.
*   **Top 10 Países Migratorios**: Creación de gráficos de barras para mostrar los 10 países con mayor número de inmigrantes a Canadá, utilizando diversas paletas de colores (`Blues_r`, `rocket`, `Paired`, `tab10`).
*   **Estilos de Grilla**: Exploración de diferentes estilos de grilla de Seaborn (`darkgrid`, `whitegrid`, `white`).
*   **Comparación de Tendencias Sudamericanas**: Creación de un gráfico de línea con Seaborn para comparar las tendencias de inmigración de Colombia, Brasil, Argentina y Perú con un estilo limpio.

### 4. Visualización Interactiva con Plotly
*   **Gráficos de Línea Interactivos**: Creación de visualizaciones interactivas para la inmigración colombiana y la de todos los países sudamericanos, permitiendo al usuario explorar los datos con zoom y herramientas interactivas.
*   **Animaciones**: Desarrollo de gráficos animados para mostrar la evolución de la inmigración a lo largo del tiempo para Colombia, y una comparativa animada entre Brasil y Argentina.

### 5. Desafío Práctico
*   **Análisis de Ventas**: Resolución de un desafío de visualización para comparar las ventas mensuales de cuatro tiendas diferentes (`A`, `B`, `C`, `D`) utilizando `subplots` de Matplotlib y aplicando personalizaciones.

---
