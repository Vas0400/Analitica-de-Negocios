# Proyecto Final – Analítica de Negocios (EAFIT)

**Predicción de abandono (churn), segmentación y pronóstico de gasto de clientes de e-commerce**

**Integrantes:** Samuel Vásquez Atehortúa · Lucas Palacio · Jerónimo Estrada

## Enlaces
- 📓 Notebook en Colab: https://colab.research.google.com/drive/19N7Y8Po1DSTNBwGB84zAAB1cDhFs7m2V
- 🎥 Video: _(pegar link de YouTube)_
- 📊 Base de datos: [Customers Transactions – Kaggle](https://www.kaggle.com/datasets/fares279/customers-transactions)

## Modelos
| Modelo | Objetivo | Resultado |
|---|---|---|
| K-means | Segmentar clientes | 4 segmentos (alto valor, nuevos de bajo valor, inactivos, leales) |
| Árbol de Decisión | Predecir churn | Sensibilidad 87,2% · AUC 0,83 |
| Red Neuronal MLP | Predecir churn (comparación) | Sensibilidad 61,5% · AUC 0,74 |
| Red Neuronal MLP (regresión) | Pronosticar gasto total | R² 0,936 · MAE 119 USD |

## Archivos
- `Proyecto_Final_Analitica_Churn.ipynb`: portafolio completo (introducción, problema, objetivos, datos, modelos, resultados, discusión, limitaciones, ética, conclusiones, recomendaciones y bibliografía).
- `graficas/`: gráficas de resultados usadas en la presentación.
