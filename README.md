# Sistema de Recomendación

Este proyecto es un ejemplo de implementación de un sistema de recomendación basado en contenido y un sistema de recomendación de filtro colaborativo en Python.

## Descripción

El código proporcionado consta de dos partes principales:

1. Sistema de recomendación basado en contenido: Utiliza las características de los libros (descripción y categorías) para calcular la similitud entre ellos y recomendar libros similares.
2. Sistema de recomendación de filtro colaborativo: Utiliza las interacciones entre usuarios y libros (calificaciones) para encontrar usuarios similares y recomendar libros basados en las calificaciones de usuarios similares.

El código carga dos conjuntos de datos: uno con información sobre los libros y otro con calificaciones de los usuarios. Luego, realiza un preprocesamiento de los datos, como eliminar filas con valores nulos y seleccionar columnas relevantes.

Después de la preparación de datos, se implementan las funciones de recomendación basadas en contenido y de filtro colaborativo. Estas funciones toman un libro o un usuario como entrada y devuelven una lista de libros recomendados.

Además, se incluyen evaluaciones de los sistemas de recomendación, como la precisión en K, la diversidad, la calidad, la eficiencia y la novedad. Se generan gráficos comparativos para visualizar estas métricas y la similitud de las categorías recomendadas por cada modelo.

## Requisitos

El código se ha desarrollado en Python y requiere las siguientes bibliotecas:

- pandas
- numpy
- matplotlib.pyplot
- scikit-learn (sklearn)

## Instrucciones de Uso

1. Clonar el repositorio o descargar los archivos en tu máquina local.
2. Asegurarse de tener instaladas las bibliotecas requeridas mencionadas anteriormente.
3. Colocar los archivos de datos (books_data.xlsx y Books_rating.xlsx) en la misma carpeta que el código.
4. Ejecutar el código en un entorno Python (por ejemplo, Jupyter Notebook) para obtener recomendaciones y visualizar los resultados.



