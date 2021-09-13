# Lectura 4

El paper de esta semana es un pequeño resumen de Content-Based Recommendation Systems. Primero explica de qué se tratan estos sistemas, y luego muestra las diferentes componentes que los conforman: las representaciones de los items, el perfil del usuario (sus preferencias e historial), y finalmente los modelos de Machine Learning que se pueden usar para aprender dichas representaciones.

En general me parece que gran parte de lo que se menciona está desactualizado. Sobre todo en los modelos de ML y en la representación de los campos de texto. Hoy en día sabemos que los modelos de lenguaje pueden ser muy efectivos para clasificar documentos y/o extraer _features_. El paper fue publicado el año 2007. Word2Vec es del año 2013. Transformer es del 2017. Es por eso que en el paper se limitan a usar solamente TF-IDF, o a reglas lógicas simples. Por otra parte, otros modelos de clasificación basados en aprendizaje profundo pueden ser usados en vez de usar Árboles de Decisión, Naive Bayes, o SVM. 

Otra falencia relacionada con lo mismo es que no se menciona la posibilidad de extraer _features_ de imágenes (tales como fotos de un producto o carátulas) o incluso de video. Supongo que esto es algo que solamente se lograría después, con el avance de las CNN y otros modelos de Computer Vision. Un claro ejemplo de que esto se puede hacer es la lectura opcional "_Content-based artwork recommendation: integrating painting metadata with neural and manually-engineered visual features_"

De todas formas, creo que lo que más se rescata del paper es el esquema en el que sitúa la recomendación basada en contenido. Lo más importante es que hay que tener una buena representación del contenido y una buena representación del usuario.

En cuanto a los algoritmos mencionados en el paper, me llamo la atención el algoritmo de Rocchio, ya que ellos mismos dicen que matemáticamente no está demostrado que funcione, pero que sí funciona empíricamente. Algo que no entendí además es cómo se etiqueta un documento como relevante o no relevante.

Siento que en general al paper le faltó dar más ejemplos concretos, ya que solo se queda con la descripción teórica de las fórmulas, y eso hace que sea difícil de entender.
