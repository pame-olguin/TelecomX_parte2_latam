# 📊 Predicción de Cancelación de Clientes

Este proyecto aplica técnicas de machine learning para identificar los factores que influyen en la cancelación de clientes y construir modelos predictivos que permitan anticipar este comportamiento. El objetivo es apoyar decisiones estratégicas de retención y mejorar la comprensión del perfil de clientes en riesgo.

---

## 🧠 Objetivo

- Analizar el comportamiento de cancelación de clientes.
- Evaluar distintos modelos de clasificación.
- Identificar las variables más influyentes.
- Proponer estrategias de retención basadas en los resultados.

---

## 🧪 Modelos utilizados

- **Regresión Logística**
- **Random Forest**
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**
- **XGBoost**

Cada modelo fue evaluado con métricas como accuracy, precision, recall, F1-score y matriz de confusión. Se aplicó balanceo de clases y normalización cuando fue necesario.

---

## 📊 Comparación de modelos

| Modelo               | Accuracy | Recall (Cancelación) | F1-score (Cancelación) |
|----------------------|----------|-----------------------|-------------------------|
| Regresión Logística  | 0.77     | **0.68**              | **0.61**                |
| Random Forest        | 0.77     | 0.61                  | 0.59                    |
| SVM (LinearSVC)      | 0.76     | 0.76                  | 0.63                    |
| XGBoost              | 0.78     | 0.70                  | 0.64                    |

---

## 🔍 Variables más influyentes

| Variable                     | Impacto |
|------------------------------|---------|
| Tipo_contrato_Mensual        | Alta    |
| Antiguedad_meses             | Alta    |
| Tipo_internet_Fibra óptica   | Alta    |
| Cargos_mensuales             | Alta    |
| Cargos_totales               | Media   |
| Seguridad_en_linea           | Media   |
| Soporte_tecnico              | Media   |

---

## 📈 Estrategias de retención propuestas

- Incentivar contratos anuales o bianuales.
- Campañas de fidelización para clientes nuevos.
- Revisión de cargos mensuales y percepción de valor.
- Promoción de servicios complementarios.
- Activación de alertas para clientes en riesgo.

---

## 📌 Conclusiones

El modelo XGBoost mostró el mejor rendimiento general, mientras que la regresión logística y SVM ofrecieron mayor interpretabilidad. Las variables más relevantes fueron el tipo de contrato, antigüedad y tipo de internet. Estas conclusiones permiten diseñar estrategias de retención más efectivas y personalizadas.

---

## 🛠️ Tecnologías utilizadas

- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn
- Google Colab


