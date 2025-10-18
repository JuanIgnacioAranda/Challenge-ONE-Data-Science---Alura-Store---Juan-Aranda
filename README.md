# Proyecto Alura Store - Análisis de Datos

Este proyecto forma parte del **Desafío de Data Science de Alura Latam**.  
El objetivo es analizar los datos de ventas de cuatro tiendas de la cadena **Alura Store** para ayudar al Sr. Juan a decidir cuál de ellas debería vender, basándose en su rendimiento comercial, satisfacción de clientes y cobertura geográfica.

---

## Propósito del análisis

El propósito de este estudio es identificar la tienda con menor desempeño general considerando cinco aspectos clave:

1. **Ingresos totales por tienda.**  
2. **Categorías de productos más y menos vendidas.**  
3. **Calificación promedio de los clientes.**  
4. **Productos con mayor y menor rotación.**  
5. **Costo de envío promedio.**

A partir de estos indicadores, se busca elaborar una recomendación sustentada con evidencia gráfica y numérica, apoyando la toma de decisiones del Sr. Juan.

---

## Estructura del proyecto

- **AluraStoreLatam.ipynb** → cuaderno principal con el análisis completo y los gráficos.  
- **data/** → carpeta con los archivos CSV de las cuatro tiendas (`tienda_1.csv` a `tienda_4.csv`).  
- **LICENSE** → licencia del proyecto.  
- **README.md** → este archivo con la descripción general.

---

## Análisis realizados

Durante el desarrollo se realizaron los siguientes análisis, con sus respectivos gráficos:

- **Facturación total por tienda:** comparación directa de ingresos acumulados.  
- **Ventas por categoría:** muestra qué tipos de productos dominan en cada tienda.  
- **Calificación promedio:** mide la satisfacción de los clientes.  
- **Productos más y menos vendidos:** identifica qué artículos impulsan (o frenan) las ventas.  
- **Costo de envío promedio:** permite evaluar la eficiencia logística.  
- **Distribución geográfica:** analiza la cobertura territorial y el comportamiento regional de ventas.

Cada uno de estos apartados cuenta con visualizaciones claras (barras, líneas, circulares, mapas de calor y dispersión) generadas con **Matplotlib** y **Seaborn**, lo que permite comprender de forma visual las diferencias de desempeño entre las tiendas.

---

## Análisis geográfico y cobertura territorial

El análisis de coordenadas (latitud y longitud) permitió identificar las zonas donde se concentran las ventas y cómo se distribuye la actividad comercial entre las tiendas.  
Las cuatro tiendas operan en **19 ciudades**, con una fuerte presencia en **Bogotá, Medellín, Cali y Cartagena**, los principales centros urbanos del país.

Los gráficos de dispersión y mapa de calor mostraron que las tiendas **1 y 2** mantienen un volumen estable en la mayoría de las regiones, mientras que la **Tienda 4**, aunque tiene la misma cobertura, registra **menores ingresos y ventas por ciudad**, lo que sugiere una menor eficiencia comercial.

---

## Conclusión general

Tras analizar todos los indicadores, se concluye que:

- **La Tienda 1** presenta el mejor equilibrio general entre ingresos, ventas y calificaciones.  
- **La Tienda 2** mantiene un rendimiento competitivo, con buenos resultados en varias categorías.  
- **La Tienda 3** muestra un desempeño aceptable, aunque ligeramente inferior en satisfacción.  
- **La Tienda 4**, en cambio, obtiene los **ingresos más bajos y menor rotación de productos**, sin diferencias positivas en calificación o cobertura que compensen su rendimiento.

**Recomendación:**  
La **Tienda 4** es la candidata más lógica para ser vendida.  
Su menor rentabilidad y desempeño general la convierten en la opción menos conveniente para mantener en la cadena, sin afectar la presencia territorial ni los resultados globales de Alura Store.

---

## Instrucciones para ejecutar el proyecto

1. Clonar o descargar este repositorio.  
2. Abrir el archivo `AluraStoreLatam.ipynb` en **Google Colab** o **Jupyter Notebook**.  
3. Ejecutar las celdas en orden, asegurándose de tener instaladas las librerías **pandas**, **matplotlib** y **seaborn**.  
4. Observar los resultados gráficos y la conclusión final.

---

## Tecnologías utilizadas

- **Python 3**  
- **Pandas** (procesamiento de datos)  
- **Matplotlib** y **Seaborn** (visualización)  
- **Jupyter / Google Colab** (entorno de análisis)

---

## Nota final

Este proyecto fue desarrollado con fines educativos, aplicando herramientas de análisis de datos para resolver un problema empresarial real.  
El enfoque está en la interpretación de la información más que en el uso avanzado de modelos predictivos, promoviendo la comprensión de cómo los datos pueden apoyar decisiones estratégicas en un contexto comercial.

