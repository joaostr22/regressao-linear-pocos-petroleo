# Seleção de Poços de Petróleo via Regressão Linear e Análise de Risco

## 🎯 Objetivo

Prever reservas de petróleo em três regiões e estimar lucro dos poços, usando bootstrapping para avaliar risco e escolher a região mais lucrativa.

## 🧠 Como fiz o projeto

Treinei modelos de regressão linear para cada região, validei o desempenho com RMSE e selecionei os 200 poços com maior retorno previsto entre 500 analisados. Usei 1.000 simulações de bootstrapping para calcular lucro esperado, intervalo de confiança e probabilidade de prejuízo, recomendando a melhor região com base em risco < 2,5%.

## 🚀 Tecnologias
- Python
- Pandas
- NumPy
- Scikit-Learn (Linear Regression)
- Bootstrapping manual

## 📦 Como instalar
```bash
git clone https://github.com/joaostr22/regressao-linear-pocos-petroleo.git
cd regressao-linear-pocos-petroleo
