# Analise de Credito em Linguagem Python

## Pré-Processamento de dados

# Descrição:

Este repositório contém uma análise exploratória de dados de crédito com o objetivo de prever a probabilidade de inadimplência de clientes. O projeto abrange as seguintes etapas:

Coleta de Dados: Utilização de um conjunto de dados contendo informações de 1500 clientes, incluindo:
1. ID do cliente
2. Renda
3. Idade
4. Valor do empréstimo
5. Histórico de pagamento (variável alvo: 0 - adimplente, 1 - inadimplente)

# Pré-processamento:

1. Limpeza: Remoção de duplicatas, tratamento de valores inconsistentes (ex: idade negativa) e outliers.

2. Tratamento de valores ausentes: Imputação de valores faltantes utilizando estratégias como média, mediana ou moda, dependendo da característica da variável.

3. Escalonamento: Normalização dos dados para garantir que todas as features tenham a mesma escala, utilizando técnicas como StandardScaler ou MinMaxScaler.

# Análise Exploratória de Dados (EDA):

1. Visualização: Criação de gráficos (histograma, scatter plot) para entender a distribuição das variáveis e identificar relações entre elas.

2. Estatísticas descritivas: Cálculo de medidas como média, mediana, desvio padrão para obter um resumo estatístico dos dados


## Tecnologias Utilizadas:

Linguagem: Python
Bibliotecas: pandas, numpy, matplotlib, seaborn, scikit-learn, plotly
Autor: Matheus Andrade Moreira
