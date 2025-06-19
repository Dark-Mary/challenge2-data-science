📄 **DESCRIÇÃO**

Este projeto faz parte do Desafio de Data Science do programa ONE + Alura, no qual foi proposta uma análise dos dados de uma empresa fictícia de telecomunicações chamada Telecom X, que enfrenta altos índices de evasão de clientes (churn).

O objetivo principal é realizar o processo completo de ETL (Extração, Transformação e Carga) dos dados para entender os padrões que levam os clientes a cancelarem seus serviços. Essa análise fornecerá informações valiosas para que a empresa desenvolva estratégias de retenção.

🚀 **ETAPAS DO PROJETO**

🔍 **1. Extração dos Dados**

Os dados foram extraídos diretamente de uma API hospedada no GitHub, no formato JSON.

O dataset contém informações cadastrais, uso de serviços, tipos de contratos e dados financeiros dos clientes da Telecom X.

🔧 **2. Transformação dos Dados**

Realizamos a normalização de dados aninhados (nested JSON), convertendo campos como customer, phone, internet e account em colunas planas.

Ajustamos os tipos de dados:

Colunas numéricas como MonthlyCharges, TotalCharges e tenure foram convertidas corretamente para formatos numéricos.

Tratamento de dados:

Remoção de linhas com valores nulos e dados inconsistentes.

Padronização de textos (ex.: Contract, PaymentMethod, Churn).

Remoção de duplicatas para garantir a integridade do dataset.

📊 **3. Carga e Análise Exploratória de Dados** (EDA)

Foram geradas análises visuais e estatísticas, buscando entender os seguintes padrões:

✅ Distribuição do Churn: percentual de clientes que cancelaram vs. permaneceram.

✅ Relação do Churn com o tipo de contrato: contratos de curto prazo têm maior evasão.

✅ Distribuição do tempo de contrato (tenure): clientes com menos tempo tendem a cancelar mais.

✅ Análise financeira: clientes com mensalidades mais altas demonstram maior propensão ao churn.

📄 **4. Relatório Final**

O relatório apresenta:

➕ Visão geral dos dados tratados.

➕ Gráficos explicativos sobre o comportamento dos clientes.

➕ Principais achados sobre os fatores que mais influenciam o churn.

➕ Sugestões para o time de Data Science e para o negócio, incluindo:

Oferecer contratos de longo prazo.

Criar benefícios para clientes com menor tempo de contrato.

Monitorar clientes com altos valores de mensalidade.

🛠️ **Tecnologias e Bibliotecas Utilizadas**

🔗 Python 3.11

📦 Pandas – Manipulação e análise de dados

📊 Seaborn e Matplotlib – Criação de gráficos e visualizações

🌐 Requests – Acesso à API

✅ Google Colab – Ambiente de desenvolvimento
