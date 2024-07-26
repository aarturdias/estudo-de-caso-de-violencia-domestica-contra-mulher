# Análise Exploratória de Dados (EDA) sobre Violência Doméstica contra a Mulher

## Descrição

Este repositório contém uma Análise Exploratória de Dados (EDA) focada em compreender os padrões, tendências e características da violência doméstica contra a mulher. A análise foi realizada utilizando um conjunto de dados abrangente.

## Objetivos

- Explorar e entender a distribuição dos casos de violência doméstica contra a mulher.
- Identificar padrões e tendências ao longo do tempo.
- Analisar características demográficas das vítimas e agressores.
- Investigar a relação entre diferentes variáveis e a incidência de violência.
- Gerar visualizações que facilitem a interpretação dos dados.

## Conteúdo do Repositório

- `data/`: Contém os conjuntos de dados utilizados na análise.
- `notebooks/`: Notebooks Jupyter com as etapas da análise exploratória.
- `README.md`: Este arquivo, com informações sobre o projeto.

## Ferramentas Utilizadas

- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Jupyter Notebook
- SkLearning

## Resultados

A Análise Exploratória de Dados (EDA) revelou padrões importantes sobre a violência doméstica contra a mulher. Utilizando a Regressão Logística como algoritmo de modelagem, alcançamos uma acurácia de 75,18%. Esta acurácia indica que o modelo foi capaz de classificar corretamente 75,18% dos casos no conjunto de dados de teste. Este resultado sugere que o modelo tem um bom desempenho na predição da ocorrência de violência doméstica com base nas características analisadas. No entanto, é importante considerar outras métricas de avaliação, como precisão, recall e F1-score, para obter uma visão mais completa do desempenho do modelo. A análise também destacou a necessidade de dados adicionais e mais detalhados para melhorar a precisão e a utilidade prática das previsões.

### ACURÁCIA DOS MODELOS
- Regressão Logística 75.18%
- Random Forest 74.39%
- XGBoost 73.79%
- LGBM 73.18%
- KNN 72.93%
- SVC 72.60%
- Árvore de decisão 67.17%
- Navie Bayes 53.89%


### DataSet retirado em:
  
  https://www.kaggle.com/datasets/fahmidachowdhury/domestic-violence-against-women
