# Analisis-de-los-mejores-libros-de-Amazon

# Introducción
En este proyecto realicé el análisis de datos de los mejores libros de Amazon (2009 – 2019) con el objetivo de realizar un ejercicio de práctica para analizar el comportamiento de los datos partiendo de l planteamiento de las siguientes preguntas:

¿Cuáles son los mejores libros de acuerdo a su rating?
¿Cuál es el libro que ha tenido la mayor cantidad de reviews de todos los años?
¿Cuál es el género de libro preferido por los lectores?
¿Cuál es el precio de los libros más vendidos?

# Datos
El dataset o conjunto de datos que utilicé fue obtenido del sitio web de Kaggle [1], utilicé las librerías de Python: Pandas, Seaborn y Matplotlib para la exploración y visualización de los datos y usé Deepnote para realizar todo el proceso.

# Análisis
La base de datos está integrada por información de 550 libros que pertenecen al top 50 de libros más vendidos de cada año (2009 a 2019) en Amazon. Y la base consta de seis columnas donde se especifican las características de cada libro tales como: nombre, autor, rating, cantidad de reviews, precio, año y género.

-¿Cuáles son los mejores libros de acuerdo a su rating?
Para dar respuesta a esta pregunta realicé la agrupación de los datos de acuerdo a su calificación o rating utilizando la función groupby de la librería Pandas [Python]. De esta forma se logró identificar que el 20% del total de los libros analizados obtuvo la mayor calificación de rating (4.9) y estos fueron:

-¿Cuál es el libro que ha tenido la mayor cantidad de reviews de todos los años?
L mayor cantidad de reviews fue de 87.841 para el libro: Where the Crawdads Sing o La chica salvaje en la edición en español y obtuvo un rating de 4.8:

-¿Cuál es el género que sobresalió?
Los libros preferidos por los usuarios de Amazon correspondieron al género No Ficción con 310 libros equivalente a un 56.3%. Mientras que los de género de Ficción fueron 240 libros correspondiente a un 43.6% del total de los analizados.

De igual forma, e logró identificar que el rating de todos los libros de género No Ficción estuvo por encima de 4.0. Mientras que para los libros de Ficción se observa un comportamiento diferente debido a que algunos de sus libros tuvieron calificaciones menores a 3.25.

-¿En promedio, cuánto cuestan los libros?
El precio de los libros ha disminuido con el tiempo. El menor precio alcanzado se encuentra en el periodo posterior al año 2016 con un promedio de precios de 13 y10 USD.

# Conclusiones
-Se logró utilizar las librerías Python para realizar representaciones gráficas con el fin de analizar la base de datos seleccionada.

-Se identificó que 4 libros de la serie de Harry Potter y DogMan se ubican dentro de los mejores con un rating de 4.9.

-El libro Where the Crawdads Sing fue lanzado en 2018. Sin embargo, obtuvo más reviews que cualquier otro libro lanzado en el periodo de 2009 a 2019.

-El género de no ficción fue el favorito en el periodo estudiado y la calificación o rating de los libros se mantuvo siempre arriba del 4.0.


# Bibliografía
[1]         “Amazon Top 50 Bestselling Books 2009 – 2019 | Kaggle.” https://www.kaggle.com/datasets/sootersaalu/amazon-top-50-bestselling-books-2009-2019 (accessed Aug. 13, 2022).

Made by [Angie Lara](https://angielara.com/analisis-de-los-mejores-libros-de-amazon/)
