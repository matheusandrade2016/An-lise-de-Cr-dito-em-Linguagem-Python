# Analise de Credito em Linguagem Python

## Pré-Processamento de dados

# Descrição:

Este repositório contém uma análise exploratória de dados de crédito com o objetivo de prever a probabilidade de inadimplência de clientes. O projeto abrange as seguintes etapas:

Coleta de Dados: Utilização de um conjunto de dados contendo informações de 1500 clientes, incluindo:
(*)ID do cliente
Renda
Idade
Valor do empréstimo
Histórico de pagamento (variável alvo: 0 - adimplente, 1 - inadimplente)

# Pré-processamento:

Limpeza: Remoção de duplicatas, tratamento de valores inconsistentes (ex: idade negativa) e outliers.

Tratamento de valores ausentes: Imputação de valores faltantes utilizando estratégias como média, mediana ou moda, dependendo da característica da variável.

Escalonamento: Normalização dos dados para garantir que todas as features tenham a mesma escala, utilizando técnicas como StandardScaler ou MinMaxScaler.

# Análise Exploratória de Dados (EDA):

Visualização: Criação de gráficos (histograma, scatter plot) para entender a distribuição das variáveis e identificar relações entre elas.

Estatísticas descritivas: Cálculo de medidas como média, mediana, desvio padrão para obter um resumo estatístico dos dados


## Tecnologias Utilizadas:

Linguagem: Python

Bibliotecas: pandas, numpy, matplotlib, seaborn, scikit-learn, plotly


