# Projeto de Predição de Score de Crédito
Este projeto tem como objetivo desenvolver um modelo preditivo para estimar o score de crédito utilizando Regressão Linear. O foco é aplicar técnicas de pré-processamento e normalização de dados, além de avaliar o desempenho do modelo preditivo.

## Conteúdo do Projeto

### Pré-processamento dos Dados
Normalização dos dados utilizando:
  - StandardScaler
  - MinMaxScaler
- Codificação de variáveis categóricas com **LabelEncoder**
- Separação dos dados em conjunto de treino e teste com **train_test_split**

### Criação e Avaliação do Modelo
- Utilização do algoritmo LinearRegression da biblioteca sklearn.
- Avaliação do modelo com a métrica R² (r2_score).

### Bibliotecas Utilizadas
``pandas: Manipulação de dados``
matplotlib e seaborn: Visualização de dados
numpy: Operações matemáticas
scikit-learn: Ferramentas para machine learning e pré-processamento
Passos para Reproduzir o Projeto
Clone o repositório e instale as dependências necessárias:

bash
Copiar código
git clone <url_do_repositorio>
cd <nome_do_projeto>
pip install -r requirements.txt
Execute o notebook Credit_score.ipynb:

bash
Copiar código
jupyter notebook Credit_score.ipynb
Siga as seções do notebook:

Realize o pré-processamento dos dados.
Crie e avalie o modelo preditivo.
Como Funciona o Modelo
O modelo de Regressão Linear é treinado com dados normalizados para prever o score de crédito.
A métrica R² é usada para avaliar a qualidade do ajuste do modelo, indicando o quão bem ele explica a variabilidade dos dados.
Possíveis Melhorias
Testar outros algoritmos, como Árvores de Decisão ou Random Forest.
Realizar uma análise mais aprofundada de correlações entre variáveis.
Adicionar mais métricas de avaliação, como MAE ou RMSE
