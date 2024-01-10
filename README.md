#Explicación sobre lo que muestran los datos del entrenamiento del modelo.

![image](https://github.com/Estivbi/Entrenar-un-modelo-ML/assets/94956228/7176856a-5ee2-405a-9c9d-50692c1028d1)

En cuanto a la interpretación del primer gráfico, podemos ver que:
•	Las flores de Iris setosa se caracterizan por sépalos cortos y anchos.
•	Las flores de Iris versicolor tienen sépalos de longitud intermedia y ancho.
•	Las flores de Iris virginica tienen sépalos largos y estrechos.
Estas diferencias en la longitud y el ancho del sépalo pueden ser útiles para clasificar las flores de Iris en sus diferentes especies. Por ejemplo, una flor con sépalos cortos y anchos es muy probable que sea una Iris setosa.
Además, podemos ver que hay una cierta correlación entre la longitud y el ancho del sépalo para cada especie. En general, las flores con sépalos más largos también tienden a tener sépalos más anchos.


![image](https://github.com/Estivbi/Entrenar-un-modelo-ML/assets/94956228/d044dcfe-9cba-4228-93bb-2875e8ee6a7c)

En cuanto a la interpretación del segundo gráfico, podemos ver que:
•	Las flores de Iris setosa se caracterizan por pétalos cortos y estrechos.
•	Las flores de Iris versicolor tienen pétalos de longitud intermedia y ancho.
•	Las flores de Iris virginica tienen pétalos largos y anchos.
Estas diferencias en la longitud y el ancho del pétalo pueden ser útiles para clasificar las flores de Iris en sus diferentes especies. Por ejemplo, una flor con pétalos cortos y estrechos es muy probable que sea una Iris setosa.
Además, podemos ver que hay una cierta correlación entre la longitud y el ancho del pétalo para cada especie. En general, las flores con pétalos más largos también tienden a tener pétalos más anchos.


Accuracy: 0.93 -> la precisión del modelo es de 0.93. Esto significa que el modelo realizó correctamente el 93% de las predicciones en el conjunto de datos de prueba.

Predictions: ['Iris-setosa', 'Iris-setosa'] -> Esto significa que el modelo ha predicho que los nuevos datos de la primera observación corresponden a la clase Iris-setosa, y los de la segunda a la clase Iris-setosa.
En general, la interpretación de una predicción de KNN es la siguiente:
•	La etiqueta de clase de la primera observación es la clase a la que se asigna el punto de datos que está más cerca de los nuevos datos.
•	La etiqueta de clase de la segunda observación es la clase a la que se asigna el punto de datos que está en segundo lugar más cerca de los nuevos datos, y así sucesivamente.
En el caso concreto del ejercicio, los nuevos datos están más cerca de los puntos de datos de la clase Iris-setosa. Por lo tanto, el modelo ha predicho que los nuevos datos pertenecen a la clase Iris-setosa.
