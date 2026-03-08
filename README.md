## Python Insights - Análise de Cancelamento de Clientes (Churn)
Este projeto faz parte de um estudo de Ciência de Dados focado em entender os motivos pelos quais os clientes de uma empresa (base de 800 mil usuários) estão cancelando seus serviços e propor estratégias para reduzir essa taxa.

## 📋 Contexto
A empresa identificou que a maioria de sua base de clientes está inativa. O objetivo desta análise é identificar padrões nos dados que indiquem um alto risco de cancelamento (Churn) e sugerir ações práticas.

## 🛠️ Tecnologias Utilizadas
Python: Linguagem principal.

Pandas: Para manipulação e tratamento dos dados.

Plotly: Para criação de gráficos interativos e visualização de dados.

Jupyter Notebook: Ambiente de desenvolvimento.

## 🔍 Etapas do Projeto
Tratamento de Dados:

Remoção de informações irrelevantes (ex: CustomerID).

Exclusão de registros com valores nulos.

Análise Inicial:

Verificação da taxa atual de cancelamento.

## Identificação de Padrões (Insights):

Contratos Mensais: Identificou-se que todos os clientes com contrato mensal cancelaram o serviço.

Ligações no Call Center: Clientes que ligam mais de 4 vezes para o suporte têm uma probabilidade muito maior de cancelar.

Dias de Atraso: Clientes com mais de 20 dias de atraso no pagamento são considerados de alto risco.

## 📈 Resultados e Conclusões
Ao filtrar e tratar as causas raiz identificadas, o projeto demonstra como a taxa de cancelamento pode ser drasticamente reduzida:

Ação 1: Incentivar a migração de contratos mensais para anuais ou trimestrais.

Ação 2: Criar alertas para resolver problemas de clientes que ligam excessivamente para o suporte.

Ação 3: Implementar políticas para evitar atrasos de pagamento superiores a 20 dias.