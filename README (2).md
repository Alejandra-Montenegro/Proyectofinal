# 🎬 Proyecto 3: Sistema de Recomendación Híbrido con Deep Learning

## 📌 Descripción del Proyecto

Este proyecto propone el desarrollo de un **sistema de recomendación híbrido** para una **plataforma de streaming**, con el objetivo de mejorar la retención de usuarios mediante recomendaciones personalizadas y relevantes. El sistema responde a la problemática de que muchos usuarios abandonan la plataforma debido a recomendaciones irrelevantes.

---

## 🧠 Solución de Inteligencia Artificial

Se implementó un enfoque híbrido que integra distintas técnicas de IA para ofrecer recomendaciones más precisas y personalizadas:

- ✅ **Filtrado Colaborativo Profundo** (Neural Matrix Factorization)
- ✅ **Filtrado Basado en Contenido** (CNN para imágenes, NLP para sinopsis)
- ✅ **Modelado Secuencial** (LSTM/GRU para comportamiento temporal)
- ✅ **Factores Contextuales** (hora del día, dispositivo, ubicación)
- ✅ **Multi-Task Learning** (rating y duración de visualización)
- ✅ **Cold Start Solution** con técnicas de *Few-Shot Learning*

---

## 🗂️ Datasets Utilizados

- [x] Datos simulados de streaming
- [ ] MovieLens 25M
- [ ] Netflix Prize Dataset
- [ ] IMDb metadata

---

## 📁 Estructura del Repositorio

```
ProyectoFinal/
├── README.md
├── requirements.txt
├── data/
│   └── movie_titles.csv
├── src/
│   ├── neural_network.py
│   ├── data_preprocessing.py
│   ├── experiments.py
│   └── utils.py
├── notebooks/
│   ├── 01_implementacion_red.ipynb
│   ├── 02_experimentacion.ipynb
│   └── 03_analisis_resultados.ipynb
├── results/
│   ├── training_curves.png
│   ├── training_accuracy.png
│   ├── performance_comparison.csv
│   └── architecture_analysis.png
└── docs/
    └── reporte_tecnico.md
```

---

## 🧪 Metodología de Trabajo

1. Implementación desde cero de red neuronal Feedforward con NumPy.
2. Adaptación al problema de predicción de ratings.
3. Comparación de arquitecturas, funciones de activación y tasas de aprendizaje.
4. Evaluación con métricas de regresión.
5. Análisis de escalabilidad y proyección a TensorFlow/Keras.

---

## 📊 Entregables

- ✅ Modelo híbrido funcional
- ✅ Notebooks con experimentación comparativa
- ✅ Resultados visuales de entrenamiento y evaluación
- ✅ Reporte técnico (2 páginas)
- ✅ API y dashboard (en desarrollo)

---

## 📌 Requisitos

- Python 3.10+
- NumPy
- Pandas
- Matplotlib
- scikit-learn

Instalar dependencias:

```bash
pip install -r requirements.txt
```

---

## 🚀 Ejecución

Ejecuta los notebooks en orden desde la carpeta `/notebooks`:

1. `01_implementacion_red.ipynb` → Red neuronal desde cero
2. `02_experimentacion.ipynb` → Pruebas y comparaciones
3. `03_analisis_resultados.ipynb` → Visualización de desempeño

---

## 🤖 Autora

**Alejandra Montenegro**  
Maestría en Inteligencia Artificial  
Universidad de Especialidades Espíritu Santo  
Año: 2025
