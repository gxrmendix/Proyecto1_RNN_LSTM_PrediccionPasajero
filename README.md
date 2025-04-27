# Proyecto 1: Predicción de Pasajeros de Aerolíneas usando LSTM

## Descripción del Proyecto

Este proyecto aplica un modelo de Red Neuronal Recurrente (RNN) con celdas LSTM (Long Short-Term Memory) para predecir el número mensual de pasajeros de aerolíneas, utilizando el clásico "Airline Passengers Dataset".

El objetivo es predecir secuencias temporales aprovechando la capacidad de las LSTM para capturar dependencias a largo plazo.

## Estructura del Repositorio

```
Proyecto1_RNN_LSTM_PrediccionPasajeros/
├── README.md
├── requirements.txt
├── notebook/
│   └─ proyecto_lstm_pasajeros.ipynb
├── data/
    └─ airline-passengers.csv
```

## Instrucciones de Ejecución

1. Clonar el repositorio:
```bash
git clone https://github.com/tu_usuario/Proyecto1_RNN_LSTM_PrediccionPasajeros.git
```

2. Instalar las dependencias:
```bash
pip install -r requirements.txt
```

3. Ejecutar el notebook `proyecto_lstm_pasajeros.ipynb` ubicado en la carpeta `notebook/`.

## Justificación del Uso de LSTM

Las redes LSTM son ideales para series de tiempo debido a su capacidad de manejar dependencias a largo plazo, evitando los problemas de desvanecimiento del gradiente que afectan a las RNN tradicionales. En este proyecto, LSTM permite predecir patrones estacionales y tendencias en el número de pasajeros.

## Justificación del Optimizador

Se utilizó el optimizador **Adam** debido a su adaptabilidad del aprendizaje y eficiencia computacional. Adam combina las ventajas de AdaGrad y RMSProp, siendo especialmente efectivo para problemas de secuencias temporales donde las actualizaciones de parámetros requieren ser más robustas.

## Resultados Principales

- Métricas de evaluación:
  - Error cuadrático medio (MSE)
  - Error absoluto medio (MAE)
  - Coeficiente de determinación (R2)

- El modelo ajustado logra un buen rendimiento en el conjunto de entrenamiento y mejora la generalización respecto al modelo inicial.

- Se observó una buena aproximación de las predicciones al comportamiento real de los datos.

## Dependencias Principales

- tensorflow
- keras
- numpy
- pandas
- matplotlib
- scikit-learn

## Autor

- **Nombre:** Victor A. Garmendia Fuentes
- **Curso:** Deep Learning
- **Fecha:** Abril 2025

---

Este repositorio forma parte del proyecto de entrega del curso de Deep Learning.
