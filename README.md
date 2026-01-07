# TelecomX Churn Analysis

Análisis de churn de clientes para TelecomX usando Python/Pandas en Google Colab.

## 📊 Dataset
- **Fuente**: TelecomX_Data.json (7043 registros, JSON anidados)
- **Objetivo**: Predecir `Churn` (Yes/No)
- **Columnas**: 48 (customer, phone, internet, account features)

## 🔧 ETL Realizado
✅ Carga JSON desde GitHub raw URL

✅ Flatten JSON anidados con pd.json_normalize()

✅ Conversión dtypes: object → int/category

✅ Columnas binarias: Yes/No → 0/1

text

## 📈 Próximos pasos (EDA)
- Análisis univariado Churn
- Correlaciones y feature importance
- Visualizaciones con seaborn/matplotlib
- Insights para reducir cancelaciones
