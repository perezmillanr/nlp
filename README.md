# Proyecto Natural Language Processing

### Desafio 1: Análisis de la similaridad entre documentos

- Selección de 5 palabras al azar del conjunto de datos y se calcula la similaridad coseno entre cada uno de estos documentos y el resto del conjunto.
- Identificación de 5 palabras más similares para cada documento original.
- Analisis si la similitud identificada tiene sentido en base al contenido del texto y la etiqueta de clasificación.
- Entrenamiento de modelos de clasificación Naïve Bayes (ComplementNB y MultinomialNB) con el objetivo de maximizar el f1-score macro en el conjunto de datos de prueba.
- Ajuste los parámetros del vectorizador y de los modelos para optimizar el rendimiento.
- Comparación de resultados de ambos modelos.

### Desafio 2

- Elección de un corpus de texto de interés: Reviews de Amazon
- Entrenamiento de embeddings: Utilizar Gensim para entrenar embeddings con el corpus elegido.
- Análisis de similaridades: Estudiar las similaridades entre términos utilizando las embeddings entrenadas: Palabras negativas y positivas.
- Grafico de las similaridades en 2D y 3D (opcional)
- Mención de los casos interesantes e interpretación en base al conocimiento del corpus.

### Desafio 3

- Entrenamiento de un modelo de lenguaje basado en arquitectura de redes recurrentes a partir de un corpus de texto.
- En el transcurso del ejercicio se explorarán técnicas de generación de secuencias y se medirá la calidad de las mismas calculando la perplejidad.
- Estructurar adecuadamente el dataset para este problema.

### Desafio 4

- Utilización de datos de conversaciones en inglés disponibles del desafío ConvAI2 para construir un bot de preguntas y respuestas (QA).
- Utilización los datos del desafío ConvAI2 para entrenar un modelo de lenguaje.
- El modelo de lenguaje se utilizará para construir un bot de QA que pueda responder a las preguntas de los usuarios.
- El modelo se puede utilizar en una variedad de aplicaciones, como servicio al cliente, educación y atención médica.

### Desafio 5

- Entrenamiento del modelo de clasificación de sentiment analysis para un dataset de reviews de apps utilizando BERT como encoder: Bueno, Malo, Neutro.
- Entrenamiento del modelo propuesto hasta la sección "3-BERT Fine tuning".
- Evaluación del F1-score en un conjunto de datos de prueba.
- Repetir el proceso para un modelo de 5 salidas
- Repetir el proceso agregando una capa densa previa antes antes de la de salida
