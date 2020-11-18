# K-NN
Algoritmo K-NN


**Fecha:** 18-nov-2020

**Desarrollado por:** José Miguel Llanos M

**Asignatura:** Minería de Datos

**Basado del libro:** Aprende Machine Learning del autor Juan Ignacio Begnato

----------------------------------------

**Ejercicio Python con sklearn**

* Se tiene el archivo reviews.csv con diferentes opiniones de usuarios sobre una App (257 registros). 
* De los diferentes campos se utilizaran las columnas wordcount y sentimentValue como características para alimentar el algoritmo K-NN.
* La columna wordcount indica la cantidad de palabras utilizadas para la opinión.
* La columna sentimentValue indica si el comentario fue valorado como positivo o negativo (-4 hasta 4).
* La etiqueta será Star Rating indica las estrellas que dieron los usuarios a la App, son valores discretos del 1 al 5.

**Pasos a seguir**

1. Importar las librerías (numpy, pandas, matplotlib y sklearn).
2. Cargar los datos.
3. Generar las estadísticas de los datos (wordcount, Star Rating, sentimentValue)
4. Visualizar los datos con histogramas
5. Observar los registros de la etiqueta (Star Rating)
6. Crear el set de entrenamiento y prueba
7. Usar K-NN con sklearn
8. Generar la matriz de confusion y la precision del modelo

