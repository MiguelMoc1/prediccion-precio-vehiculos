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
  - **RMSE en Prueba:** 40.56
  - **Tiempo de Entrenamiento:** 2.60 segundos
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
| Regresión Lineal   | 53.46                 | 53.45         | 1.78 segundos            |
| Random Forest      | 32.27                 | 41.03         | 390.85 segundos          |
| LightGBM           | 37.95                 | **40.56**     | **2.60 segundos**        |
| CatBoost           | 1645.05               | 1700.44       | N/A                      |
| XGBoost            | 40.18                 | 41.36         | 1.45 segundos            |

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
