Trabajo Final: Cálculo del Índice de Vegetación de Diferencia Normalizada (NDVI) en el área Embalse Los Molinos

Autor: Elisabet Marina Benitez
Curso: Introducción a las técnicas inteligentes de resolución de problemas de planificación, secuenciación y ejecución

Introducción
Este proyecto tiene como objetivo calcular el Índice de Vegetación de Diferencia Normalizada (NDVI) para el Embalse Los Molinos utilizando imágenes satelitales Landsat 8. El NDVI es un indicador clave para evaluar la vegetación y la salud de la misma en un área específica. El proceso incluye la extracción de las bandas necesarias, un análisis exploratorio de las bandas, y la aplicación de una máscara (generada a partir del índice MNDWI) y la eliminación de nubes previo al cálculo de NDVI. La máscara se realizó con el objetivo de obtener el área correspondiente al embalse para el análisis de NDVI.

Instalación
Para llevar a cabo el programa se utilizó Google Colab. Al cual se tiene acceso mediante el siguiente link:
https://colab.research.google.com/drive/1gQyB-s8ZNGCe7JVYHJ0_djLxIc0WcR2y?usp=sharing

Para ejecutar el archivo y levantar las imágenes se da acceso a la siguiente carpeta que es donde se ubican las imágenes:
https://drive.google.com/drive/folders/1d2nqnvwbNtVpl5URlUI4J2mXnX_bHS67?usp=sharing

Para desarrollar este proyecto se realizaron los pasos mencionados a continuación:
a) Se instalaron e importaron las siguientes librerías: rasterio, matplotlib, numpy, zipfile, os.
b) Montar el Google drive donde se encuentra el archivo zip con las imágenes a trabajar.
c) Cargar y descomprimir el archivo zip
d) Extracción de las bandas necesarias para trabajar (verde, rojo, NIR, SWIR).
e) Análisis exploratorio de los datos y metadatos de la imagen.
f) Cálculo MNDWI y máscara.
g) Eliminación de nubes.
h) Cálculo de NDVI en el área de estudio.
i) Exportar la imagen de NDVI del área de estudio

Algunas consideraciones
Es importante tener en cuenta que cuando se deben transformar los valores para generar un producto, con estos mismos datos se deben hacer los análisis exploratorios y demás. Siempre se trabaja con los mismos datos para que los resultados sean comparables.
