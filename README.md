# AluraStoreLatam
# Proyecto de Análisis de Datos: Alura Store Latam

## Propósito del Análisis
Este proyecto tiene como objetivo principal realizar un análisis exhaustivo del rendimiento de cuatro tiendas de Alura Store Latam. A través de la exploración de diversas métricas clave, como ingresos, ventas por categoría, satisfacción del cliente, costos de envío y tendencias temporales, buscamos identificar las fortalezas y debilidades de cada tienda. El objetivo final es proporcionar una recomendación estratégica al Sr. Juan sobre cuál tienda debería considerar vender para optimizar el portafolio de negocios y maximizar la rentabilidad a largo plazo.

## Estructura del Proyecto y Organización de Archivos
- **AluraStoreLatam.ipynb**: Cuaderno principal de Jupyter con todo el código Python para la importación de datos, el análisis, la generación de gráficos y el informe final.  
- **README.md**: Archivo de documentación general (éste).  
- **data/**: Carpeta para los archivos CSV de datos:
  - `tienda_1.csv`
  - `tienda_2.csv`
  - `tienda_3.csv`
  - `tienda_4.csv`

## Ejemplos de Gráficos e Insights Obtenidos
1. **Calificación Promedio de Clientes por Tienda**  
   - Gráfico de barras con escala de 3.5 a 4.5.  
   - *Insight*: La Tienda 3 tiene la calificación más alta, mientras que la Tienda 1 muestra oportunidades de mejora.

2. **Top 3 Productos Más y Menos Vendidos por Tienda**  
   - Grid de gráficos de barras comparativos.  
   - *Insight*: Cada tienda presenta patrones de venta únicos; algunos productos de alto valor son consistentemente populares.

3. **Costo de Envío Promedio por Tienda**  
   - Gráfico de líneas para comparar eficiencia logística.  
   - *Insight*: La Tienda 4 es la más eficiente en costos de envío; la Tienda 1, la menos eficiente.

4. **Ventas Mensuales por Tienda (Enero–Marzo)**  
   - Gráfico de líneas de tendencias de ventas mensuales.  
   - *Insight*: La Tienda 1 muestra crecimiento en el primer trimestre; la Tienda 4 está por debajo del promedio.

5. **Ventas Anuales por Tienda a lo Largo del Tiempo**  
   - Gráfico de líneas de evolución de ingresos anuales.  
   - *Insight*: Todas las tiendas registran una caída en 2023, con la Tienda 4 experimentando la disminución más pronunciada.

## Conclusión Principal
Basado en el análisis de ingresos reales, satisfacción del cliente, eficiencia de costos y tendencias de ventas, se recomienda **vender la Tienda 4**. A pesar de su eficiencia en costos de envío, su bajo ingreso real y la mayor tendencia negativa en ventas la convierten en la candidata más adecuada para la desinversión, permitiendo al Sr. Juan consolidar recursos y enfocarse en las tiendas con mayor potencial de crecimiento.

## Instrucciones para Ejecutar el Notebook
1. **Clonar el repositorio**  
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio
2. **Abrir en Google Colab**  
   - Haz clic en la insignia de Colab en la parte superior de este README.md (o en la página del notebook en GitHub).  
   - O bien, ve a https://colab.research.google.com/, selecciona “File → Open notebook → GitHub” y pega la URL de tu repositorio.

3. **Ejecutar las celdas**  
   - En Colab, ve a “Runtime → Run all”.

4. **Requisitos (solo si ejecutas localmente)**  
   ```bash
   pip install pandas matplotlib folium geopy
