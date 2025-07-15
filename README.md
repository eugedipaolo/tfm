# TFM
Trabajo de Fin de Máster de María Eugenia Di Paolo, correspondiente al Máster en Inteligencia Artificial por la UNIR. El proyecto consiste en una investigación comparativa sobre el desempeño de diversos modelos de ML y DL para predecir la demanda de sangre según el tipo sanguíneo

Evaluar la capacidad de modelos de ML y DL para predecir la necesidad de transfusiones según el tipo de sangre, incluso en ausencia de una etiqueta directa, utilizando una variable proxy construida a partir de criterios clínicos.

## Contenido

- Limpieza y transformación de datos hospitalarios
- Construcción de la variable proxy `needs_transfusion`
- Análisis exploratorio de datos
- Entrenamiento de modelos de ML para la predicciíon de cada tipo de sangre (StackingRegressor)
- Entrenamiento de modelos de DL para la predicciíon de cada tipo de sangre (redes LSTM)
- Evaluación y comparación de métricas

## Tecnologías utilizadas

- Python 3.12.4
- Pandas, NumPy, Scikit-learn
- TensorFlow, Keras
- Matplotlib, Seaborn
- XGBoost, LightGBM, CatBoost
- Statsmodels
- Jupyter Notebook

##  Estructura del repositorio

eda.ipynb: Análisis exploratorio de los datos. Incluye visualizaciones de la distribución de grupos sanguíneos, evolución temporal, análisis de estacionalidad y generación de la variable proxy needs_transfusion.

demanda_O_pos.ipynb: Modelo predictivo para la demanda de sangre del tipo O⁺.

demanda_O_neg.ipynb: Modelo predictivo para la demanda de sangre del tipo O⁻.

demanda_A_pos.ipynb: Modelo para tipo A⁺.

demanda_A_neg.ipynb: Modelo para tipo A⁻.

demanda_B_pos.ipynb: Modelo para tipo B⁺.

demanda_B_neg.ipynb: Modelo para tipo B⁻.

demanda_AB_pos.ipynb: Modelo para tipo AB⁺.

demanda_AB_neg.ipynb: Modelo para tipo AB⁻.

HDHI Admission data.csv: Conjunto de datos base utilizado para todos los análisis y modelos.

README.md # Este archivo

Autor
María Eugenia Di Paolo
Máster en Inteligencia Artificial — UNIR (2025)

