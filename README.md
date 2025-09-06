# Projeto de Análise Exploratória de Dados (EDA) - IMDb
## 1. Visão Geral 
Este projeto tem como objetivo realizar uma Análise Exploratória de Dados (EDA) do dataset de filmes do IMDb, a fim de extrair insights, identificar padrões e responder a perguntas de negócio sobre fatores que influenciam o sucesso de um filme.
Além da EDA, o projeto inclui pré-processamento, modelagem preditiva e predição de novas entradas, permitindo estimar métricas como a nota IMDB de um filme com base em suas características.

## 2. Estrutura do Projeto 
Para executar a análise, você precisará de um ambiente Python com as bibliotecas necessárias e o arquivo de dados original.

- desafio_indicium_imdb.csv: O arquivo de dados que contém as informações sobre os filmes.

- O código Python (que pode ser em um arquivo .py ou em um Jupyter Notebook).

## 3. Tecnologias Utilizadas 
O código foi desenvolvido em Python e utiliza as seguintes bibliotecas:

Pandas: Manipulação e limpeza dos dados.

NumPy: Operações numéricas.

Matplotlib: Criação de gráficos estáticos.

Seaborn: Visualizações estatísticas avançadas e estéticas.

Scikit-learn: Pré-processamento, OneHotEncoder, MultiLabelBinarizer, RandomForestRegressor e métricas de avaliação.

Joblib: Para salvar e carregar o modelo treinado e o MultiLabelBinarizer.


Para instalar as dependências, utilize o comando abaixo:


- pip install pandas matplotlib seaborn scikit-learn joblib

## 4. Instruções de Uso

Arquivo de Dados: Coloque desafio_indicium_imdb.csv no mesmo diretório do seu script Python ou Notebook.
Execução: Execute o código. O script realiza automaticamente:
Carregamento e visualização inicial dos dados.
Limpeza e tratamento de colunas numéricas e categóricas.
Tratamento especial da coluna Genre com múltiplos valores.
Separação entre variáveis de entrada (X) e alvo (y).
Divisão entre treino e teste.
Criação de pipeline com pré-processamento e RandomForestRegressor.
Treinamento do modelo e avaliação de métricas (MAE, RMSE, R²).
Predição de novos filmes com alinhamento de colunas.
Geração de gráficos e visualizações, salvos em .png.
