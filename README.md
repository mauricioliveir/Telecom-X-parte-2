 # 📊 Telecom Churn Prediction Analytics
**Desafio Telecom X II | Programa ONE + Alura**

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11%2B-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Library-Pandas%20|%20Sklearn%20|%20XGBoost-orange" alt="Libraries">
  <img src="https://img.shields.io/badge/ONE%20%2B%20Alura-Challenge%20Telecom%20X%20II-brightgreen" alt="ONE + Alura">
</p>

---

## 🎯 Objetivos
- Identificar padrões de clientes que cancelam serviços (**Churn**)
- Desenvolver modelos preditivos com **Recall > 80%**
- Gerar insights acionáveis para **reduzir evasão em 25%**

---

## 🔍 Métricas dos Modelos
| Modelo               | Recall | AUC-ROC | Precisão |
|----------------------|--------|---------|----------|
| Regressão Logística  | 80%    | 0.76    | 50%      |
| Random Forest        | 45%    | 0.68    | 65%      |
| XGBoost              | 70%    | 0.75    | 55%      |

---

## 🛠️ Tecnologias
- **Pandas**: Limpeza e transformação de dados
- **Scikit-learn**: Modelos de machine learning
- **XGBoost**: Algoritmos de boosting
- **Matplotlib/Seaborn**: Visualização de dados

---

## 📌 Insights Chave
**Fatores com maior impacto no Churn**:
1. Contratos mensais aumentam 3x o risco de cancelamento
2. Clientes sem suporte técnico premium tem 60% mais churn
3. Planos com valor acima de $75/mês tem retenção 40% menor

**Recomendações**:
- Converter contratos para anuais com desconto
- Criar pacotes de suporte técnico inclusos
- Desenvolver planos intermediários ($50-$70)

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-purple" alt="License">
</p>
