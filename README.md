![Allura Store Banner](https://github.com/byfurkation/Allura_store/blob/main/assets/banner.png?raw=true)


# <h1 align="center"> Allura Store - en Python </h1>
## <h1 align="center"> Análisis de datos para tienda alura y decisiones estratégicas </h1>

![Static Badge](https://img.shields.io/badge/Data%20Analysis-Python-brightgreen?style=flat-square)

## Indice  

- [1 El propósito del análisis realizado](#1-el-propósito-del-análisis-realizado)

- [2 La estructura del proyecto y organización de los archivos](#2-La-estructura-del-proyecto-y-organización-de-los-archivos)

- [3 Ejemplos de gráficos e insights obtenidos](#3-Ejemplos-de-gráficos-e-insights-obtenidos)

- [4 Instrucciones para ejecutar el notebook](#4-Instrucciones-para-ejecutar-el-notebook) 

- [5 Acceso al proyecto](#acceso-al-proyecto)

- [6 Tecnologías utilizadas](#6-tecnologías-utilizadas)

- [7 Autor](#7-autor)

## 1 El propósito del análisis realizado
En este caso práctico, se plantea ayudar al señor Juan a decidir qué tienda de su cadena Alura Store debe vender para iniciar un nuevo emprendimiento. Para ello, se analizan datos de ventas, rendimiento y reseñas de las 4 tiendas de Alura Store. El objetivo es **identificar la tienda menos eficiente** y presentar una recomendación final basada en los datos.

Para dicho fin se necesita: 
* Cargar y manipular datos CSV con la biblioteca Pandas.

* Crear visualizaciones de datos con la biblioteca Matplotlib.

* Analizar métricas como ingresos, reseñas y rendimiento de ventas.

**Requisitos:**

* Analizar datos de la tienda.

* Evaluar información como los ingresos, las categorías más vendidas, las reseñas de los clientes, los productos más vendidos y el envío promedio.

* Crear gráficos para visualización, mínimo de 3 gráficos diferentes, que pueden incluir gráficos de barras, circulares, de dispersión y otros.

* Enviar una recomendación: Después del análisis, escriba un texto explicando a qué tienda debería vender el Sr. João y por qué, basándose en los datos presentados.

## 2 La estructura del proyecto y organización de los archivos
Para llevar a cabo el presente análisis, se puede dividir en las siguientes etapas:

1️⃣ **Extracción de datos**

Los datos de cada tienda están disponibles en archivos CSV que se encuentran dentro del presente proyecto bajo los nombres de "tienda_1.csv", "tienda_2.csv", "tienda_3.csv" y "tienda_4.csv" si es que se considera necesario revisarlos o hacer un análisis independiente, sin embargo es importante mencionar que en el Notebook de Júpiter de nombre "AluraStoreLatam.ipynb" que también se encuentra presente en el proyecto, al abrirlo en Google Colab, se encontrarán referenciados mediante código, lo cual permite extraer información de las cuatro tiendas y organiza los datos en DataFrames utilizando la biblioteca Pandas.

Para descargar el Notebook de Júpiter de nombre "AluraStoreLatam.ipynb" es importante entrar al repositorio seleccionar el archivo dando clic en él, para posteriormente en la nueva ventana de navegación, ir a la parte superior derecha donde se buscará una flecha en dirección hacia abajo, la cual al colocar el cursor sobre él nos aparecerá la leyenda " downland file". Se presionará dicho botón, lo cual lo descargará en nuestra carpeta que tengamos predeterminada.

2️⃣ **Explorar el conjunto de datos**

Es esencial explorar el conjunto de datos para comprender su estructura y contenido. Este paso permite identificar patrones, inconsistencias y las columnas más relevantes para los siguientes pasos.

El conjunto de datos se estructura de la siguiente forma: 

* Producto y Categoría: Artículos vendidos y sus calificaciones.
* Precio y Envío: Valores de venta y costos asociados.
* Fecha y ubicación de compra: Información temporal y geográfica.
* Evaluación de compra: Comentarios de clientes.
* Tipo de Pago y Cuotas: Métodos utilizados por los clientes.
* Coordenadas Geográficas: Ubicación de las transacciones. 

Una vez hecha esta exploración, nos permite comprender cuáles son las probables primeras actividades que necesitamos para cumplir el objetivo de nuestro análisis.

3️⃣**Análisis de Datos**

*Ingreso total por cada tienda*

En este primer análisis, se calcula el ingreso total de cada tienda. Sumando los valores de la columna Precio de cada conjunto de datos de la tienda para estimar los ingresos.

*Ventas por categoría*
  
Se calcula la cantidad de productos vendidos por categoría en cada tienda. La idea es agrupar los datos por categoría y contar el número de ventas de cada tipo, mostrando las categorías más populares de cada tienda.

*Valoración media por tienda*
Se calculan las calificaciones promedio de los clientes para cada tienda. El objetivo es conocer la satisfacción del cliente con los productos vendidos.

*Productos más y menos vendidos*
Identificar qué productos fueron los más vendidos y los menos vendidos en cada tienda. Se deben visualizar los resultados para que quede claro qué productos destacaron en ventas en cada tienda.

*Valor del envío promedio por tienda*
En este paso, se calcula el costo de envío promedio para cada tienda. El objetivo es comprender cuánto se gasta, en promedio, en el envío de cada tienda.


4️⃣**Visualizaciones**
Después de realizar los análisis, se debe transformar los resultados en visualizaciones que ayuden a comprender mejor los patrones y los insights encontrados.

De acuerdo a lo creado creado, se recomienda generar al menos tres gráficos. Estos gráficos deben ser de diferentes tipos (como barras, líneas, dispersión, entre otros) para presentar una visión completa de los datos, resaltando los puntos más relevantes, como *los ingresos de la tienda, la distribución de categorías de productos, las opiniones de los clientes, los productos más vendidos y/o los costes de envío.*

Matplotlib ofrece una variedad de tipos de gráficos que son fáciles de implementar.

🖼️

5️⃣**Informe Final**



## 3 Ejemplos de gráficos e insights obtenidos

## 4 Instrucciones para ejecutar el notebook

## 5 Acceso al proyecto

## 6 Tecnologías utilizadas
* Python.
* Jupiter Notebook en Google Colab.
* Github.

## 7 Autor

| [<img src="https://avatars.githubusercontent.com/u/194540551?s=200" width=115><br><sub>Christian Carvajal</sub>](https://github.com/byfurkation) |
| :---: |
