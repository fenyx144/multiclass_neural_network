# Multiclass Neural Network with Iris Dataset 🌼

Una implementación desde cero de una red neuronal básica utilizando **Python** y **NumPy**. Este proyecto se centra en la clasificación multiclase usando el famoso conjunto de datos **Iris**, ideal para principiantes en inteligencia artificial y ciencia de datos.

## ✨ Características
- Clasificación multiclase en el conjunto de datos Iris.
- Codificación one-hot para etiquetas.
- Normalización de características con StandardScaler.
- Entrenamiento mediante retropropagación.
- Evaluación de desempeño con métricas como precisión, recall y F1-score.

## 📂 Estructura del proyecto
El proyecto está organizado en las siguientes secciones:
1. **Carga de datos**: Utilización del dataset Iris de scikit-learn.
2. **Preprocesamiento**: Normalización y codificación de etiquetas.
3. **Definición del modelo**: Inicialización de parámetros y funciones de activación.
4. **Entrenamiento**: Implementación de retropropagación.
5. **Evaluación**: Reporte de métricas y desempeño en el conjunto de prueba.

## 🚀 Cómo usar
1. Clona este repositorio:
    ```bash
   git clone https://github.com/tu_usuario/multiclass-neural-network.git
    ```
2. Instala las dependencias necesarias y ejecuta el script:
    ```bash
    pip install numpy scikit-learn
    python multiclass_nn.py
    ```
## 📊 Ejemplo de salida
    Pérdida durante el entrenamiento:
    ```bash
        Epoch 0, Loss: 1.0986
        Epoch 100, Loss: 0.6432
        Epoch 200, Loss: 0.4321
        ...
    ```
Reporte de clasificación:
```bash
Reporte de Clasificación:
              precision    recall  f1-score   support

     setosa       1.00      1.00      1.00        15
 versicolor       0.93      0.87      0.90        15
  virginica       0.88      0.93      0.90        15

  accuracy                           0.93        45
 macro avg       0.93      0.93      0.93        45
weighted avg 0.93 0.93 0.93 45
```
## 📘 Recursos
- [Documentación de scikit-learn](https://scikit-learn.org/)
- [Fundamentos de redes neuronales](https://en.wikipedia.org/wiki/Artificial_neural_network)
- [Dataset Iris en Kaggle](https://www.kaggle.com/uciml/iris)

## 🛠️ Contribuciones
Las contribuciones son bienvenidas. Si encuentras un problema o tienes una idea para mejorar este proyecto, no dudes en abrir un **issue** o enviar un **pull request**.

