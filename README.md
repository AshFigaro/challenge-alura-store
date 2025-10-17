<h1>Challenge Alura Store</h1>

- <h2>Objetivo del Proyecto<h2>

El propósito de este proyecto es realizar un análisis cuantitativo del rendimiento de cuatro tiendas de Alura Store para determinar cuál de ellas debe ser vendida. El informe final se basa en una justificación rigurosa utilizando métricas clave de ingresos, satisfacción del cliente y eficiencia operativa.

- <h2>Análisis y Hallazgos Clave<h2>

El análisis se centró en la consolidación y limpieza de datos de las cuatro tiendas, seguido del cálculo y la visualización de cinco métricas fundamentales para la toma de decisiones.

- <h3>Conclusión Ejecutiva<h3>

Basado en la evaluación integral, se recomienda la venta de la Tienda 4. Esta tienda presenta el peor rendimiento financiero (Ingreso Total más bajo) y la peor Calificación Promedio de clientes, lo que indica un problema sistémico de baja calidad y escasa demanda.

- <h3>Métricas Clave<h3>

<strong>1. Ingreso Total por Tienda:</strong> Se calculó la suma de ingresos por tienda, estableciendo la Tienda 4 como la de menor rendimiento, con $[1.03]$ mil millones.

<strong>2. Ventas por Categoría:</strong> Se identificaron las categorías más y menos vendidas en cada tienda, mostrando la distribución de la demanda interna.

<strong>3. Calificación Promedio (Satisfacción del Cliente):</strong> Se calculó el promedio de la columna Calificación. La Tienda 4 consistentemente presenta el promedio más bajo ($[3.96]$ vs. $[4.01]$ en la más alta).
  
<strong>4. Productos Más y Menos Vendidos:</strong> Se identificó el Top 5 y el Bottom 5 de productos por cada tienda para analizar el inventario estancado.

<strong>5. Costo de Envío Promedio:</strong> Se calculó el promedio del costo de envío por tienda. Este dato fue crucial para refutar la causa de las bajas ventas, ya que la Tienda 4 resultó ser la más eficiente logísticamente (costo promedio más bajo).

- <h2>Visualizaciones Clave<h2>

Se generaron tres gráficos esenciales para comunicar los insights al equipo ejecutivo, enfocándose en la comparación directa entre las cuatro tiendas:

<strong>1. Gráfico de Barras Verticales:</strong> Muestra el Ingreso Total de cada tienda, haciendo visualmente evidente el rezago de la Tienda 4.

<strong>2. Gráfico de Barras Horizontales:</strong> Compara la Calificación Promedio, resaltando la peor experiencia del cliente de la Tienda 4.

<strong>3. Gráfico de Pastel (Pie Chart):</strong> Detalla la composición de las ventas por categoría solo para la Tienda 4, para entender en qué se está vendiendo su limitado volumen.

- <h2>Estructura y Tecnologías<h2>

El proyecto se desarrolló siguiendo el flujo de trabajo estándar de análisis de datos:

<strong>1. Consolidación de Datos:</strong> Unificación de los 4 archivos CSV individuales en un único DataFrame principal.

<strong>2. Limpieza de Datos:</strong> Estandarización de formatos (eliminar $, ,, notación científica) y corrección del ID_Tienda faltante en el dataset inicial.

- <h2>Tecnologías Utilizadas<h2>

<strong>1. Python:</strong> Lenguaje principal de análisis.

<strong>2. Pandas:</strong> Para la limpieza, manipulación de datos (uso intensivo de groupby() y sort_values()) y el cálculo de métricas.

<strong>3. Matplotlib:</strong> Para la generación de visualizaciones.

- <h2>Contenido del Repositorio<h2>

<strong>1. base-de-datos-challenge1-latam/:</strong> Carpeta que contiene los datos en formato CSV para la consolidación inicial del proyecto.

<strong>2. AluraStoreLatam.ipynb (Notebook Principal):</strong> Contiene todo el código fuente del análisis, desde la carga y limpieza de datos hasta el cálculo de las 5 métricas, la generación de los 3 gráficos, y el informe final.

<strong>3. README.md:</strong> Documento actual que presenta la justificación, hallazgos clave, y la recomendación final del análisis.
   
<strong>4. Tabla.png:</strong> Imagen auxiliar que muestra un resumen tabular de los ingresos totales (Usado en el informe ejecutivo final).

- <h2>Posibles Mejoras<h2>

<strong>1. Análisis de Rentabilidad:</strong> Incluir una columna de costo del producto para calcular el margen de ganancia real por tienda, no solo los ingresos brutos.

<strong>2. Predicción de Churn:</strong> Utilizar modelos para predecir qué clientes tienen mayor probabilidad de dejar la tienda basándose en la calificación y el producto comprado.

<strong>3. Panel Interactivo:</strong> Crear un dashboard interactivo con herramientas como Plotly o Tableau para explorar los datos dinámicamente.
