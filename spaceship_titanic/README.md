# Projeto Kaggle - Spaceship Titanic
Este projeto é a minha submissão para a competição [Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic) do Kaggle.
O objetivo é prever quais passageiros foram transportados para outra dimensão com base nos dados disponíveis.

## Pipeline do Projeto
O notebook `Spaceship.ipynb` inclui:
- Análise Exploratória e Visualização dos Dados.
- Pré-processamento: tratamento de valores nulos e imputação com média/mediana.
- Engenharia de Features: criação da coluna `TotalSpent` e separação da coluna `Cabin`.
- Codificação de variáveis categóricas com One-Hot Encoding (`get_dummies`).
- Padronização dos dados com `StandardScaler` para otimizar o modelo.
- Treinamento de um modelo de **Regressão Logística**.

## Resultado
O modelo alcançou uma acurácia de **78.15%** .
