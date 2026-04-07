# Árboles de decisión
Árboles de decisión y aplicación a la previsión meteorológica

**Integrantes del grupo:** Inés Asenjo, Marta González, Raúl Martínez, Juan Sánchez

## Presentación
El trabajo contiene de una [presentación](presentacion.pdf) con teoría sobre los árboles de decisión, la matemática que rige el algoritmo, un ejemplo sencillo de árbol, cómo se pueden solucionar problemas de sobreajuste y otros subalgoritmos

## Aplicación de los árboles de decisión a la previsión meteorológica
En el [Jupyter Notebook](arboles_de_decision-2.ipynb) hemos aplicado los árboles de decisión al estudio de predicción a un día vista sobre la posibilidad de lluvia. Hemos trabajado con un dataset con datos meteorológicos de entre 2007 y 2017 en varias ciudades australianas (celda 2). Mostramos primero un modelo de entrenamiento con un árbol simple con todas las variables de DecisionTreeClassifier predeterminadas (celdas 4 y 5). Después restringimos max_features en la celda 7, y luego equilibramos las clases con class_weight porque proporcionalmente hay muchos más días sin lluvia que con lluvia (celda 10). Para terminar, aplicamos un random forest (celda 13). 

## Conclusión
A pesar de que con clases equilibradas la precisión del modelo disminuye, nos dice con más seguridad que va a llover a pesar de que luego no llueve al día siguiente en lugar de que no va a llover y en realidad sí llueve. Consideramos que esta forma de cometer errores en la predicción es la mejor, por lo que el resultado del aprendizaje ha sido bueno.

## Entornos de programación
Hemos ejecutado el Jupyetr Notebook en colab.research.google.com, pero funciona en otros entornos como Visual Studio Code. 


