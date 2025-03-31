# Energy Efficiency Prediction with MLP

Este proyecto utiliza un **Multilayer Perceptron (MLP)** para predecir la **carga de calefacción (Heating Load)** de edificios en función de sus características físicas y térmicas. El dataset proviene del **UCI Machine Learning Repository** y contiene 768 muestras con 8 características de entrada.

## Dataset
El dataset incluye las siguientes características de entrada:
- **X1**: Compacidad relativa del edificio
- **X2**: Área de superficie total (m²)
- **X3**: Área de pared total (m²)
- **X4**: Área del techo (m²)
- **X5**: Altura total del edificio (m)
- **X6**: Orientación (categoría de 2 a 5)
- **X7**: Área de acristalamiento total (m²)
- **X8**: Distribución del acristalamiento (categoría de 0 a 5)

La variable objetivo es **Y1**: Heating Load (Carga de calefacción), que es lo que se intenta predecir.

## Modelo
El modelo MLP es entrenado utilizando las características anteriores para predecir la carga de calefacción. El entrenamiento se realiza utilizando **scikit-learn** y **TensorFlow**.

## Resultados
El rendimiento del modelo se evalúa utilizando métricas como la precisión en la predicción de la carga de calefacción.
