# LABORATORIO #4

+ Marvin Alejandro Diaz Castillo
Carné: 9516008
+ Héctor Alfredo Vásquez Alarcón
Carné: 21006402


# Proyecto Final

## Descripción


En este proyecto desarrollaremos un pipeline de Ingieneria de Datos utilizando Python, SQL y AWS para su desarrollo. ira trabajar con un dataset. El motivo del proyecto es poner en practica lo aprendido en la clase Ciencia de Datos en Python, 

## Objetivos generales:
Realizar un ETL por medio de AWs
Desarrollar un pipeline de Ingieneria de Datos utilizando Python, SQL y AWS para su desarrollo.


## Objetivos especificos:
* Extraer la información, 
* Transformacion de los datos por medio de Python, previo a cargar la informacion a la base de datos.  Utilizaremos librerias como Numpy y Pandas, para la exploración y analisis de la información. Para visualizacion de datos utilizaremos Matplotlib
* Extraer información de las tablas  por medio de SQL. 
* Creacion de base de datos en la nube por medio de AWS en RDS
* Crear ETLs
* Resolver 5 preguntas con base a la información disponibles

# Modelo de Datos
El modelo de datos a utilizar es un dataset de ventas denominado "sales data". Este dataset esta disponible en Kaggle, por medio del link: https://www.kaggle.com/datasets/ankitchahal1/sales-data

La serie seleccionada es estructurada, consta de 25 columnas y 2823 filas.

*Columnas del dataset:*
- ORDERNUMBER
- QUANTITYORDERED
- PRICEEACH
- ORDERLINENUMBER
- SALES
- ORDERDATE
- STATUS
- QTR_ID
- MONTH_ID
- YEAR_ID
- PRODUCTLINE
- MSRP
- PRODUCTCODE
- CUSTOMERNAME
- PHONE
- ADDRESSLINE1
- ADDRESSLINE2
- CITY
- STATE
- POSTALCODE
- COUNTRY
- TERRITORY
- CONTACTLASTNAME
- CONTACTFIRSTNAME
+ DEALSIZE


## Preguntas a responder
1.	¿Cual es la linea de producto con mayores ventas?
2.	¿Que pais vende mas?
3.	¿Cual es el año con mayores ventas?
4.	Ventas por tamaño de Dealer
5.	¿Que Customer tiene mayor compras por año?

## Procedimiento

- Exploración inicial
> En esta fase evaluaremos la informacion disponible y determinaremos los resultados que podriamos obtener

> Empezaremos trabajando con un Jupyter Notebook.

> Posteriormente importaremos librerias esenciales como NumPy, Pandas, Matplotlib.

> Utilizamos Pandas para leer la información, obtener una breve vista de las primeras filas, y realizar analisis estadistico de las columnas numericas.


- Datos duplicados y limpieza de información
> Identificar si existe informacion duplicada y si faltan valores en nuestro dataset

> Calcular el numero de filas duplicadas y borrarlas del modelo utilizando Pandas

- Creacion de Base de Datos en RDS
> El motor de la base de datos es MySQL versión MySQL 5.7.37. 

> El nombre de la base de datos creada es bdproyecto


