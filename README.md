# VisionArtificial
Proyecto de vision Artificial

En el proyecto se aborda la clasificación de imágenes mediante el machine learning.
Los datos se obtuvieron de un centro de imágenes que será MedMNIST v2 que es una colección de imágenes biomédicas
 estandarizadas. MedMNIST contiene 12 conjuntos de imágenes para
 2D y 6 conjunto de imágenes para 3D. En este caso se trabajo con el conjunto de Enfermedades
 de pulmonía (PneumoniaMNIST 2D), se realizo un estudio de las imágenes, como, por ejemplo,
 estudiar su resolución, cantidad de imágenes, numero de etiquetas, etc. La clasificación de imágenes
 fue a través de un modelo de red neuronal profunda y la red más optima se definio en base al
 estudio del conjunto. El objetivo es lograr predecir el padecimiento de una neumonia en pacientes de casos reales.
 La importancia que tiene este tipo de investigacion es el aporte al avance de
 la inteligencia artificial, el estudio de redes neuronales para clasificación mediante patrones visuales
 ayuda a crear modelos pre entrenados con datas reales y esto en el ámbito de la salud sería una
 innovación en la detección de patologías o enfermedades de manera más optima. 

 La base de datos se constituye de 5,856 Imágenes. Cantidad de clases: Existen 2 binarias que son 0 (No tiene pulmonia) y 1 (Si tiene pulmonia).  Entrenamiento/Validación/Prueba: 4,708/524/624.

 Los resultados a los que se llegaron fueron que el modelo propuesto tuvo tuvo un accuracy de 0.742, lo que indica que fue capaz de predecir correctamente el
 74.2% de las muestras de prueba. Esto significa que el modelo tiene un rendimiento moderado en
 términos de precisión, si embargo existen estrategias de mejora que se le pueden ser aplicadas. 


 Las métricas que se utilizo para este proyecto es la de MSE (o también llamada error cuadrático
 medio), esta es una métrica utilizada comúnmente en problemas de regresión para evaluar que tan
 bien se ajusta un modelo a los datos observados
![image](https://github.com/user-attachments/assets/56154559-e4cd-408a-97be-536fadbeefd0)

Visualizacion de imagenes

![image](https://github.com/user-attachments/assets/2abb9b02-b645-4eb3-a178-73cfd4d12f3a)

Demostracion de los valores de los pixeles

 ![image](https://github.com/user-attachments/assets/9d1cd1a9-00d5-47ba-a4b3-38e7db4632f5)

 

