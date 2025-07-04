# Churn-Em-Plataforma-de-Streaming

**LINK PARA O PROJETO**: [Google Colab](https://colab.research.google.com/drive/1WQQAOR9R_4MLZO-mmucq6MqsDor_umBB?usp=sharing)

## Projeto de Previsão de Churn - Plataforma de Streaming

Este projeto utiliza Machine Learning para prever o churn (cancelamento de planos) de usuários de uma plataforma de streaming, com base em seu comportamento de uso, como tempo assistido e categorias de conteúdo consumido.

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

1. **Criação de Dados Fictícios**: O modelo utiliza um dataset gerado aleatoriamente, com informações sobre os usuários, planos contratados, categorias de conteúdo e histórico de visualizações.
2. **Pré-processamento**:
   - **Transformação de variáveis categóricas**: Variáveis como gênero, tipo de assinatura e gênero do conteúdo são convertidas em valores numéricos.
   - **Normalização**: Algumas variáveis contínuas, como idade e horas assistidas, são normalizadas para garantir que todas as variáveis estejam na mesma escala.
3. **Modelo de Machine Learning**: O **Random Forest Classifier** é utilizado para prever o churn dos usuários.
4. **Avaliação do Modelo**: O modelo é avaliado utilizando:
   - **Acurácia**: Para medir a precisão do modelo.
   - **Relatório de Classificação**: Com as métricas de precisão, recall e F1-score.
   - **Matriz de Confusão**: Para visualizar os acertos e erros do modelo.

## Resultados

O modelo é avaliado utilizando as seguintes métricas:
- **Acurácia**: Medida da precisão global do modelo.
- **Relatório de Classificação**:
  - **Precisão**: Percentual de previsões corretas para a classe "Cancelado".
  - **Recall**: Percentual de cancelamentos realmente previstos pelo modelo.
  - **F1-Score**: Média harmônica entre precisão e recall.
- **Matriz de Confusão**: Exibe a quantidade de acertos e erros das previsões.

## Melhorias Futuras

- Experimentar diferentes modelos de Machine Learning, como **Gradient Boosting** ou **XGBoost**, para melhorar o desempenho.
- Testar técnicas de **balanceamento de classes**, como **SMOTE**, caso o churn esteja desbalanceado.
- Implementar **Ajuste de Hiperparâmetros** usando técnicas como **GridSearchCV** ou **RandomizedSearchCV**.
- **Análise de Feature Importance** para entender quais variáveis mais influenciam a previsão do churn.

## Contribuição

Se você deseja contribuir para o projeto, fique à vontade para fazer um fork, abrir issues ou enviar pull requests. Todas as contribuições são bem-vindas!

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.
