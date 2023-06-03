# M2

## Clasificación de imágenes Fashion MNIST

**[Fashion-MNIST](https://github.com/zalandoresearch/fashion-mnist)** es un conjunto de datos de imágenes de artículos de Zalando, que consta de un conjunto de entrenamiento de 60,000 ejemplos y un conjunto de prueba de 10,000 ejemplos. Cada ejemplo es una imagen en escala de grises de 28x28, asociada a una etiqueta de una de las 10 clases. El conjunto de datos sirve como un reemplazo directo del conjunto de datos original [MNIST](http://yann.lecun.com/exdb/mnist/) para la evaluación de algoritmos de aprendizaje automático. Comparte el mismo tamaño de imagen y la estructura de divisiones de entrenamiento y prueba. Puedes obtener más información sobre el conjunto de datos en este [enlace de Kaggle](https://www.kaggle.com/datasets/zalando-research/fashionmnist).

En este repositorio se implementaron dos modelos para la detección automatica de cada una de sus 10 clases.
Aquí están los diferentes cuadernos:

* **1-Convolution Layer CNN**: Entrené un clasificador CNN simple con 1 capa de convolución, 1 capa de max-pooling, 2 capas densas y 1 capa de dropout. Obtuve una precisión del 92.29%.
* **4-Convolution Layer CNN**: Entrené un clasificador CNN aún más profundo con 4 capas de convolución, 2 capas de max-pooling, 3 capas densas, 5 capas de dropout y 6 capas de normalización por lotes. Obtuve una precisión del 93.52%.

### Requisitos

* [Python 2.7](https://www.python.org/download/releases/2.7/) o [Python 3.6](https://www.python.org/downloads/release/python-360/)
* [Jupyter Notebook](http://jupyter.org/)

### Dependencias

Elige las versiones más recientes de las siguientes dependencias:

* [pandas](https://pandas.pydata.org/)
* [numpy](http://www.numpy.org/)
* [matplotlib](https://matplotlib.org/)
* [sklearn](http://scikit-learn.org/stable/)
* [keras](https://keras.io/)
* [tensorflow](https://www.tensorflow.org/)

