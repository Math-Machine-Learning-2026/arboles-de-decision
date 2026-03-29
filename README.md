# arboles-de-decision
Árboles de decisión y aplicación a la previsión meteorológica

Inés Asenjo, Marta González, Raúl Martínez, Juan Sánchez

El trabajo consta de una presentación con teoría sobre los árboles de decisión, la matemática que rige el algoritmo, un ejemplo sencillo de árbol, cómo se pueden solucionar problemas de sobreajuste y otros subalgoritmos. 
También incluye el Jupyter Notebook con el código: hemos aplicado los árboles de decisión al estudio de predicción a un día vista sobre la posibilidad de lluvia. Hemos trabajado con un dataset con datos meteorológicos de entre 2007 y 2017 en varias ciudades australianas. Mostramos primero un modelo de entrenamiento con un árbol simple con todas las variables de DecisionTreeClassifier predeterminadas. En otras celdas, restringimos max_features, y luego equilibramos las clases con class_weight porque proporcionalmente hay muchos más días sin lluvia que con lluvia. Para concluir, incluimos todo en un random forest. Concluimos que, a pesar de que con clases equilibradas la precisión del modelo disminuye, nos dice con más seguridad que va a llover a pesar de que luego no llueve al día siguiente y no dice que no va a llover y en realidad sí llueve. Consideramos que esta forma de cometer errores en la predicción es la mejor, por lo que el resultado del aprendizaje ha sido bueno.

Hemos ejecutado el Jupyetr Notebook en colab.research.google.com, pero funciona en otros entornos como Visual Studio Code. 


