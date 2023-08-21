# KhonenSOM
EN: This Python-programmed project implements a Kohonen Map, also known as the Kohonen Self-Organizing Neural Network. It's a type of unsupervised learning neural network primarily utilized for performing clustering tasks. Its main goal is to discover patterns and relationships in input data without the need for prior labels or categories. In this case, we group a map of RGB color pixels.

For its successful implementation, we have had to fine-tune the respective hyperparameters using various techniques and visualizations to avoid overfitting and underfitting, ensuring that the network generalizes correctly. 

Once we have our network properly trained, we proceed to classify 50 new patterns. For each of them, we print the Best Matching Unit (BMU) and then create a bar histogram of the resulting activation matrix. To justify the values of our network's hyperparameters, we also include our elbow graph. Finally, we test the classification of 7 patterns with extreme values (very different colors) to verify if our network has been trained correctly

ES:Este proyecto programado en Python implementa un Mapa de Kohonen, también conocido como la Red Neuronal Autoorganizada de Kohonen. Es un tipo de red neuronal de aprendizaje no supervisado que se utiliza principalmente para realizar tareas de agrupamiento. Su objetivo principal es descubrir patrones y relaciones en los datos de entrada sin necesidad de etiquetas o categorías previas. En este caso, agrupamos un mapa de píxeles de colores RGB.

Para su implementación exitosa, hemos tenido que ajustar los hiperparámetros correspondientes utilizando diversas técnicas y visualizaciones para evitar el sobreajuste y el subajuste, garantizando que la red generalice de manera correcta.

Una vez que tenemos nuestra red correctamente entrenada, procedemos a clasificar 50 patrones nuevos. Para cada uno de ellos, imprimimos la Unidad de Coincidencia Mejor (Best Matching Unit, BMU) y luego creamos un histograma de barras de la matriz de activación resultante. Para justificar los valores de los hiperparámetros de nuestra red, también incluimos nuestro gráfico del codo. Finalmente, probamos la clasificación de 7 patrones con valores extremos (colores muy diferentes) para verificar si nuestra red ha sido entrenada correctamente
