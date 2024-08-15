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

## EDA



