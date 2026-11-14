## Relatório de Insights – Análise de Inadimplência de Clientes de Cartão de Crédito

### Principais descobertas da análise

A análise dos dados permitiu identificar aspectos importantes sobre o comportamento financeiro dos clientes e a capacidade de prever a inadimplência. O conjunto de dados reúne informações sobre limite de crédito, valores das faturas, pagamentos realizados, histórico de atrasos e características dos clientes.

Entre os principais achados, destacam-se:

1. Histórico de pagamentos como indicador de risco

O histórico de pagamentos representa uma informação importante para identificar possíveis situações de inadimplência. Clientes que apresentam atrasos recorrentes podem representar um risco maior para a instituição financeira, tornando esse histórico uma variável relevante para a análise de crédito.

2. Importância do comportamento financeiro

Os valores das faturas e dos pagamentos realizados permitem acompanhar o comportamento financeiro dos clientes. A comparação entre esses valores pode ajudar a identificar situações em que os pagamentos não acompanham os valores cobrados nas faturas, indicando possíveis dificuldades financeiras.

3. Desempenho dos modelos de Machine Learning

Foram desenvolvidos e comparados três modelos de classificação: Regressão Logística, Árvore de Decisão e Random Forest.

Os resultados de acurácia foram superiores a 80% em todos os modelos:

Regressão Logística: 80,55%.

Árvore de Decisão: 81,55%.

Random Forest: 81,33%.

A Árvore de Decisão apresentou a maior acurácia, enquanto o Random Forest obteve o melhor resultado de AUC (0,7715), demonstrando maior capacidade de distinguir clientes com diferentes níveis de risco.

### Dificuldade na identificação de clientes inadimplentes

Um dos resultados mais importantes foi observado na matriz de confusão. Apesar da boa acurácia geral, os modelos apresentaram dificuldades para identificar corretamente os clientes que realmente se tornaram inadimplentes.

A Árvore de Decisão identificou corretamente 453 clientes inadimplentes, enquanto o Random Forest identificou 447 e a Regressão Logística apenas 288.

Isso demonstra que os modelos ainda deixam passar uma quantidade significativa de clientes que apresentam risco de inadimplência.

### Relevância dos achados para a problemática

A problemática abordada no projeto consiste em identificar antecipadamente clientes com maior probabilidade de inadimplência, permitindo que uma instituição financeira tome decisões preventivas e reduza possíveis prejuízos.

Os resultados demonstram que os dados históricos dos clientes possuem potencial para auxiliar nesse processo, principalmente por meio das informações relacionadas ao histórico de pagamentos, valores das faturas e pagamentos realizados.

Entretanto, a análise dos modelos revelou uma limitação importante: a acurácia elevada não representa necessariamente uma boa capacidade de identificação de inadimplentes.

Nesse contexto, a capacidade de identificar corretamente os clientes que poderão deixar de pagar suas faturas é especialmente relevante. Um cliente inadimplente classificado incorretamente como bom pagador pode representar prejuízos financeiros para a instituição.

Portanto, o projeto demonstra que a utilização de Machine Learning pode contribuir para a gestão de riscos de crédito, mas também evidencia a necessidade de aprimorar os modelos para melhorar a identificação da classe de inadimplência.

### Sugestões de ações e soluções

Com base nos resultados obtidos, algumas ações podem ser adotadas por uma instituição financeira:

1. Monitoramento preventivo de clientes

Utilizar o histórico de pagamentos para identificar clientes que apresentam atrasos recorrentes, permitindo antecipar possíveis situações de inadimplência.

2. Revisão dos limites de crédito

Avaliar periodicamente os limites concedidos aos clientes, considerando seu comportamento financeiro e histórico de pagamentos. Clientes que apresentam sinais de maior risco podem passar por uma análise mais criteriosa antes de receber aumentos de limite.

3. Desenvolvimento de estratégias de negociação

Oferecer alternativas de renegociação, parcelamento ou regularização de débitos para clientes que apresentem sinais de dificuldade financeira, reduzindo a possibilidade de inadimplência.

4. Aprimoramento dos modelos preditivos

Realizar ajustes nos modelos de Machine Learning, buscando aumentar a capacidade de identificação dos clientes inadimplentes. Também é importante avaliar estratégias para lidar com o desequilíbrio entre as classes, testar diferentes parâmetros e ajustar o limiar de classificação.

5. Acompanhamento contínuo dos resultados

Monitorar periodicamente o desempenho do modelo, verificando se as previsões continuam consistentes e se as estratégias adotadas estão contribuindo para reduzir a inadimplência.

### Conclusão

A análise demonstrou que os dados históricos dos clientes podem ser utilizados para apoiar a identificação de possíveis situações de inadimplência. Os modelos desenvolvidos apresentaram resultados satisfatórios em termos de acurácia, com destaque para a Árvore de Decisão e o Random Forest.