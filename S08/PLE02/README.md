# Canalización de Datos para el Modelo de Regresión Lineal

Este proyecto implementa una canalización de datos para entrenar y evaluar un modelo de regresión lineal que predice las calorías quemadas durante un entrenamiento. El modelo es elegido entre 3 opciones, que son entrenadas y evaluadas tras u.na limpieza del conjunto de datos en un análisis exploratorio de datos (EDA)

## Estructura del Proyecto

El proyecto tiene la siguiente estructura de archivos:

- `modelo_regresion_lineal.pkl`: Archivo que contiene el modelo de regresión lineal entrenado.
- `ple02_gimnasio_procesados.csv`: Conjunto de datos procesados.
- `ple02_gimnasio.csv`: Conjunto de datos original.
- `ple02_n01_eda.ipynb`: Notebook de análisis exploratorio de datos (EDA).
- `ple02_n02_seleccion_modelo.ipynb`: Notebook de selección y evaluación del modelo.
- `X_test.csv`, `X_train.csv`, `y_test.csv`, `y_train.csv`: Conjuntos de datos de entrenamiento y prueba.
- `README.md`: Este archivo.
- `requirements.txt`: Archivo con las dependencias necesarias para el proyecto.

## Ejecución de la Canalización de Datos

Para ejecutar la canalización de datos y entrenar el modelo de regresión lineal, se deben seguir los siguientes pasos:

1. **Instalar las dependencias**: Asegurarse de tener instaladas las bibliotecas necesarias. Puedes instalarlas usando `pip`:

   ```sh
   pip install pandas scikit-learn matplotlib numpy joblib
   ```

   Alternativamente, se pueden instalar estas dependencias a través del archivo **requirements.txt** contenido en este mismo repositorio:

```sh
pip install -r requirements.txt
```

2. **Ejecutar el análisis exploratorio de datos (EDA)**: Se debe abrir y ejecutar el notebook `ple02_n01_eda.ipynb` para realizar el análisis exploratorio de datos.

3. **Seleccionar y entrenar el modelo**: Abrir y ejecutar el notebook `ple02_n02_seleccion_modelo.ipynb` para seleccionar, entrenar y evaluar el modelo de regresión lineal. Este notebook también guardará el modelo entrenado en `modelo_regresion_lineal.pkl`.

4. **Visualizar las predicciones atípicas**: Dentro del notebook `ple02_n02_seleccion_modelo.ipynb`, se incluye el código para visualizar las predicciones y las predicciones atípicas.

5. **Evaluar el modelo**: Utiliza los archivos `X_test.csv` y `y_test.csv` para evaluar el rendimiento del modelo cargado desde `modelo_regresion_lineal.pkl`.

## Notas

- Asegurarse de que los archivos CSV (`X_test.csv`, `X_train.csv`, `y_test.csv`, `y_train.csv`) estén en el mismo directorio que los notebooks para que puedan ser cargados correctamente.
- El archivo `modelo_regresion_lineal.pkl` se genera al ejecutar el notebook `ple02_n02_seleccion_modelo.ipynb`.

- Dentro de cada notebook, se ofrece una explicación detallada de cada uno de los pasos que se van tomando para llegar a la elección del modelo final para realizar las predicciones.
