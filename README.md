# Análise de Dados Comercial

## Descrição
Este projeto apresenta uma análise aplicada a um conjunto de dados fictícios do setor Comercial de uma empresa e visa construir visualizações para compreender a performance de vendas por diferentes ângulos e extrair insights a respeito dessas vendas.

## KPIs do setor Comercial
- Volume de vendas
- Ticket Médio
- Taxa de conversão
- Ciclo de vendas
- Retenção de clientes
- Lucratividade
- Produtividade da equipe de vendas
- Satisfação do cliente

## Resultados de performance a serem obtidos
- Total de vendas por segmento
- Total de vendas por fabricante
- Total de vendas por categoria
- Total de vendas por vendedor

## Estrutura do Projeto
1. Carregamento, leitura e tratamento de dados
  - Conjunto de dados `Dados_Comerciais.xlsx` é carregado utilizando a biblioteca `pandas`.
  - Inspeção das colunas e tipos de dados
  - Verificação de integridade dos dados

2. Análise Exploratória
- Segmento **Doméstico** possui maior volume de vendas que os demais.
- Concentração desbalanceada de receita entre os fabricantes.
- Discrepância notável de faturamento entre a categoria **Eletrodomésticos** que possui maior parte de vendas totais em cima das outras categorias.
- Evidências de possível adoção de estratégias para potencializar o crescimento nos segmentos menos explorados e categorias com maior potencial de crescimento.

## Requisitos
- Python 3.x
- Bibliotecas:
  - pandas
  - matplotlib
  - plotly
