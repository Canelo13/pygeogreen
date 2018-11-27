# pygeogreen
Python library for identify green areas from a vector field.
# Calculo de índice de vegetación del estado de colima, y creación de un mapa Georrefenciado

Autores: Jorge Humberto  Vargas Nava,  Juan Daniel Espinoza Ramos

Resumen

Realizar un programa utilizando Python más GDAL, que se encargara de realizar un cálculo de vegetación del estado de colima y a la vez creara una imagen .tif, también realizamos lo mismo con otros archivos .tif del estado y del país, además de archivos .tif de otros países.

**Palabras Clave:**  cálculo de vegetación, imagen .tif

Abstract:

Perform a program using Python plus GDAL, which will perform a vegetation calculation of the state of Colima and at the same time create a .tif image, we also do the same with other .tif files of the state and country, as well as .tif files from other countries.

**Keywords:** GDAL, vegetation calculation, image .tiff

## 0.1. Introducción.

En este proyecto realizaremos un cálculo de vegetación del estado de colima utilizando GDAL, PYTHON Y RGDAL, este último lo utilizaremos para que nos de la imagen .tif ya referenciada y así poderla trabajar en QGIS sin ningún problema.

**Calculo de vegetación.**

El NDVI (Normalized Difference Vegetation Index) es un índice de vegetación muy versátil para la evaluación de la vegetación y la dinámica de cambio de cobertura. Este índice ha sido estudiado y evaluado con una serie de satélites por muchos años, cambiando su  método de cálculo respecto del número y tipo de bandas del satélite.

## 0.2. Desarrollo Experimental.

Los experimentos o intentos realizados en este proyecto fueron varios, para iniciar nosotros queriamos realizar un programa un programa que nos prporcioanar las coordenadas de cada poligono de colima, pero nos enfrentamos con el problema que tendriamos que tener una

orotofoto o un mapa vectorizado para que esto funcionara, tambien nosw dimos cuneta que tendriamos que realizar muchas capa para lograr eso.

Para la realizacion del calculo de NDVI primero lo realizamos de una manera normla con una imagen .tiff descagada de la pagina para ver que funcionara bien el programa una vez que logramos que el programa funcionara con una solo imagen comenzamos a probar con varias imágenes a la vez para ver como reaccionaba el programa al trabajar con varios archivos a la vez y ver si dicho programa tenia la capacidad de trabajar bajo marcha forzada por lo que nos dimos cuenta el programa puede trabajar ,uy bien con varias archivos a la vez siemore y cuando la computadora sobre la que estas trabajando los soprte.

https://github.com/Canelo13/pygeogreen/blob/master/imagen.png

Lo primero que intentamos fue que el programa que calcularia el NDVI estuviera bien echo despues comenzamos a ver lo de la lectura de varios .tif descargados de la pagina y luego comenzamos a ver como le hariamos para que el .tiff que seria nuestro resultado quedara georreferenciado.

Programa encargado de leer un solo archivo .tif

Una vez obentido el .tif con el programa lo unico que hicimos despues fue comprobar que si quedara georefenciado y lo que hcimios fue revisar en QGIS.

### 0.2.1. **Manejo de Datos.**

El manejo de datos de este trabajo tan solo fueron las distintos archivos .tif para el cálculo de vegetación de distintas partes de colima, y de algunos otros lugares, no solo del estado de colima o de México en general, sino también de algunas otras  partes del mundo

### 0.2.2. **Análisis de Resultados.**

Los resultados obtenidos en este proyecto fueron satisfactorios ya que cumplieron con  lo que se plantea en el proyecto y era ver el cálculo de vegetación del estado de Colima y con ese mapa comprobar el aumento de la mancha urbana en los últimos años y en los años futuros ya que con este programa se puede realizar el cálculo de vegetación de años anteriores y así comprobar cómo es que la mancha urbana ha ido creciendo año con año y cual será su comportamiento en un futuro.

### 0.2.3. **Conclusiones.**

Como conclusión de este proyecto mi compañero y yo llegamos a una solo conclusión y es que el cálculo de vegetación es de mucha ayuda para saber el comportamiento histórico de la mancha urbana  y el comportamiento a futuro de esta mediante el dicho calculo

Este programa es muy importante por una simple razón , la cual es que la vegetación es lo mas importante para el ser humando dejando de lado el agua ya que es nuestra comida por lo tanto el saber donde esta ubicado y su extensión es de gran ayuda para distinguir la ciudad del campo o lugares de áreas verdes.

## 0.3. Bibliografía.

- [http://gidahatari.com/ih-es/calculo-del-indice-de-vegetacion-ndvi-de-imagenes-landsat-8-con-qgis](http://gidahatari.com/ih-es/calculo-del-indice-de-vegetacion-ndvi-de-imagenes-landsat-8-con-qgis)
- [https://ers.cr.usgs.gov/login?RET\_ADDR=https://ers.cr.usgs.gov](https://ers.cr.usgs.gov/login?RET_ADDR=https://ers.cr.usgs.gov)
poster:

