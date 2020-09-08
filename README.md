# Prediccion de valores de calidad de enlace LQI - RSSI por medio de series temporales usando ML y DL
_Proyecto dedicado al alojamiento de repositorios de automatización de generación, ejecución y prueba de rendimiento de modelos de ML y DL para la predicción valores LQI y RSSI en redes IEEE 802.15.4_

_Este proyecto es enfocado a la predicción de la calidad de enlace en redes IEEE 802.15.4 a través del uso de series temporales univariantes. Los algoritmos que se usan para la predicción o regresión de la calidad de enlace en estas redes corresponde a los algoritmos de Random Forest, Support Vector Regressor y el modelo de redes recurrentes LSTM. También se utilizó un algoritmo de predicción de series temporales conocido como ARIMA el cual se usó como referencia para la evaluación de los modelos de ML y DL._ 

_En los notebooks se encontrarán funciones que actúan para la lectura, pretratamiento, generación de modelos, prueba y generación de errores de cada modelo. A su vez la implementación tiene la capacidad de automatizar procesos haciendo llamadas entre funciones para que, a partir de un conjunto de observaciones de una serie temporal univariante, se ejecuten los procedimientos anteriormente mencionados y se generen un reporte al final de la ejecucción de cada modelo._

 
## ¿Cómo usar? 📃
Para ejecutar los modelos es requisito contar con un entorno virtual o en inglés "enviroment" que contenga:
* **Python 3.6.
* **Matplotlib en su versión estable.
* **Statsmodels (v0.12.0).
* **Tensorflow 2.0 -Keras
* **Scikit-learn 0.23.2


## Autores ✒
* ** Juan David Mantilla López
