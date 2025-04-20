# Alura Store - Análisis de Datos

## Propósito del proyecto

Este proyecto fue realizado como parte del desafío final del curso de Ciencia de Datos de Alura Latam. El objetivo principal es analizar los datos de ventas de cuatro tiendas diferentes para ayudar al Sr. Juan a decidir cuál de ellas debería vender, basándonos en factores como:

- Ingresos totales
- Categorías más y menos vendidas
- Calificaciones promedio de los clientes
- Productos más vendidos y menos vendidos
- Costos de envío promedio

## Estructura del proyecto

El proyecto está compuesto por los siguientes archivos:

- `alura_store.ipynb`: Notebook principal donde se desarrolla todo el análisis, visualizaciones y conclusiones.
- `README.md`: Este archivo con la descripción general del proyecto.
- `tienda1.csv`, `tienda2.csv`, `tienda3.csv`, `tienda4.csv`: Archivos con los datos originales de cada tienda.

## Ejemplos de gráficos e insights

Durante el análisis se generaron diferentes tipos de gráficos con `matplotlib` para visualizar los datos. Algunos ejemplos:

- **Gráfico de barras**: Comparación de ingresos por tienda.
- **Gráfico de torta (pie chart)**: Distribución de ventas por categoría.
- **Gráfico de barras horizontales**: Calificación promedio por tienda.

### Insight clave:

> La Tienda 4 fue identificada como la menos rentable, con ingresos más bajos, calificaciones promedio menores y productos menos populares. Por esta razón, se recomienda vender esa tienda.

## Cómo ejecutar el notebook

1. Cloná o descargá este repositorio.
2. Asegurate de tener instalado Python 3 y Jupyter Notebook.
3. Instalá las dependencias si no las tenés:
   ```bash
   pip install pandas matplotlib
