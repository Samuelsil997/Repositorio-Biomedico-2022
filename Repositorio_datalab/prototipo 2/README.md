
# Repositorio prototipo 2

Link: https://dataverse.redclara.net/dataverse/analisis1

estructura:

![image](https://user-images.githubusercontent.com/99204787/203448607-64be990a-cb8d-4948-a25d-5d40857559d1.png)

 
# Dataverse Analisis

https://dataverse.redclara.net/dataverse/analisis

Para este prototipo, lo que se realizó fue que se realizó en un dataverse en el que se nos fue entregado el poder máximo para poder modificar apariencia, agregar widgets, y probar funciones que no pueden ser probadas sin publicar un dataverse. También se modificó la estructura del dataverse de “análisis” basándonos en lo realizado en la tesis , en desarrollo al momento de realizar este trabajo , por Camila Lemus . Es decir, está hecha para análisis de machine learning en general. La nueva estructura es la siguiente:

Title: un título que sea fácil de buscar

Autor: Nombre del autor, afiliación, id y clase de id.

Contact: información de contacto del autor, incluyendo ID y correo electrónico. 

Description: datos generales del análisis, tales como que fue utilizada una exactitud RNA , luego estos datos pueden ser incluidos en palabras clave para afacilitar su búsqueda. 

Subject: siempre debe ser “Medicine, health and life science”

Keyword: es obligatorio agregar la cantidad de razones y cuáles fueron las razones utilizadas en el análisis.

Production date: fecha en que fue realizado el análisis.

Production place: donde fue realizado. 

Kind of data: el tipo de datos utilizados, por ejemplo, electroencefalogramas. 

Series: es la categoría que se ha escogido para incluir el porcentaje de exactitud, en notas ,de manera opcional, se puede colocar el tiempo de procesamiento.

Software: el software utilizado para el análisis, como por ejemplo, Matlab. 

Related datasets: datasets relacionados a este análisis, es decir, que se hayan utilizado, como, por ejemplo, archivos edf que se encuentren en el dataset de pruebas. 



# Dataverse Pruebas
https://dataverse.redclara.net/dataverse/pruebas1

Luego de conversar con la gente de HUMANA, se realizaron cambios a la estructura del dataverse de las pruebas como electroencefalogramas, la estructura es la siguiente:

El título del Dataset debe ser representativo del archivo que se está subiendo, de manera que sea fácil de buscar.

Author: La información de autor debe incluir el nombre, institución a la que está relacionado, y el id que se le entregó en el repositorio

Contact: Información de contacto de la misma forma. 

Description: La descripción debe ser corta y concisa. Debe contener información relevante sobre la manera en que se produjo la muestra.

Subject: El “subject” siempre debe ser el que está en la imagen.



Keyword: En keyword incluimos los datos más concretos que faciliten la búsqueda, como la frecuencia en que el electroencefalograma fue tomado, el canal en que fue hecho, y la cantidad de tomas hechas. Esto con el objetivo de que sea más fácil encontrar cierta clase de datos.
	
  Notes: En notes, se pone el tiempo que requirió adquirir esta información
	
  Language: el idioma en que fue hecho.
	
  Contributor: El origen de los datos, como por ejemplo physionet en este caso, o HUMANA en otros. 
	
  Depositor: El que está subiendo el dataset .
	
  Deposit date:  Día en que se crea el dataset.
	
  Kind of data: por ejemplo electroencefalograma.
	
  Notas: información general del tiempo de cada toma. 
