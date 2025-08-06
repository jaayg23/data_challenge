# data_challenge

By: Jacobo Ayala

Proyecto para detectar posibles candidatos a adquirir un CDT para bancos.

## Estructura del repositorio

- **data/**
  - **raw/**: Datos originales sin procesar (ej: DATASET_CHALLENGE.csv)
  - **processed/**: Datos procesados y listos para análisis/modelado (ej: cdts_analysis.csv, cdts_prediction.csv)
- **notebooks/**
  - **0.0-data_challenge-introduction.ipynb**: Introducción y contexto del reto de datos
  - **1.0-data_challenge_visualization.ipynb**: Visualización y análisis exploratorio de los datos
  - **ML_dataset/**: Notebooks de modelos de machine learning
    - **tree_decision.ipynb**: Árboles de decisión
    - **svm.ipynb**: Support Vector Machine
- **enviroment.yml**: Archivo para crear el entorno conda con las dependencias necesarias
- **requirements.txt**: (Vacío o para dependencias adicionales vía pip)

## Instalación

1. Clona este repositorio:
   ```bash
   git clone <url-del-repositorio>
   ```
2. Crea el entorno conda:
   ```bash
   conda env create --file enviroment.yml
   conda activate data_challenge
   ```
3. (Opcional) Instala dependencias adicionales con pip:
   ```bash
   pip install -r requirements.txt
   ```

## Uso

- Ejecuta los notebooks en la carpeta `notebooks/` para explorar los datos, visualizar resultados y probar modelos de machine learning.
- Los datos procesados y crudos se encuentran en la carpeta `data/`.

## Licencia
