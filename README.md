En El ejercicio se usa un dataset varia data del cancer en donde se establece si el cancer es benigno o maligno 

En el ejerccio usamos los datos para predecir si el cancer es benigno o maligno asi con analisis de datos se puede tratar de predecir si la gente nececita intervencion o no.

usamos tres tipos de modelos 
-neural network
-random forest
-gradiente

en neural network la matris de confucion nos da un error bastante grande con respescto a la clase 1 que se puede considerar con los datos malignos 
casi 55 flasos positivos de la prediccion 
ninguna concidencia con relacion a los casos benignos nos da calramente una idea de que o la red nececita un dataset de training mas extenso o la red debe ajustarse para minimizar el error.


en random forrest la matris de confucion das da un mayor precicion ya que los asiertos tanto de benignos y malignos crecieron sustancialmente
los falsos positivos bajaron siendo los casos malignos mayores a los benignos pero con un bajo porcentaje a comparacion de los asiertos.
El random forest por su forma de realizar las predicciones se acopla perfectamente al dataset dando un buen porcentaje de aceptacion

En gradiente tenemos una muy buena prediccion.
totalmente aceptable en predicciones correctas ribaliza mucho a random forrest.
los falsos positivos han crecido un poco mas por lo que se presume que debemos tener datos sobrepuestos.
la gradiente se puede ajustar si se analiza los datos para ver si un ajuste seria beneficioso 
por el modelo el radom fores es mucho mejor pero la gradiente no se queada atras y sus resltados son prometedores y validos.

Para finalizar se tiene que las predicciones pueden ayudar mucho a detectar un cancer maligno y si se tiene data de los pacietntes esto ayudara mucho a preveer muertes inecesarias.
