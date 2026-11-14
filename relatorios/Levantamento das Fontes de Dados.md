## Fonte de dados – Default of Credit Card Clients
Fonte: UCI Machine Learning Repository – Default of Credit Card Clients.

Link: https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients.

Observação: os dados são de clientes de Taiwan, de 2005. Portanto, servem muito bem para desenvolver e demonstrar o projeto, mas não representam necessariamente o comportamento atual dos consumidores brasileiros.

## Descrição da fonte de dados
O conjunto de dados Default of Credit Card Clients está disponibilizado gratuitamente no UCI Machine Learning Repository, uma plataforma acadêmica que reúne conjuntos de dados utilizados em pesquisas e projetos de análise de dados e Machine Learning.

A base contém informações de 30.000 clientes de cartão de crédito de Taiwan, referentes ao ano de 2005. Seu principal objetivo é permitir o estudo dos fatores associados à inadimplência, considerando características demográficas, limites de crédito, histórico de pagamentos e valores das faturas.

Os dados permitem investigar padrões de comportamento financeiro dos clientes e identificar quais características apresentam maior associação com a ocorrência de inadimplência no mês seguinte.

## Tipos de dados disponíveis
Os dados são classificados como estruturados, pois estão organizados em linhas e colunas, permitindo sua leitura e manipulação por ferramentas como Excel, Google Sheets, Python, Power BI e bibliotecas de análise de dados.

Formato dos dados: a base está disponível em formato tabular, podendo ser baixada e utilizada em arquivos compatíveis com ferramentas de análise, como CSV e XLSX.

## Métodos para acessar e coletar os dados
A coleta pode ser realizada diretamente pelo site do UCI Machine Learning Repository, sem necessidade de autenticação ou utilização de ferramentas de scraping.

Os principais métodos são:

1. Download direto

O usuário acessa a página do conjunto de dados e realiza o download dos arquivos disponibilizados. Essa é a maneira mais simples de obter os dados.

2. Acesso por Python

Também é possível utilizar bibliotecas como ucimlrepo para importar os dados diretamente para um ambiente Python, sem precisar baixar e importar manualmente o arquivo.



## Descrição das variáveis do conjunto de dados

### Identificação e informações pessoais

ID: Identificador único de cada cliente.

LIMIT_BAL: Valor do limite de crédito concedido ao cliente.

SEX: Sexo do cliente (1 = masculino; 2 = feminino).

EDUCATION: Nível de escolaridade do cliente (1 = pós-graduação; 2 = universidade; 3 = ensino médio; 4 = outros).

MARRIAGE: Estado civil do cliente (1 = casado; 2 = solteiro; 3 = outros).

AGE: Idade do cliente, em anos.

### Histórico de pagamentos

As colunas abaixo representam a situação do pagamento das faturas nos últimos seis meses.

PAY_0: Situação do pagamento em setembro de 2005.

PAY_2: Situação do pagamento em agosto de 2005.

PAY_3: Situação do pagamento em julho de 2005.

PAY_4: Situação do pagamento em junho de 2005.

PAY_5: Situação do pagamento em maio de 2005.

PAY_6: Situação do pagamento em abril de 2005.

Os valores representam o histórico de pagamento: valores positivos indicam a quantidade de meses de atraso, enquanto valores negativos e zero representam outras situações de pagamento registradas na base.

### Valores das faturas

Representam os valores das faturas mensais dos clientes nos últimos seis meses.

BILL_AMT1: Valor da fatura de setembro de 2005.

BILL_AMT2: Valor da fatura de agosto de 2005.

BILL_AMT3: Valor da fatura de julho de 2005.

BILL_AMT4: Valor da fatura de junho de 2005.

BILL_AMT5: Valor da fatura de maio de 2005.

BILL_AMT6: Valor da fatura de abril de 2005.

### Valores pagos

Representam os pagamentos realizados pelos clientes em cada um dos últimos seis meses.

PAY_AMT1: Valor pago em setembro de 2005.

PAY_AMT2: Valor pago em agosto de 2005.

PAY_AMT3: Valor pago em julho de 2005.

PAY_AMT4: Valor pago em junho de 2005.

PAY_AMT5: Valor pago em maio de 2005.

PAY_AMT6: Valor pago em abril de 2005.

### Variável-alvo

default_payment_next_month: Indica se o cliente apresentou inadimplência no mês seguinte (0 = não apresentou inadimplência; 1 = apresentou inadimplência).