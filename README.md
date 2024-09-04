# US_Education_Finances - Kaggle

## Descrição do Projeto de Análise de Dados

### Título: Análise e Regressão de Dados 

### Introdução
Este projeto foi desenvolvido com o objetivo de responder à pergunta: Como posso estimar a TOTALREV (Receita total) de um distrito escolar com base nas receitas federais (TFEDREV), estaduais (TSTREV) e locais (TLOCREV)? Utilizando um modelo de Regressão Linear. Os dados foram retirados da plataforma Kaggle, um repositório popular de datasets para análise de dados e aprendizado de máquina. A formulação foi feita da seguinte maneira: TOTALREV como variável dependente e TFEDREV, TSTREV, TLOCREV como variáveis independentes.

### Pergunta de Pesquisa
A pergunta que buscamos responder neste projeto é: Como posso estimar a TOTALREV (Receita total) de um distrito escolar com base nas receitas federais (TFEDREV), estaduais (TSTREV) e locais (TLOCREV)?

### Metodologia
 #### 1) Carregar e preparar os dados:
 Os dados foram obtidos da plataforma Kaggle, a partir do dataset US Education Finances.
 O dataset contém informações abrangentes sobre 374161 registros para sistemas de escolas públicas. Todos os valores, exceto para associação de outono e renda pessoal, são expressos em milhares de dólares. Os dados de associação de outono são apresentados em valores inteiros. Os totais de renda pessoal são expressos em milhões de dólares. Dentre as variaveis estão: # estado, Associação de Outono, nome da escola, data por ano, Receita total do ensino fundamental secundario, Receita total de fontes federais, Receita total de fontes estaduais, Receita total de fontes locais, Despesas totais atuais com instrução, Despesas correntes totais para serviços de suporte, Outras despesas correntes e Despesa total de desembolso de capital.
 - **Importar os Dados:** Carregue a planilha CSV contendo os dados das receitas e despesas escolares.
 - Verificar e Tratar Dados Faltantes: Verifique se há dados ausentes nas colunas relevantes (TOTALREV, TFEDREV, TSTREV, TLOCREV) e trate-os adequadamente (por exemplo, substituindo por média/mediana ou removendo linhas incompletas).
 - Converter Tipos de Dados: Certifique-se de que as colunas numéricas estejam no formato correto.
 
 #### 2) Pré-processamento dos Dados:
- Limpeza dos dados, incluindo tratamento de valores ausentes e inconsistências.
- Transformação de variáveis categóricas em variáveis numéricas (codificação).
- Normalização/Padronização dos dados para otimizar o desempenho do modelo de classificação.

#### 3) Análise Exploratória dos Dados (EDA):
   - Visualização dos dados para identificar padrões, tendências e possíveis outliers.
   - Estatísticas descritivas para entender melhor a distribuição das variáveis.

#### 4) Modelagem e Treinamento:
  - Seleção do modelo de classificação adequado (Árvore de Decisão, K-Nearest Neighbours e Naïve Bayes).
  - Divisão dos dados em conjuntos de treinamento e teste.
  - Treinamento do modelo utilizando o conjunto de treinamento.

#### 5) Avaliação do Modelo:
  - Avaliação do desempenho do modelo utilizando a métrica de Acurácia.

#### 6) Implementação e Resultados:
  - Implementação do modelo de classificação para prever GradeClass que é a variavel para classificar os estudantes.
  - Interpretação dos resultados e resposta à pergunta de pesquisa.

## Resultados

- O modelo de classificação atingiu uma acurácia de **94%** no conjunto de teste.
- Observando a acurácia é possivel perceber que a proporção de previsões corretas feitas pelo modelo em relação ao total de previsões foi de quase 100%.
- Ao inserir novos dados de novos alunos podemos concluir que o modelo será capaz de prever a classificação de alunos em grupos com 94% de acerto.
