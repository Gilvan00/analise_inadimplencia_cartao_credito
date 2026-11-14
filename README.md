# Análise de Inadimplência em Cartões de Crédito

## Sobre o projeto

Este projeto tem como objetivo analisar o comportamento financeiro de clientes de cartão de crédito e identificar padrões associados à inadimplência. Também foram desenvolvidos modelos de Machine Learning para avaliar a capacidade de prever quais clientes apresentam maior risco de não pagamento.

A proposta é utilizar dados para gerar informações relevantes que possam apoiar a tomada de decisões, a gestão de crédito e a prevenção de inadimplência.

## Objetivos

Analisar o perfil dos clientes.

Identificar padrões no histórico de pagamentos.

Investigar a relação entre comportamento financeiro e inadimplência.

Desenvolver e comparar modelos de Machine Learning.

Apresentar insights e recomendações estratégicas.

## Base de dados

Foi utilizada a base pública Default of Credit Card Clients, disponibilizada pela Universidade Nacional de Taiwan por meio do repositório UCI Machine Learning Repository.

A base contém informações de 30.000 clientes, incluindo limite de crédito, dados demográficos, histórico de pagamentos, valores das faturas e pagamentos realizados.

Fonte: UCI Machine Learning Repository

## Tecnologias utilizadas

Python

PySpark

Matplotlib

Seaborn

Google Looker Studio

Git e GitHub

## Etapas do projeto

Levantamento e compreensão do problema.

Identificação da fonte de dados.

Exploração e preparação dos dados.

Análise exploratória e identificação de padrões.

Desenvolvimento de modelos de Machine Learning.

Avaliação e comparação dos modelos.

Construção de dashboard interativo.

Elaboração de insights e recomendações.

## Modelos desenvolvidos

Foram utilizados três algoritmos de classificação:

Regressão Logística.

Árvore de Decisão.

Random Forest.

Os modelos foram avaliados por meio de métricas como acurácia, recall e AUC, considerando especialmente a capacidade de identificar clientes inadimplentes.

## Resultados

Os modelos apresentaram acurácia superior a 80%. Entretanto, a análise demonstrou que a acurácia isolada não é suficiente para avaliar a capacidade de identificar clientes inadimplentes.

O Random Forest apresentou AUC de aproximadamente 0,77 e recall de aproximadamente 33,89% para a classe de inadimplentes, evidenciando oportunidades de melhoria na identificação de clientes com maior risco.

## Dashboard

Foi desenvolvido um dashboard no Google Looker Studio para apresentar os principais resultados da análise, dividido em três áreas:

Perfil e Visão Geral dos Clientes.

Comportamento Financeiro e Inadimplência.

Insights e Recomendações Estratégicas.

Link do dashboard: https://datastudio.google.com/reporting/28ecf7a5-005e-49f4-a737-56db4e90a6c2

## Estrutura do repositório

dados/: informações sobre a base de dados.

notebooks/: notebooks de análise e Machine Learning.

relatorios/: documentos e relatórios do projeto.

dashboard/: documentação e link do dashboard.

imagens/: capturas de tela e imagens dos resultados.

## Considerações finais

O projeto permitiu aplicar técnicas de análise de dados e Machine Learning em um problema de negócio realista, demonstrando como informações históricas podem contribuir para a identificação de padrões de risco e apoiar estratégias de prevenção à inadimplência.

Os resultados também reforçam a importância de avaliar diferentes métricas e aprimorar continuamente os modelos preditivos.
