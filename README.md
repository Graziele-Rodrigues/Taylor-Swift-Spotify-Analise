# Taylor-Swift-Spotify-Analise

Este repositório contém um código em Python para análise de dados relacionados à artista Taylor Swift e suas músicas. O código realiza as seguintes etapas:

## 1. Importando bibliotecas
O código começa importando as bibliotecas necessárias, incluindo pandas, numpy, matplotlib e seaborn, para manipulação e visualização de dados.

## 2. Lendo os dados
Os dados são lidos de um arquivo CSV usando o pandas e armazenados em um DataFrame.

## 3. Limpeza dos dados
Algumas colunas são removidas do DataFrame, incluindo a coluna 'ARTIST' e a coluna de índice.

## 4. Análise exploratória de dados
O código realiza várias análises exploratórias de dados, incluindo:

- Visualização da distribuição da popularidade das músicas.
- Avaliação da popularidade por álbum, mostrando um gráfico de barras.
- Identificação das 10 músicas mais populares.
- Exploração da relação entre as características das músicas, como energia, dançabilidade e valência.
- Criação de um heatmap para visualizar a correlação entre diferentes características das músicas.

## 5. Modelagem preditiva
O código também inclui uma seção dedicada à modelagem preditiva para prever a popularidade das músicas com base em suas características. Ele utiliza modelos de regressão linear para isso.

6. Avaliação do modelo
Após a criação dos modelos, o código avalia seu desempenho usando o coeficiente de determinação  e o erro quadrático médio (RMSE).

Este código oferece uma análise abrangente dos dados de Taylor Swift e demonstra técnicas de análise de dados, visualização e modelagem preditiva em Python usando bibliotecas populares como pandas, seaborn e scikit-learn.

## Licença

Esse código tem como licença o MIT