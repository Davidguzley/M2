# M2

## Selección del conjunto de datos

### Descripción
El conjunto de datos "Nike Adidas Shoes for Image Classification" es un conjunto de datos recopilado y compartido en Kaggle por el usuario Ifeanyi Nneji. Este conjunto de datos se creó específicamente para la clasificación de imágenes de zapatos de las marcas Nike y Adidas. Las imágenes se extrajeron de Bing utilizando la biblioteca "bing_image_search" de pypi. Se descargaron inicialmente 400 imágenes de cada clase y luego se recortó el conjunto de datos a 300 imágenes (se eliminaron algunas imágenes no relacionadas en el proceso de compilación del conjunto de datos). A continuación, se proporciona una descripción detallada del conjunto de datos:

* **Tamaño del conjunto de datos:** El conjunto de datos contiene un total de 576 imágenes en formato .jpg de zapatillas Nike y Adidas, distribuidas de la siguiente manera:
  * Entrenamiento: 230 imágenes de Nike y 230 imágenes de Adidas.
  * Pruebas: 30 imágenes de Nike y 30 imágenes de Adidas.
  * Validación: 28 imágenes de Nike y 27 imágenes de Adidas.

* **Distribución de clases:** El conjunto de datos está equilibrado, lo que significa que hay una cantidad igual de imágenes de zapatos Nike y Adidas. Esto asegura que tu modelo de clasificación pueda aprender de manera justa y precisa para ambas marcas.

* **Anotaciones:** Cada imagen está etiquetada correctamente con la marca correspondiente, es decir, si es un zapato Nike o un zapato Adidas. Estas etiquetas son cruciales para entrenar un modelo de aprendizaje automático capaz de diferenciar entre ambas marcas.

* **Variedad de imágenes:** El conjunto de datos contiene una variedad de imágenes de zapatos, incluyendo diferentes estilos, colores y ángulos de visualización. Esto ayudará a tu modelo a capturar las características distintivas de cada marca y realizar una clasificación precisa.

* **Calidad de las imágenes:** Las imágenes del conjunto de datos tienen una resolución razonablemente alta y una calidad visual adecuada para el propósito de clasificación. Sin embargo, es posible encontrar algunas variaciones en la calidad debido a la diversidad de fuentes y condiciones de captura.

Conjunto de datos: [Enlace al conjunto de datos](https://www.kaggle.com/datasets/ifeanyinneji/nike-adidas-shoes-for-image-classification-dataset?select=validation)
