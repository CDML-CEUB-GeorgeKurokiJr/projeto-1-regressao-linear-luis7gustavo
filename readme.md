# 🚖 Previsão Dinâmica de Tarifas
## Uber & Lyft em Boston

> Projeto de Ciência de Dados focado na modelagem e análise de preços dinâmicos no setor de mobilidade urbana.

---

## 📌 Sobre o Projeto

Este projeto tem como objetivo prever o valor das tarifas das plataformas Uber e Lyft na cidade de Boston, utilizando técnicas de análise exploratória de dados (EDA) e modelos de Machine Learning.

A proposta é entender:

- Quais variáveis mais impactam o preço da corrida
- Como fatores externos influenciam a tarifa
- Como construir um modelo preditivo eficiente
- Quais insights estratégicos podem ser extraídos para tomada de decisão

---

## 🎯 Objetivos

- 📊 Analisar o comportamento das tarifas
- 🧠 Construir modelos preditivos
- 📈 Avaliar métricas de performance
- 💰 Gerar insights financeiros e estratégicos

---

## 🗂️ Estrutura do Projeto

```
📁 data/                -> Conjunto de dados utilizados
📁 notebooks/           -> Análise exploratória e modelagem
📁 models/              -> Modelos treinados
📄 README.md            -> Documentação do projeto
```

---

## 🧪 Metodologia

### 1️⃣ Análise Exploratória (EDA)

- Tratamento de valores nulos
- Análise de distribuição de preços
- Correlação entre variáveis
- Identificação de outliers

### 2️⃣ Engenharia de Features

- Transformação de variáveis categóricas
- Normalização / Padronização
- Seleção de variáveis relevantes

### 3️⃣ Modelagem

Foram testados modelos como:

- Regressão Linear
- Random Forest
- Modelos baseados em árvores

### 4️⃣ Avaliação

As principais métricas utilizadas foram:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

---

## 📊 Resultados

O modelo final apresentou:

- ✅ Boa capacidade preditiva
- 📉 Redução significativa de erro em comparação ao baseline
- 📈 Alto poder explicativo das variáveis principais

---

## 💡 Principais Insights de Negócio

Alguns fatores que mais impactam o preço:

- ⏰ Horário da corrida
- 🌧️ Condições climáticas
- 📍 Local de origem e destino
- 🚗 Tipo de serviço selecionado
- 📊 Nível de demanda (surge pricing)

### Insights estratégicos:

- A demanda influencia fortemente o aumento de tarifas.
- Condições climáticas elevam o preço médio das corridas.
- Regiões com maior fluxo apresentam maior variabilidade de preço.

---

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📈 Possíveis Melhorias Futuras

- Implementar modelos mais robustos (XGBoost, LightGBM)
- Deploy do modelo via API (FastAPI)
- Construção de dashboard interativo (Streamlit ou Power BI)
- Análise temporal mais aprofundada

---

## 👨‍💻 Autor

**Luis Gustavo**  
---

## 🚀 Como Executar o Projeto

```bash
# Clone o repositório
git clone https://github.com/seuusuario/seurepositorio.git

# Instale as dependências
pip install -r requirements.txt

# Execute o notebook
jupyter notebook
```

---


