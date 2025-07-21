# Análisis de Sismos en Chile (1950–2025)

Este proyecto analiza los sismos de magnitud mayor o igual a 7 ocurridos en Chile entre 1950 y febrero de 2025. El objetivo principal es estudiar su evolución temporal y su distribución según el horario en que ocurrieron (hábil o no hábil), con el fin de generar insights útiles para la gestión del riesgo sísmico.

## 📌 Objetivos

- Analizar la evolución de los sismos ≥ 7 Richter cada 5 años.
- Clasificar los eventos según si ocurrieron en horario hábil o no hábil.
- Evaluar la distribución geográfica y temporal de los eventos.
- Generar una narrativa de riesgo basada en la ocurrencia horaria.
- Aplicar modelos de Machine Learning para predecir la ocurrencia en horario hábil.

## 🧱 Estructura del Proyecto

1. **Carga y limpieza de datos** desde un dataset público.
2. **Conversión de fechas** a zona horaria chilena.
3. **Clasificación de horario hábil** (lunes a viernes, 07:30–19:30).
4. **Análisis exploratorio** con visualizaciones.
5. **Modelado predictivo** con Random Forest y selección de variables.
6. **Evaluación de modelos** con métricas como AUC, F1 y curvas ROC/PR.

## ⚙️ Tecnologías utilizadas

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Imbalanced-learn
- Workalendar (para feriados en Chile)

Este proyecto analiza los sismos de magnitud mayor o igual a 7 ocurridos en Chile entre 1950 y febrero de 2025. El objetivo principal es estudiar su evolución temporal y su distribución según el horario en que ocurrieron (hábil o no hábil), con el fin de generar insights útiles para la gestión del riesgo sísmico.

## 📌 Objetivos

- Analizar la evolución de los sismos ≥ 7 Richter cada 5 años.
- Clasificar los eventos según si ocurrieron en horario hábil o no hábil.
- Evaluar la distribución geográfica y temporal de los eventos.
- Generar una narrativa de riesgo basada en la ocurrencia horaria.
- Aplicar modelos de Machine Learning para predecir la ocurrencia en horario hábil.

## 🧱 Estructura del Proyecto

1. **Carga y limpieza de datos** desde un dataset público.
2. **Conversión de fechas** a zona horaria chilena.
3. **Clasificación de horario hábil** (lunes a viernes, 07:30–19:30).
4. **Análisis exploratorio** con visualizaciones.
5. **Modelado predictivo** con Random Forest y selección de variables.
6. **Evaluación de modelos** con métricas como AUC, F1 y curvas ROC/PR.

## ⚙️ Tecnologías utilizadas

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Imbalanced-learn
- Workalendar (para días feriados en Chile)
