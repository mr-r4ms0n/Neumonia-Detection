## Deteccion de Neumonia usando imagenes X-Ray por medio de algoritmos geneticos y redes neuronales convolucionales                                         

### Descripcion
<pre>
1. Deteccion de Neumonia usando una red neuronal Convololucional y un algoritmo evolutivo y por medio del modelo “InceptionV3” with 5856 images of X-ray (1.15GB).
3. Con una red neuronal convolucional cumpliendo el 89.53% de asertividad y perdida del 0.41.
</pre>

#### Dataset
<pre>
Nombre del dataset     : Chest X-Ray Images (Pneumonia)
Dataset Link     : <a href=https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia>Chest X-Ray Images (Pneumonia) Dataset (Kaggle)</a>
                 : <a href=https://data.mendeley.com/datasets/rscbjbr9sj/2>Chest X-Ray Images (Pneumonia) Dataset (Original Dataset)</a>
</pre>

<pre>
<b>Detalles del dataset</b>
Nombre del dataset      : Chest X-Ray Images (Pneumonia)
Numero de clases        : 2
Numero/Tamaño de img    : Total           : 5856 (1.15 Gigabyte (GB))
                          Entrenamiento   : 5216 (1.07 Gigabyte (GB))
                          Validacion      : 320  (42.8 Megabyte (MB))
                          Testeo          : 320  (35.4 Megabyte (MB))

<b>Parametros del modelo</b>
Libreria de machine learning: Keras
Modelo base                 : InceptionV3 && Algoritmo evolutivo && CNN
Optimizadores               : Adam plugin
Funcion de perdida          : Entropia

<b>Para la red neuronal convolucional : </b>
<b>Parametros de entrenamiento</b>
Tamaño del lote           : 64
Numero de poblaciones     : 30
Tiempo de entrenamiento   : 2 Hours

<b>Salida (Prediccion/ Reconocimiento / Metricas de clasificacion)</b>
<b>Pruebas</b>
Puntuacion F1           : 89.53%
Perdida                 : 0.41
Precision               : 88.37%
Casos con neumonia      : 95.48% (For positive class)
</pre>

##### Matriz de confusion: 
<kbd>
<img src=https://github.com/anjanatiha/Detection-of-Pneumonia-from-Chest-X-Ray-Images/blob/master/demo/report/CM.png alt="Confusion Matrix" width=800px height=600px>
</kbd>

#### Herramientas / Librerias
<pre>
Lenguaje de desarrollo    : Python
Herramientas/IDE          : Anaconda
Librerias                 : Keras, TensorFlow, Inception, ImageNet
</pre>

#### Dates
<pre>
Current Version         : v1.0
Last Update             : 25/11/2022
</pre>