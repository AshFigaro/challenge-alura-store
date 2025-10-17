<h1>Challenge Alura Store</h1>

- <h2>Objetivo del Proyecto<h2>

El propósito de este proyecto es realizar un análisis cuantitativo del rendimiento de cuatro tiendas de Alura Store para determinar cuál de ellas debe ser vendida. El informe final se basa en una justificación rigurosa utilizando métricas clave de ingresos, satisfacción del cliente y eficiencia operativa.

- <h2>Análisis y Hallazgos Clave<h2>

El análisis se centró en la consolidación y limpieza de datos de las cuatro tiendas, seguido del cálculo y la visualización de cinco métricas fundamentales para la toma de decisiones.

- <h3>Conclusión Ejecutiva<h3>

Basado en la evaluación integral, se recomienda la venta de la Tienda 4. Esta tienda presenta el peor rendimiento financiero (Ingreso Total más bajo) y la peor Calificación Promedio de clientes, lo que indica un problema sistémico de baja calidad y escasa demanda.

- <h3>Métricas Clave<h3>

1. Ingreso Total: Se calculó la suma de ingresos por tienda, estableciendo la Tienda 4 como la de menor rendimiento, con $[1.03]$ mil millones.

2. Calificación Promedio (Satisfacción del Cliente): Se calculó el promedio de la columna Calificación. La Tienda 4 consistentemente presenta el promedio más bajo ($[3.96]$ vs. $[4.01]$ en la más alta).

3. Composición de Ventas: Se identificó el Top 5 de productos más y menos vendidos en cada tienda, permitiendo analizar el inventario estancado de la Tienda 4.

4. Costo de Envío: Se calculó el promedio del costo de envío. Este dato refuta la causa de las bajas ventas, ya que la Tienda 4 resultó ser la más eficiente logísticamente (costo de envío más bajo, $[23,459]$).

- <h2>Visualizaciones Clave<h2>

Se generaron tres gráficos esenciales para comunicar los insights al equipo ejecutivo, enfocándose en la comparación directa entre las cuatro tiendas:

1. Gráfico de Barras Verticales: Muestra el Ingreso Total de cada tienda, haciendo visualmente evidente el rezago de la Tienda 4.

2. Gráfico de Barras Horizontales: Compara la Calificación Promedio, resaltando la peor experiencia del cliente de la Tienda 4.

3. Gráfico de Pastel (Pie Chart): Detalla la composición de las ventas por categoría solo para la Tienda 4, para entender en qué se está vendiendo su limitado volumen.

- <h2>Estructura y Tecnologías<h2>

El proyecto se desarrolló siguiendo el flujo de trabajo estándar de análisis de datos:

1. Consolidación de Datos: Unificación de los 4 archivos CSV individuales en un único DataFrame principal.

2. Limpieza de Datos: Estandarización de formatos (eliminar $, ,, notación científica) y corrección del ID_Tienda faltante en el dataset inicial.

- <h2>Tecnologías Utilizadas<h2>

1. Python: Lenguaje principal de análisis.

2. Pandas: Para la limpieza, manipulación de datos (uso intensivo de groupby() y sort_values()) y el cálculo de métricas.

3. Matplotlib: Para la generación de visualizaciones.

- <h2>Posibles Mejoras<h2>

1. Análisis de Rentabilidad: Incluir una columna de costo del producto para calcular el margen de ganancia real por tienda, no solo los ingresos brutos.

2. Predicción de Churn: Utilizar modelos para predecir qué clientes tienen mayor probabilidad de dejar la tienda basándose en la calificación y el producto comprado.

3. Panel Interactivo: Crear un dashboard interactivo con herramientas como Plotly o Tableau para explorar los datos dinámicamente.
