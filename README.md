# Projeto-Previs-o-Ibov

Objetivo:
Criar um modelo que preveja se o fechamento do IBOVESPA do dia 
seguinte será maior ou menor que o do dia atual. Deve prever a tendência (↑ ou ↓) com acuracidade mínima 
de 75% em um conjunto de teste. O conjunto de testes deverá conter o último 
mês (30 dias) de dados disponíveis

##  Fonte de Dados
Fonte: (https://br.investing.com/indices/bovespa-historical-data)
Como obter: Baixar um intervalo de 2 anos e selecionar o período 'diário'.
Período utilizado: 04/12/2023 - 03/12/2025 [2 anos]

## Resultados
- Acuracidade de 80% últimos 30 dias
- Previsão D+1: Queda, índice: 160,1

## Estrutura
1. Análise exploratória;
2. Ajustes na base para utilização da biblioteca Prophet;
3. Criação de média móvel últimos 3 dias para ajudar a bilioteca;
4. Gridsearch para descobrir melhores parâmetros e ajuste de um parâmetro (change_point_prior_scale) para melhor acuracidade;
5. Criação do gráfico com matplotlib mostrando previsão;
6. Criação do backtesting com iniício após 180 dias para validar mais ainda nosso modelo.

## Tecnologias
Python, pandas, prophet, numpy, intertools, gridsearch, ipython, matplotlib, sklearn

## Autor
Ygor Azevedo Carneiro
Linkedin: https://www.linkedin.com/in/ygorac/
