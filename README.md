# Churn-Em-Plataforma-de-Streaming
LINK PARA O PROJETO: https://colab.research.google.com/drive/1WQQAOR9R_4MLZO-mmucq6MqsDor_umBB?usp=sharing

# Projeto de Previsão de Churn - Plataforma de Streaming

Este projeto utiliza Machine Learning para prever o churn (cancelamento de planos) de usuários de uma plataforma de streaming.

## Tecnologias Utilizadas

- **Google Colab**: Ambiente de desenvolvimento para rodar o notebook de Machine Learning.
- **Python**: Linguagem de programação utilizada para implementação.
- **Pandas**: Biblioteca para manipulação e análise de dados.
- **Numpy**: Biblioteca para operações numéricas e geração de dados aleatórios.
- **Scikit-learn**: Biblioteca de Machine Learning para criação e treinamento do modelo.
- **Matplotlib** e **Seaborn**: Bibliotecas para visualização de dados.

## Como Rodar

1. **Abrir no Google Colab**:
   - Abra o notebook no [Google Colab](https://colab.research.google.com/drive/1WQQAOR9R_4MLZO-mmucq6MqsDor_umBB?usp=sharing).
   - Importe os dados e execute as células para rodar o modelo de previsão de churn.

2. **Rodar as Células**:
   - Execute as células do notebook uma por uma para ver os resultados do modelo.
   - As células de treinamento e avaliação do modelo estarão no início do notebook.

## Objetivo

Prever quais usuários de uma plataforma de streaming têm maior chance de cancelar o plano com base no seu comportamento de uso, como tempo assistido e categorias de conteúdo consumido.

## Como o Modelo Funciona

- O modelo utiliza um **Random Forest Classifier** para prever o churn (cancelamento de planos).
- O dataset fictício contém informações sobre os usuários, planos contratados, categorias de conteúdo e histórico de visualizações.

## Resultados

O modelo é avaliado utilizando as métricas:
- **Acurácia**
- **Relatório de Classificação** (Precisão, Recall, F1-Score)
- **Matriz de Confusão** para visualização dos acertos e erros do modelo.
