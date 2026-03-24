# Miniproyecto #1 DeepLearning

Desarrollado por:

- María Clara Ávila

- Mateo Giraldo

- Miguel Lugo

- Hector Sanjuan

Antes de empezar con el análisis exploratorio, es necesario que tengamos contexto del tema que vamos a abordar.


El dataset utilizado para este proyecto reposa en `Kaggle` y puede acceder a el mediante este enlace: https://www.kaggle.com/competitions/avazu-ctr-prediction

## Objetivo

Construir un modelo de clasificación supervisada usando MLP (Multilayer Perceptron/Red Neuronal Multicapa) para predecir si un usuario hará clic en un anuncio móvil (click = 1) o no (click = 0). Se comparará el desempeño de los modelos construidos con scikit-learn y PySpark. Además, se aplicará LIME para interpretar predicciones individuales del modelo.

## Variables disponibles

`id`: identificador del anuncio

`click`: indicador de si hubo clic

`hour`: hora de la impresión del anuncio (formato YYMMDDHH)

`C1`: variable categórica anonimizada

`banner_pos`

`site_id`, `site_domain`, `site_category`

`app_id`, `app_domain`, `app_category`

`device_id`,`device_ip`, `device_model`

`device_type`, `device_conn_type`

`C14–C21`: variables categóricas anónimas