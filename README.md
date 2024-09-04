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
 - **Verificar e Tratar Dados Faltantes:** Verifique se há dados ausentes nas colunas relevantes (TOTALREV, TFEDREV, TSTREV, TLOCREV) e trate-os adequadamente (por exemplo, substituindo por média/mediana ou removendo linhas incompletas).
 - **Converter Tipos de Dados:** Certifique-se de que as colunas numéricas estejam no formato correto.
 
 #### 2) Divisão dos Dados em Treino e Teste:
- **Dividir em Variáveis Dependentes e Independentes**
- **Dividir em Treino e Teste**

#### 3) Treinamento do Modelo:
   - **Treinar o Modelo de Regressão Linear**

#### 4) Avaliação do Modelo:
  - **Predições no conjunto de teste** 

#### 5) Interpretação dos resultados:
  - Avaliação do desempenho do modelo utilizando a métrica de Acurácia.

#### 6) Implementação e Resultados:
  - **Coeficientes:** Cada coeficiente da regressão linear indica o quanto a TOTALREV é afetada por uma unidade adicional em TFEDREV, TSTREV, ou TLOCREV
  - **R²:** O valor de R² indica a proporção da variabilidade da TOTALREV que é explicada pelo modelo.
  - **RMSE e MAE:** Avaliam a precisão das predições feitas pelo modelo.

#### 7) Ajuste e Melhoria do Modelo (Opcional)
- **Transformações de Dados:** Se necessário, considere transformar as variáveis (por exemplo, log-transformar) para melhorar o ajuste do modelo.
- **Cross-Validation:** Realize validação cruzada para garantir que o modelo seja robusto em diferentes subconjuntos dos dados.

## [Documentação](https://github.com/GislaineMartins/Students-Performance/wiki)

