<h3 align="center">Instituto Tecnológico de Aeronáutica - ITA</h3>

<h3 align="center">Introdução a Ciência de Dados - CMC-13</h3>

<h3 align="center">Alunos: Fernando Zanchitta, Guilherme Kowalczuk, Rafael Frisch e Yuri Gama</h3>

---

# Laboratório de Exame

## 1. Objetivo

Exercitar e fixar conhecimentos adquiridos sobre Ciência de Dados uma base de dados fornecida.

## 2. Descrição do Trabalho

### 2.1. Base de dados (dataset)

O dataset incluem dados sobre imóveis no Reino Unido e seus preço (em Libras esterlinas). Utilizando os dados disponíveis, prepare os dados e separe-os em dois conjuntos: treino e validação (para ajsutes de hiperparâmetros). Os dados incluem: Price; House-Type; Area (square feets); Bedrooms; Bathrooms; Receptions; City-County; Postal Code. A descrição dos dados e o arquivo de dados está disponível no Google Classroom. Mais informações sobre o dataset estão disponíveis no arquivo real_estate.txt.

A preparação de dados deve verificar a existência de dados faltantes ou inconsistentes e definir como trata-los (se houver). Deve-se também avaliar a relevância de cada campo para a realização de uma melhor estimativa do preço, inclusive com análise exploratória de dados usando gráficos.

### 2.2. Tarefas a Realizar

#### 2.2.1. Preparação dos Dados

Avalie se todos os campos são úteis para o trabalho. Se houver campos não úteis, exclua-os dando justificativa. Faça uma análise exploratória dos dados. Prepare os dados para serem apresentados aos modelos de estimativa (regressores).Os dados podem ter atributos faltantes ou com imprecisões em seu valor (ruído). Separe-os em dois conjuntos: treino e validação (para ajsutes de hiperparâmetros).

#### 2.2.2. Modelo baseado em Redes Neurais do tipo MLP (MultiLayer Perceptron)

Crie um modelo baseado em Redes Neurais do tipo MLP (MultiLayer Perceptron) para estimar o preço do imóvel, dadas as outras informações da linha.

#### 2.2.3. Modelo baseado em Árvores de Decisão ou Em Florestas Aleatórias (Random Forests)

Crie um modelo baseado em Árvores de Decisão ou Em Florestas Aleatórias (Random Forests) ou outra técnica vista no curso (K-NN, redes bayesianas, etc) para estimar o preço do imóvel, dadas as outras informações da linha.

#### 2.2.4. Análise Comparativa do desempenho dos modelos

Avalie comparativamente os dois modelos, utilize medidas apropriadas de desempenho de modelos (RMSE, MAE, MAPE, R2, etc). Discuta os resultados e qual seria o modelo mais apropriado.

Verifique o desempenho nos dados de treinamento e validação. Há variação de desempenho significativa? Em caso positivo, explique porquê.

#### 2.2.5. Aplicação da predição do Modelo Desenvolvido

Criar um trecho de código para aplicar o modelo gerado a um arquivo de dados não
conhecido a priori, mas com mesmo formato do arquivo de dados fornecido (UK_real_estate.csv). Observe que o arquivo de dados deverá ser preparado pelo código para ser apresentado ao regressor, de modo similar ao feito no item 1. O nome do arquivo de dados de testes será `UK_real_estate_test.csv`.

## 3. Material a ser Entregue e Prazo

Deve ser entregue um jupyter notebook (formato .ipynb) com descrição, comentários e código-fonte

OBS: Entregar através do Google Classroom! Não compacte o arquivos em um zip (ou qq outro formato),
    A. Notebook com descricão, comentários e código-fonte (ver detalhes abaixo)

Prazo de Entrega: 12/julho/2023;

### 3.1. Estrutura do Notebook

OBS:(arquivo em jupyter Notebook ) Intercarlar células(tags) de texto e código fonte observando estrutura indicada abaixo. Comentar o código nas célula de código

**Título: Lab. Exame - CMC-13**

**Equipe: Nomes do membros da Equipe**

1. **Preparação dos dados.** Descrever procedimentos realizados para concluir esta tarefa
1. **Modelo baseado em Redes Neurais do tipo MLP (MultiLayer Perceptron).** Descrever procedimentos realizados para concluir esta tarefa.
1. **Modelo baseado em Árvores de Decisão ou Em Florestas Aleatórias (Random Forests).** Descrever procedimentos realizados para concluir esta tarefa.
1. **Análise Comparativa do desempenho dos modelos.** Apresente os dados e discussões sobre os resultados, inclusive dados sobre o desempenho no dataset de treino e testes.
1. **Aplicação da predição do Modelo Desenvolvido.** Trecho de código para uso do modelo desenvolvido aplicado a um arquivo de dado do mesmo formato do arquivo de dados fornecido (`UK_real_estate.csv`). O nome do arquivo de dados de testes será `UK_real_estate_test.csv`.
1. **Conclusões.** Comentários e sugestões sobre o trabalho (complexidade/facilidade, sugestões, etc.).
