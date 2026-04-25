# 💳 Fraud Detection with Machine Learning

## 🚀 Overview

Este projeto aplica técnicas de Machine Learning para detectar **fraudes em transações financeiras**, um problema clássico de **classificação desbalanceada**.

O foco não é apenas prever corretamente, mas **identificar fraudes com alta sensibilidade (recall)** — algo crítico em cenários reais.

---

## 📊 Dataset

* Fonte: Credit Card Fraud Dataset (TensorFlow / Kaggle)
* Contém transações reais anonimizadas
* Forte desbalanceamento (~0.17% de fraudes)

---

## 🎯 Objetivo

Construir modelos capazes de:

* Detectar fraudes com alto **recall**
* Minimizar falsos negativos
* Balancear precisão e sensibilidade

---

## 🧠 Técnicas Utilizadas

### 🔹 Modelagem

* Regressão Logística
* Random Forest
* XGBoost

### 🔹 Tratamento de dados

* Feature Engineering (`log`, scaling)
* SMOTE (oversampling)
* Undersampling

### 🔹 Avaliação

* ROC-AUC
* Precision-Recall Curve
* Ajuste de threshold

### 🔹 Interpretabilidade

* SHAP (explicação das previsões)

---

## 📈 Principais Insights

* 📉 **Accuracy é enganosa** em dados desbalanceados
* 🎯 Ajustar o **threshold** melhora significativamente o recall
* ⚖️ Técnicas de balanceamento impactam diretamente o desempenho
* 🚀 XGBoost apresentou melhor performance geral
* 🔍 SHAP mostrou quais variáveis mais influenciam o modelo

---

## 📊 Resultados (exemplo)

| Métrica         | Valor      |
| --------------- | ---------- |
| ROC-AUC         | ~0.98      |
| Recall (fraude) | Alto       |
| Precision       | Balanceada |

> ⚠️ Em detecção de fraude, **recall é mais importante que accuracy**

---

## 🧪 Como Executar

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost shap imbalanced-learn
```

Abra o notebook no Google Colab ou Jupyter e execute as células.

---

## 🛠️ Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* SHAP

---

## 📌 Diferenciais do Projeto

✔ Tratamento explícito de dados desbalanceados
✔ Comparação entre múltiplos modelos
✔ Ajuste de threshold (nível profissional)
✔ Uso de SHAP para interpretabilidade
✔ Estrutura organizada e reprodutível

---

## 🧠 Aprendizados

Este projeto reforça que:

* Modelos não devem ser avaliados apenas por accuracy
* Entender o problema é tão importante quanto modelar
* Interpretabilidade é essencial em aplicações reais

---

## 📬 Contato

Se quiser trocar ideia sobre dados ou projetos:

* LinkedIn: (https://www.linkedin.com/in/felipe-luna-581377152/)
* GitHub: (https://github.com/Flip-data96)

---

⭐ Se este projeto te ajudou ou chamou atenção, considere dar uma estrela!
