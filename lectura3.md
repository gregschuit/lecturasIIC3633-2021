# Lectura 3

En este *paper* se explica en general las diferentes alternativas que existen para evaluar un sistema recomendador. La primera parte del texto se encarga de explicar tres tipos de estudio: el *offline*, el estudio con usuarios, y el *online*. La segunda parte habla de las métricas matemáticas que se pueden calcular a la hora de evaluar el sistema, y cuáles son mejores en cada uno de los tipos de sistemas.

Me llamó bastante la atención que se le diera énfasis a que la evaluación *offline* no es lo ideal. En general, en otro tipo de modelos de ML, uno queda satisfecho con dividir el *dataset* en *training*, *validation* y *testing*, pero en este artículo se inclinan por realizar la evaluación con usuarios reales. Esto me hace mucho sentido. Sin embargo, creo que al explicar la evaluación *offline*, el artículo no menciona algo muy importante, que es la naturaleza dinámica de los gustos de la gente. Sentí que las desventajas que dieron del enfoque *offline* se centraron en la posible inducción de sesgos al usar menos datos. Pero creo que les faltó mencionar que, aún incluyendo todos los datos, es muy probable que la distribución de gustos a predecir ya no sea exactamente la misma que se usó para entrenar. Existe un "*data drift*" intrínseco en los gustos de las personas.

El concepto que más me llamó la atención fue el de *trust*. Ya que nunca había pensado que fuese relevante recomendar en ciertas ocasiones elementos que el usuario ya conoce. Hacer esto da más confianza al usuario de que el sistema recomienda cosas que en verdad le gustan.

Si bien se explican de manera bien detallada las diferentes formas de evaluar un modelo, siento que faltó análisis o recomendaciones para poder mejorar en cada una de las métricas. Creo que con lo indicado en el *paper* se pueden identificar fortalezas y debilidades de un sistema recomendador, pero no se dan indicaciones para mejorar.

En relación con el punto anterior, noté que el *paper* trata de cierta forma a los sistemas recomendadores como cajas negras. Esto se puede relacionar con la segunda lectura opcional (*Cremonesi, P., Koren, Y., & Turrin, R. (2010). Performance of recommender algorithms on top-n recommendation tasks.*), ya que en esta última se profundiza en el uso de diferentes arquitecturas (*neighboorhood models*, *latent factor*, etc.). La lectura obligatoria es de cierta manera agnóstica al tipo de arquitectura que se esté usando. 

En general sentí que el artículo era demasiado largo para su contenido. Creo que los autores pudieron haber escrito algo mucho más resumido. Ser tan largo lo hizo bastante fome de leer, y los contenidos no eran difíciles de entender.













