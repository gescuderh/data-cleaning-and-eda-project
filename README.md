# Data Cleaning and EDA Project

## Descripción
Este proyecto incluye la limpieza y el análisis exploratorio de datos (EDA) de un dataset que ha elaborado ChatGPT. Se realizó la limpieza del dataset para prepararlo para identificar patrones y relaciones en los datos.

## Objetivos
- Limpiar datos y manejar valores faltantes y anómalos.
- Realizar un análisis exploratorio para identificar patrones.
- Crear visualizaciones para comunicar hallazgos clave.

## Descripción del Dataset

id: Identificador único del registro.

name: Nombre de la persona.

age: Edad de la persona.

income: Ingreso de la persona.

city: Ciudad de residencia.

has_children: Indicador de si tiene hijos.

num_purchases: Número de compras realizadas.

signup_date: Fecha de registro.

## Cómo Ejecutar el Proyecto
1. Clona el repositorio:
   ```bash
   git clone https://github.com/gescuderh/data-cleaning-and-eda-project.git

2. Navega al directorio del proyecto:
   ```bash
   cd data-cleaning-and-eda-project

4. Instala las dependencias:

   Crea un archivo `requirements.txt` para listar las dependencias del proyecto:

   ```text
   jupyter
   numpy
   pandas 
   os
   seaborn
   matplotlib.pyplot
   missingno
   warnings
   ````
   
   ```bash
   pip install -r requirements.txt
   ```

6. Ejecuta el notebook:
   ```bash
   jupyter notebook notebooks/data_cleaning_and_eda.ipynb
   ```

## Limpieza de los datos

Se han identificado las siguientes irregularidades en el dataset original (messy-dataset.csv)

1. Registros Null en las columnas "age" y "num_purchases" y datatype erroneo.
2. Valores atípicos ("-99999") en columna "income".
3. Valores inconsistentes ("Unknown") en columna "city".
4. Valores inconsistentes ("MAYBE") en columna "has_children".

## Análisis Exploratorio de Datos (EDA)

A continuación se muestran los gráficos generados durante el análisis, junto con una breve descripción de cada uno.

# 1. Distribución de la Edad

![Distribución de la Edad](charts/age_distribution.png)

**Descripción**: Este gráfico muestra la distribución de las edades en el dataset. Podemos observar que la mayoría de los registros se encuentran en el rango de 30 a 50 años.

# 2. Ingresos por Ciudad

![Ingresos por Ciudad](charts/income_by_city.png)

**Descripción**: El gráfico muestra los ingresos promedio por ciudad. Se observa que la ciudad de Los Ángeles tiene un ingreso promedio más alto en comparación con Phoenix y Houston.

# 3. Número de Compras por Edad

![Número de Compras por Edad](charts/purchases_by_age.png)

**Descripción**: Este gráfico muestra la relación entre la edad y el número de compras realizadas. Los datos sugieren que los clientes más jóvenes tienden a hacer más compras.

## Conclusiones

- La mayoría de los registros tienen edades entre 30 y 50 años.
- Los Ángeles tiene los ingresos promedio más altos entre las ciudades analizadas.
- Los clientes más jóvenes parecen hacer más compras.



