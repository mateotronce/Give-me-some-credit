# Give-me-some-credit

# Give Me Some Credit - Análisis de Riesgo Crediticio

Este proyecto analiza el dataset "Give Me Some Credit" de Kaggle, explorando los factores que influyen en el riesgo crediticio. 

## Estructura del Proyecto
- **Exploración de Datos:** Carga del dataset, inspección general y limpieza inicial.
- **Visualización:** Histogramas, matriz de correlación y scatter plots para entender la relación entre variables.
- **Análisis Estadístico:** Descripción de las principales características del dataset.
- **Modelado Predictivo:** Implementación de modelos de Machine Learning para predecir el riesgo crediticio.

## Requisitos
- Python 3.x
- Librerías necesarias:
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn xgboost joblib
  ```

## Uso
Ejecuta el notebook `Give_me_some_credit.ipynb` para realizar el análisis exploratorio de datos (EDA) y entrenar modelos predictivos.

## Implementación del Modelo Predictivo
1. **Preprocesamiento de datos:** Limpieza, escalado y eliminación de valores nulos.
2. **División del dataset:** Entrenamiento (80%) y prueba (20%).
3. **Modelos probados:**
   - Regresión Logística
4. **Evaluación:** Precisión, AUC-ROC, y F1-score.

## Mejoras Sugeridas
- Refinar el preprocesamiento de datos.
- Implementar validación cruzada para mejorar la generalización.
- Desplegar el modelo en una API para predicciones en tiempo real.
- Guardado del modelo: Uso de `joblib` para almacenar el mejor modelo.



