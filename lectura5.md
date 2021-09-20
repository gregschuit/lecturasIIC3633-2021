# Lectura 5

Para esta semana, se podía escoger entre dos lecturas. La siguiente reseña es del _paper_ "Combining Predictions for Accurate Recommender Systems".

Este paper expone el efecto positivo de realizar un ensamble de modelos sobre el dataset de Netflix Prize. Primero se explica cómo se dividió el _dataset_ para poder poner a prueba el _blending_. Luego, se explica como funcionan los diferentes modelos que se pueden usar por separado para al _challenge_ de Netflix.

Posteriormente, se indica como realizar el _blending_. Aquí se explican los métodos de regresión lineal y sus variantes. Finalmente se exponen los resultados, y se concluye que la mezcla efectivamente conlleva a una mejora en el sistema.

En general el paper es útil de leer ya que, si bien expone un caso particular (el del Netflix Prize), cuenta un panorama bastante amplio sobre de que se trata el ensamble de modelos para la recomendación basada en rating.

Una de las cosas que el _paper_ no menciona es el cómo realizar ensambles usando feedback implícito. Seguramente esto puede dar mejores resultados que solamente basandose en rating.

Por otra parte, y haciendo un simil con otras disciplinas, me parece muy interesante como la teoría detrás de un ensamble lineal se relaciona con la teoría financiera de portafolios. Esto es porque, matemáticamente, los teoremas son los mismos. La teoría financiera indica que 2 acciones (2 variables aleatoreas) se pueden sumar con el objetivo de reducir la varianza y aumentar los retornos a largo plazo. Esto es lo mismo que mezclar dos modelos con una combinación lineal de su output.  









