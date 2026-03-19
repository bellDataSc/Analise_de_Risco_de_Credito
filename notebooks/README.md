# Notebooks

Esta pasta contém os notebooks Jupyter utilizados para análise e desenvolvimento do projeto.

## Notebooks Disponíveis

### 1. Conjunto de Risco de Crédito
**Arquivo:** `conjunto_de_risco_de_crédito.ipynb`

Notebook principal contendo:
- Análise Exploratória de Dados (EDA)
- Limpeza e pré-processamento
- Engenharia de features
- Treinamento de modelos iniciais

### 2. Reamostragem
**Arquivo:** `reamostragem.ipynb`

Técnicas de balanceamento de classes:
- SMOTE (Synthetic Minority Over-sampling Technique)
- ClusterCentroids (undersampling)
- SMOTEENN (combinação de over e undersampling)

### 3. Crédito Risco Limpo
**Arquivo:** `crédito_risco_limpo.ipynb`

Versão otimizada do pipeline completo:
- Dados limpos
- Modelos finais
- Métricas de avaliação

## Como Executar

1. Instale as dependências:
```bash
pip install -r requirements.txt
```

2. Inicie o Jupyter:
```bash
jupyter notebook
```

3. Navegue até o notebook desejado e execute as células sequencialmente.
