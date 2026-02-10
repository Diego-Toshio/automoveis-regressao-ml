# Comparação de Modelos de Regressão para Previsão de Preço de Automóveis

## 📌 Contexto
A precificação de automóveis depende de diversos fatores técnicos e estruturais,
como potência do motor, consumo, dimensões e tipo de combustível.
Compreender como essas características influenciam o preço é essencial para
análises no setor automotivo e apoio à tomada de decisão.

Este projeto compara diferentes abordagens de regressão aplicadas à previsão
do preço de automóveis.

## 🎯 Objetivo
Desenvolver e comparar modelos de regressão para estimar o preço de automóveis,
avaliando o impacto de:
- Modelos lineares
- Técnicas de regularização
- Modelos não lineares

## 📊 Dataset
O dataset contém informações técnicas e estruturais de automóveis, incluindo
atributos relacionados ao motor, consumo, dimensões e preço de venda.

A variável-alvo do problema é o **preço do automóvel**.

## 🧠 Abordagem
- Análise Exploratória de Dados (EDA)
- Pré-processamento e tratamento dos dados
- Treinamento de diferentes modelos de regressão
- Avaliação de desempenho por métricas apropriadas
- Análise dos resíduos para diagnóstico dos modelos

## 🤖 Modelos Utilizados
- Regressão Linear
- Regressão com Regularização L1 (Lasso)
- Regressão com Regularização L2 (Ridge)
- Rede Neural para regressão

## 📈 Resultados
Os resultados evidenciam diferenças claras entre abordagens lineares,
regularizadas e não lineares.

- A regularização contribuiu para maior estabilidade dos modelos
- Modelos não lineares capturaram relações mais complexas
- A análise dos resíduos auxiliou na avaliação da qualidade do ajuste

## 🛠️ Tecnologias
- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn

## 📁 Estrutura do Repositório
automoveis-regressao-ml/
- Automoveis_Regressao_Comparacao_Profissional_v2.ipynb
- README.md

## 📌 Observações
Este projeto demonstra a comparação entre técnicas clássicas e modelos
mais avançados de regressão aplicados a um problema real de previsão de preços.
