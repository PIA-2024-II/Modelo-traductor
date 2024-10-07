Requisitos Previos

Antes de ejecutar este notebook, asegúrate de tener instaladas las siguientes bibliotecas:

    pandas
    pytorch 2.4.1
    cuda 12.4
    transformers (de Hugging Face)
    sklearn

Importar bibliotecas:

    Importa todas las bibliotecas necesarias para la manipulación de datos, el manejo del modelo, y el entrenamiento. Esto incluye bibliotecas como pandas, torch, y transformers, por lo que es necesario que estas esten instaladas para el funcionamiento del programa.

Configuración del dispositivo:

    Se verifica si CUDA está disponible para ejecutar el modelo en una GPU y acelerar el proceso de entrenamiento.

Carga de datos:

    Se carga un archivo CSV que contiene los datos de traducción. Se debe actualizar el código a la ruta del archivo CSV local para el correcto funcionamiento del programa, si no dará error.

Preparación de los datos:

    Se dividen los datos en conjuntos de entrenamiento y validación.
    Se utiliza DataLoader de PyTorch para gestionar los datos durante el entrenamiento.


