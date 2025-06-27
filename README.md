Análise de Evasão de Clientes (Churn)

Este projeto tem como objetivo identificar padrões e fatores que contribuem para a evasão de clientes (Churn) da empresa Telecom X.

Propósito da Análise

Através da análise de diversas características dos clientes e de seus comportamentos, buscamos entender as causas da evasão e propor recomendações para mitigar esse problema. A Análise Exploratório de Dados foi realizada para visualizar a distribuição dos dados e identificar possíveis correlações com a variável Churn. Foram utilizados alguns levanmtamentos, como:

 Distribuição de Evasão por Variáveis Categóricas e Númericas
 
#### Evasão por Gênero

#### Evasão por Tipo de Contrato

#### Evasão por Método de Pagamento


#### Evasão por Idoso


#### Evasão por Múltiplas Linhas Telefônicas


#### Evasão por Serviço de Internet


#### Evasão por Streaming de Filmes


#### Distribuição do Total Gasto


#### Distribuição por Tempo de Contrato


Estrutura do Projeto

challenge_telecomX/ │ ├── dados/
# Arquivos JSON com os dados  │ └── TelecomX_Data.json │ ├── notebook/ # Notebook com a análise

│ └── Challenge_TelecomX.ipynb │ ├── imagens/ # Gráficos gerados na análise

│ ├── balaco_clientes.png │ └── evasao_customer.gender.png │ └── evasao_customer.SeniorCitizen.png │ └── evasao_internet.InternetService.png │ └── evasao_internet.StreamingMovies.png │ └── evasao_phone.MultipleLines.png │ └── evasao_account.PaymentMethod.png │ └── evasao_account.Contract.png │ └── distribuicao_evasao.png │ └── distribuicao_account.Charges.Total.png │ └── total_gasto_churn_distribuicao.png │ └── tempo_contrato_churn_distribuicao.png 


└── README.md # Documentação do projeto

Exemplos de Gráficos e Insights

#### Evasão por Gênero

#### Evasão por Tipo de Contrato

#### Evasão por Método de Pagamento


#### Evasão por Idoso


#### Evasão por Múltiplas Linhas Telefônicas


#### Evasão por Serviço de Internet


#### Evasão por Streaming de Filmes


#### Distribuição do Total Gasto


Insights: 

- **Contratos Mensais:** Clientes em contratos mensais são o grupo de maior risco para evasão. A flexibilidade pode ser conveniente, mas não promove a lealdade a longo prazo.
- **Métodos de Pagamento:** O método de pagamento 'Electronic check' está associado a uma alta taxa de Churn. Pode haver problemas de usabilidade, confiança ou um perfil de cliente diferente associado a este método.
- **Serviços Adicionais de Internet:** A ausência de serviços de segurança online e suporte técnico parece estar correlacionada com uma maior propensão à evasão. Isso sugere que esses serviços podem ser importantes para a satisfação e retenção do cliente.
- **Total Gasto:** Clientes com menor histórico de gastos totais tendem a evadir mais. Isso pode indicar que clientes com maior tempo de casa ou que utilizam mais serviços são mais retidos.
- **Balanço de Classes:** A base de dados possui um desequilíbrio entre clientes que evadiram e que não evadiram. Isso é um ponto importante a considerar em futuras etapas de modelagem preditiva.

Como Executar o Notebook

Clone o repositório:
git clone https://github.com/jaqueline-quaresma/challenge_telecomX

cd challenge_telecomX

Instale as dependências necessárias (opcional):

pip install pandas matplotlib seaborn numpy 

Execute o notebook:

google colab notebook notebook/Challenge_TelecomX.ipynb

Seguindo as instruções será possível, acompanhar a análise exploratória de dados da empresa Telecom X.
