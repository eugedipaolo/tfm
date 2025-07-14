# tfm
Trabajo de Fin de Máster de María Eugenia Di Paolo, correspondiente al Máster en Inteligencia Artificial por la UNIR. El proyecto consiste en una investigación comparativa sobre el desempeño de diversos modelos de ML y DL para predecir la demanda de sangre según el tipo sanguíneo

Evaluar la capacidad predictiva de  para predecir la necesidad de transfusiones según el tipo de sangre, incluso en ausencia de una etiqueta directa, utilizando una variable proxy construida a partir de criterios clínicos.

## Contenido

- Limpieza y transformación de datos hospitalarios
- Construcción de la variable proxy `needs_transfusion`
- Análisis exploratorio de datos
- Entrenamiento de modelos de ML (StackingRegressor)
- Entrenamiento de modelos de DL (redes LSTM)
- Evaluación y comparación de métricas

## Tecnologías utilizadas

- Python 3.x
- Pandas, NumPy, Scikit-learn
- TensorFlow, Keras
- Matplotlib, Seaborn
- Jupyter Notebook

##  Estructura del repositorio

├── analisis_transfusiones.ipynb # Notebook principal con todo el análisis
├── README.md # Este archivo
├── requirements.txt # Lista de dependencias
└── datos/

## Instrucciones de uso

1. Abrir el notebook:

   ```bash
   jupyter notebook analisis_transfusiones.ipynb

Licencia
Este proyecto está licenciado bajo los términos de la licencia MIT.

