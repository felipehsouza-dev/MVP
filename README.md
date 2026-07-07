# MVP 

Este repositório contém o MVP (Minimum Viable Product) desenvolvido para a disciplina de **Machine Learning & Analytics**. O objetivo principal é construir um pipeline de classificação binária capaz de antecipar o cancelamento de contratos (*churn*) em uma empresa de SaaS.

## 📋 Estrutura do Repositório

* `churn_clientes_saas.csv`: Dataset público gerado e utilizado para o treinamento dos modelos.
* `MVP_Machine_Learning.ipynb`: Notebook contendo todo o ciclo de desenvolvimento do modelo (Análise Exploratória, Pré-processamento, Treinamento, Otimização e Avaliação).

## 🛠️ Tecnologias e Bibliotecas Utilizadas

* **Linguagem:** Python 3
* **Manipulação e Visualização:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Pipelines, ColumnTransformer, GridSearchCV, etc.)

## 🎯 Modelos Avaliados

O projeto avalia o desempenho de três abordagens distintas:
1. **Baseline:** `DummyClassifier` (Chute da classe majoritária)
2. **Modelo Linear:** `LogisticRegression`
3. **Modelo Baseado em Árvores:** `RandomForestClassifier` (Otimizado via Grid Search)

A principal métrica de validação utilizada foi o **F1-Score**, devido à natureza do problema de Churn.
