# challenge_TelecomX
https://colab.research.google.com/drive/1L4nStlthT8VTFYifut-nhtxTLJOfrBk8#scrollTo=x31ObwBkzg8R 
Desafio Alura - Challehge TelecomX
Este relatório apresenta uma análise exploratória detalhada dos dados de clientes da TelecomX. Nosso objetivo principal é identificar padrões e fatores que contribuem para a evasão de clientes, também conhecida como churn. Através de estatísticas descritivas e visualizações gráficas, buscamos entender o comportamento dos clientes e a distribuição das variáveis, fornecendo insights valiosos para futuras estratégias de retenção.

Resumo das Principais Descobertas
Análise Geral de Churn
Distribuição de Clientes que Deixaram a Empresa: 1869 clientes
Implicação: 36,12% dos clientes da TelecomX deixaram a empresa, o que representa uma taxa de evasão significativa.
Análise de Churn por Variáveis Categóricas
Gênero: Não há uma diferença expressiva na taxa de churn entre gêneros, com 939 clientes femininos e 930 clientes masculinos tendo evadido.
Tipo de Contrato: Clientes com contratos mensais representam a maior parcela da evasão, com 1665 clientes. Isso sugere que contratos de curto prazo estão fortemente associados ao churn.
Método de Pagamento: O cheque eletrônico é o método de pagamento mais problemático, associado a uma taxa de evasão de 58%. É crucial investigar os motivos por trás dessa alta taxa.
Parceiro e Dependentes: Ter um parceiro ou dependentes influencia o comportamento de churn: 36% dos clientes com parceiro e 17% dos clientes com dependentes acabaram por deixar a empresa.
Serviços Adicionais: Curiosamente, 90% dos clientes que evadiram possuíam serviços adicionais de serviço telefônico. Isso pode indicar que, para esses clientes, apenas o serviço telefônico adicional não foi suficiente para garantir a retenção, ou que ele é um serviço base comum a quase todos os clientes.
Análise de Churn por Variáveis Numéricas
Tempo de Permanência (Tenure): Clientes que evadem tendem a ter um menor tempo de permanência na empresa. A análise do box plot para o tempo de permanência de clientes com e sem churn revelaria que a mediana e os quartis para clientes que evadem são significativamente menores, indicando uma saída mais precoce.
Cobrança Mensal (MonthlyCharges): A cobrança mensal média para clientes que evadiram é de 74.44. Isso sugere que custos mensais mais altos podem estar correlacionados com a decisão de churn.
Cobrança Total (TotalCharges): O valor médio da cobrança total ao longo do tempo de permanência para clientes que evadiram é de 1531.80. Clientes com menor tempo de permanência naturalmente terão uma cobrança total menor.
Contas Diárias (DailyCharges): Uma média de 51.60 contas diárias foi observada ao longo do tempo de permanência por cliente que evadiu, o que provavelmente é uma derivada das cobranças mensais e tempo de permanência.
