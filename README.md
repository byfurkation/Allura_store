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
Se procede a realizar el análisis de las principales categorías de relevancia para determinar qué tienda debe de vender el señor Juan. Para este efecto se analizarán las siguientes columnas de los datos.

**Ingreso total por cada tienda**

En este primer análisis, se calcula el ingreso total de cada tienda. Sumando los valores de la columna Precio de cada conjunto de datos de la tienda para estimar los ingresos.

**Ventas por categoría**
  
Se calcula la cantidad de productos vendidos por categoría en cada tienda. La idea es agrupar los datos por categoría y contar el número de ventas de cada tipo, mostrando las categorías más populares de cada tienda.

**Valoración media por tienda**
Se calculan las calificaciones promedio de los clientes para cada tienda. El objetivo es conocer la satisfacción del cliente con los productos vendidos.

**Productos más y menos vendidos**
Identificar qué productos fueron los más vendidos y los menos vendidos en cada tienda. Se deben visualizar los resultados para que quede claro qué productos destacaron en ventas en cada tienda.

**Valor del envío promedio por tienda**
En este paso, se calcula el costo de envío promedio para cada tienda. El objetivo es comprender cuánto se gasta, en promedio, en el envío de cada tienda.

4️⃣**Visualizaciones**

Después de realizar los análisis, se debe transformar los resultados en visualizaciones que ayuden a comprender mejor los patrones y los insights encontrados.

De acuerdo a lo creado creado, se recomienda generar al menos tres gráficos. Estos gráficos deben ser de diferentes tipos (como barras, líneas, dispersión, entre otros) para presentar una visión completa de los datos, resaltando los puntos más relevantes, como *los ingresos de la tienda, la distribución de categorías de productos, las opiniones de los clientes, los productos más vendidos y/o los costes de envío.*

Matplotlib ofrece una variedad de tipos de gráficos que son fáciles de implementar.

🖼️

5️⃣**Informe Final**

Con base en los análisis realizados y los gráficos generados, se debe sintetizar los hallazgos en un informe final, en este caso se ha llevado a cabo dentro de Google Colab, redactando un texto explicando a qué **tienda debe vender el Sr. Juan**, teniendo en cuenta todos los factores analizados, como:

* Los ingresos totales de las tiendas.

* Las categorías de productos más y menos vendidas.

* Las calificaciones promedio de los clientes por tienda.

* Los productos más y menos vendidos.

* El coste de envío promedio para cada tienda.

El informe debe incluir la **justificación de su decisión, respaldada por el análisis y las visualizaciones que generaron**. Explicar, de forma clara y objetiva, las razones por las que una tienda destaca (o no) en relación a las demás, considerando las **fortalezas y debilidades de cada una.**

El informe debe estar bien estructurado, con una **introducción** que explique el propósito del análisis, un **desarrollo con la presentación de datos y gráficos**, y una **conclusión recomendando la tienda que se debe vender y justificando la elección.**

6️⃣**Análisis del desempeño geográfico OPCIONAL** 
Esta es una actividad extra para explorar las coordenadas geográficas de los datos de ventas e identificar patrones relacionados con la ubicación de las compras. Al utilizar las columnas de latitud y longitud, se pueden generar visualizaciones para comprender cómo varían las ventas según la ubicación geográfica.

Se debe utilizar los **datos de latitud (lat) y longitud (lon)** para mapear las ventas de cada tienda y analizar la distribución geográfica de los productos vendidos.

7️⃣ **Ejemplos de gráficos e insights obtenidos del desempeño geográfico OPCIONAL**
Se recomienda generar gráficos de dispersión o mapas de calor (Heatmaps) para visualizar datos e identificar áreas con la mayor concentración de ventas.

De esta forma se puede explorar si algunas tiendas tienen un rendimiento superior o inferior al esperado en determinadas regiones e identifique si existen patrones geográficos que puedan influir en el rendimiento de las tiendas, tanto en ingresos como para las calificaciones de las tiendas.

## 3 Ejemplos de gráficos e insights obtenidos

A continuación se ejemplifican gráficos e insights incluidos en el informe final, en el Notebook de Jupyter. Siendo ejemplo de esto los análisis relativos al análisis de ingreso total por tienda, ingreso por categoría Y productos más vendidos. 

Ejemplo 1:

**Análisis de Ingresos Totales** 💸

* Tienda 1: $1,150,880,400.00 (Mayor ingreso) 🔼

* Tienda 2: $1,116,343,500.00

* Tienda 3: $1,098,019,600.00

* Tienda 4: $1,038,375,700.00 (Menor ingreso) 🔽

![ingresos_tienda](https://github.com/byfurkation/Allura_store/blob/main/assets/1_ingresos_tienda.png?raw=true)

**Conclusión:** 

La *Tienda 1 lidera en ingresos* totales con una ventaja de aproximadamente $34.5 millones sobre la Tienda 2, lo que indica un volumen de negocio superior. Sin embargo, para efectos de venta, esto también significa que sería la más valiosa y por tanto la más costosa de perder del portafolio.

Ejemplo 2:

**Distribución por Categorías de Productos**

El análisis de categorías muestra patrones interesantes de demanda:

* Tienda 1:
Categorías más vendidas: Muebles (465), Electrónicos (448), Juguetes (324)
Fortaleza en diversificación de productos

* Tienda 2:
Categorías más vendidas: Muebles (442), Electrónicos (432), Juguetes (313)
Patrón similar a Tienda 1 pero con volúmenes ligeramente menores

* Tienda 3:
Categorías más vendidas: Muebles (499), Electrónicos (451), Juguetes (315)
Destaca especialmente en la categoría de Muebles

* Tienda 4:
Categorías más vendidas: Muebles (480), Electrónicos (451), Juguetes (338)
Buen equilibrio entre categorías principales

![categoria](https://github.com/byfurkation/Allura_store/blob/main/assets/2_categoria.png?raw=true)

![categoria](https://github.com/byfurkation/Allura_store/blob/main/assets/2.%20categoria_2.png?raw=true)

**Conclusión:** 

Todas las tiendas muestran fortaleza en Muebles y Electrónicos, pero la Tienda 3 sobresale particularmente en Muebles, mientras que la Tienda 1 mantiene el mejor equilibrio general.

Ejemplo 3:

**Productos Más Vendidos**
Productos estrella por tienda:

* Tienda 1: Microondas, TV LED UHD 4K, Armario (60 unidades c/u)
* Tienda 2: Iniciando en programación (65), Microondas (62), Batería (61)
* Tienda 3: Kit de bancas (57), Mesa de comedor (56), Cama king (56)
* Tienda 4: Cama box (62), Cubertería (59), Dashboards con Power BI (56)

![mas_vendid](https://github.com/byfurkation/Allura_store/blob/main/assets/4_mas_vendidos.png?raw=true)

![mas_vendid](https://github.com/byfurkation/Allura_store/blob/main/assets/4_mas_vendidos_2.png?raw=true)

**Conclusión:**: 

Cada tienda tiene productos distintivos que funcionan como pilares de ventas, lo que sugiere especialización y conocimiento del mercado local.

De la misma manera en el informe se incluyen insights recopilados sobre el análisis de las fortalezas y debilidades de las tiendas, ejemplificado con la tienda número uno a continuación:

Ejemplo: 

**Tienda 1**
**Fortalezas:**
* Líder absoluto en ingresos totales
* Excelente diversificación de productos
* Productos electrónicos de alta demanda
**Debilidades:**
* Calificación más baja de satisfacción del cliente
* Costos de envío más elevados
* Posible saturación que afecta el servicio

## 4 Instrucciones para ejecutar el notebook


## 5 Acceso al proyecto

## 6 Tecnologías utilizadas
* Python.
* Jupiter Notebook en Google Colab.
* Github.

## 7 Autor

| [<img src="https://avatars.githubusercontent.com/u/194540551?s=200" width=115><br><sub>Christian Carvajal</sub>](https://github.com/byfurkation) |
| :---: |
