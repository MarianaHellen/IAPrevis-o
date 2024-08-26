# Previsão de Score de Crédito

Este projeto desenvolve um modelo de inteligência artificial para prever o score de crédito de clientes de um banco. O objetivo é classificar automaticamente os clientes em categorias como "Ruim", "Ok" e "Bom", com base em suas informações financeiras e comportamentais.

## Descrição do Projeto

O projeto realiza uma análise detalhada do perfil dos clientes, utilizando diversas variáveis para treinar um modelo preditivo. A partir dos dados disponíveis, são criados modelos de machine learning que permitem classificar os clientes de acordo com o risco de crédito, auxiliando a instituição financeira na tomada de decisões.

## Bibliotecas Utilizadas

As seguintes bibliotecas Python foram utilizadas no desenvolvimento do projeto:

- **pandas**: Manipulação e análise de dados.
- **scikit-learn**: Construção do modelo de machine learning, incluindo:
  - `train_test_split`: Divisão do conjunto de dados em treino e teste.
  - `RandomForestClassifier`: Classificador usado para prever o score de crédito.
  - `KNeighborsClassifier`: Outro classificador utilizado no modelo.
  - `LabelEncoder`: Conversão de dados categóricos em valores numéricos.
  - `accuracy_score`: Métrica para avaliar a precisão do modelo.
