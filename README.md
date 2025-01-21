# 🚗 Predicción de Precios de Vehículos Usados

El servicio **Rusty Bargain** busca implementar una aplicación que permita a los usuarios estimar rápidamente el valor de mercado de sus vehículos. Este proyecto tiene como objetivo construir un modelo de machine learning que prediga con precisión el precio de mercado de los autos usados.

## 🎯 Objetivo del Proyecto
Desarrollar un modelo que cumpla con las siguientes métricas:
- Alta precisión en las predicciones.
- Rápida velocidad de predicción.
- Tiempo de entrenamiento optimizado.

## 📂 Estructura del Proyecto
1. **Preparación de Datos:**
   - Exploración inicial para identificar valores faltantes y corregir tipos de datos.
   - Limpieza de datos y tratamiento de valores atípicos.
   - Eliminación de columnas irrelevantes para optimizar el análisis.

2. **Exploración y Análisis de Datos:**
   - Análisis de distribuciones de precios, potencia del motor y año de registro.
   - Identificación y eliminación de outliers.

3. **Entrenamiento de Modelos:**
   - Comparación de cinco modelos:
     - **Regresión Lineal:** Usado como prueba base.
     - **Random Forest:** Mejora la captura de relaciones no lineales.
     - **LightGBM:** Excelente balance entre velocidad y precisión.
     - **CatBoost:** Ideal para manejar variables categóricas nativamente.
     - **XGBoost:** Competitivo incluso sin ajuste de hiperparámetros.

4. **Evaluación de Modelos:**
   - Métrica principal: RMSE (Root Mean Square Error).
   - Evaluación de velocidad de entrenamiento y predicción.

## 🚀 Resultados Destacados
- **Mejor Modelo:** LightGBM
  - **RMSE en Prueba:** 1986.73
  - **Tiempo de Entrenamiento:** 0.78 segundos
  - **Conclusión:** Mejor desempeño en términos de precisión y velocidad, ideal para implementaciones en producción.

## 🛠️ Tecnologías y Herramientas
- **Librerías de Python:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, LightGBM, CatBoost, XGBoost.
- **Técnicas Aplicadas:**
  - One-Hot Encoding para variables categóricas.
  - Normalización de datos.
  - Ajuste de hiperparámetros con GridSearchCV y RandomizedSearchCV.

## 📈 Métricas Clave
| Modelo            | RMSE (Entrenamiento) | RMSE (Prueba) | Tiempo de Entrenamiento |
|--------------------|-----------------------|---------------|--------------------------|
| Regresión Lineal   | 3192.27              | 72428814599.14| 0.36 segundos           |
| Random Forest      | 1034.33              | 2059.06       | 7.56 segundos           |
| LightGBM           | 1530.32              | **1986.73**   | **0.78 segundos**       |
| CatBoost           | 1968.57              | 2034.89       | 35.7 segundos           |
| XGBoost            | 1454.30              | 2040.23       | 18.39 segundos          |

## 📂 Estructura del Repositorio
- `notebooks/`: Jupyter Notebooks con el análisis y el entrenamiento de los modelos.
- `visualizations/`: Gráficas clave para analizar los datos y su estructura.
- `README.md`: Descripción del proyecto (este archivo).

## 🤝 Contribuciones
Si estás interesado en mejorar este proyecto, ¡no dudes en abrir un pull request o reportar un issue! 🚀

## 📬 Contacto
Miguel Angel Moctezuma Cedillo  
📧 [m_moctezumace@hotmail.com](mailto:m_moctezumace@hotmail.com)  
🌐 [Perfil de GitHub](https://github.com/MiguelMoc1)

---
¡Gracias por visitar este proyecto! 😃
