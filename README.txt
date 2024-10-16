*********************************************
*********************************************
1. /LSTM Diferido contiene los modelos de regresión probados en con una LSTM en diferido (stateful y no stateful). Los modelos LSTM en diferido del TFG aparecen en el directorio LSTM Diferido/Regresion/One-step/

*********************************************
*********************************************
2. /UNET + LSTM contiene los modelos de regresion probados con la arquitectura UNET de Carlos Cambero junto con la parte LSTM añadida. Los modelos que aparecen en el TFG respecto esta arquitectura se encuentran en el directorio UNET+LSTM/One-Step/Stateful/Modelo longitud 65/Prediccion_24_hras/OneStep_Modelo65_Stateful_24hras.ipynb

*********************************************
*********************************************
3. /ConvLSTM contiene algunas pruebas realizadas sin resultado con las ConvLSTM.

*********************************************
*********************************************
4. /datasets contiene los dos datasets con los que se trabaja en el TFG. "imagenes_etiquetadas_8x8-002-001.csv" es el dataset que contiene las imagenes etiquetadas de las series temporales convertidas a imagenes de las 25 turbinas eolicas. El archivo "imagenes_8x8_WT2" contiene en concreto las imagenes de la turbina eolica 2. La intencion de este ultimo archivo es trabajar con un conjunto de datos de menor tamaño.

*********************************************
*********************************************
5. /UNET contiene la ejecucion de los modelos UNET de Emilio Delgado y Carlos Cambero, generando dos series temporales de etiquetas, almacenadas en dos archivos: "etiq_Carlos_8x8_3D_prediccion.csv" y "etiq_Emilio_8x8_3D_prediccion.csv". 

	El conjunto de etiquetas "etiq_Carlos_8x8_3D_prediccion.csv" se utiliza en las LSTM en diferido del TFG.

*********************************************
*********************************************
6. El codigo del analisis de los datos se encuentra en el directorio /Scrips Visualization Colab. El analisis de los datos se realiza sobre las series temporales de las variables recogidas del parque eolico.


** Tambien se incluyen algunos modelos entrenados y almacenados en archivos con el formato .h5 **
