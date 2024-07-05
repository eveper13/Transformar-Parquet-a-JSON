# Transformar-Parquet-a-JSON
Script para transformar datos de un archivo Parquet a JSON utilizando pandas y pyarrow

## Descripción detallada:

Este repositorio contiene un notebook Jupyter (`transformar.ipynb`) que realiza una transformacion de un archivo parquet a Json. Con un analisis respectivo de las columnas del archivo usando Pandas.

### Contenido

- 'transformar.ipynb': Notebook Jupyter principal que contiene la transformacion del archivo business.parquet a .Json
- 'business.parquet': Archivo de datos Parquet utilizado en el análisis.

### Funciones 

El notebook realiza lo siguiente:
- Lee y procesa datos desde el archivo Parquet como un dataframe.
- Realiza la seleccion de todas las columnas del archivo parquet.
- Exporta los datos transformados a formato JSON.

## Cómo Ejecutar el Notebook Jupyter

### Requisitos Previos

Para ejecutar el notebook Jupyter, necesitas tener instalado lo siguiente:
- Python (preferiblemente Python 3.x)
- Jupyter Notebook
- Pandas
- PyArrow (se utiliza para leer archivos Parquet)

## Para instalar la libreria Pyarrow
Abre una terminal o línea de comandos.

Ejecuta el siguiente comando para instalar PyArrow usando pip:
pip install pyarrow