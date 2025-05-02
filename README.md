# ML_Churn

## Dataset
O dataset Telco Customer Churn, disponibilizado pela IBM, contém informações sobre clientes de uma empresa de telecomunicações e é utilizado para a análise e previsão do fenômeno de churn, ou seja, o cancelamento de serviços pelos clientes. Composto por 7.043 instâncias e 20 atributos, este conjunto de dados inclui tanto variáveis categóricas quanto numéricas, englobando aspectos como dados demográficos, informações contratuais, uso de serviços e valores monetários. A variável-alvo, Churn, classifica os clientes como aqueles que cancelaram ou não os serviços da empresa.

Entre as variáveis presentes no dataset, destacam-se informações como gender, SeniorCitizen, tenure, Contract, PaymentMethod, MonthlyCharges, e TotalCharges, que fornecem uma visão detalhada dos clientes e do relacionamento contratual com a empresa. No entanto, algumas colunas, como a TotalCharges, exigem pré-processamento adicional devido a inconsistências no tipo de dado.

Este dataset é amplamente utilizado para a construção de modelos preditivos de classificação binária, permitindo a análise de fatores que influenciam o churn dos clientes e contribuindo para a otimização de estratégias empresariais no setor de telecomunicações.

### Features

customerID → Identificador único do cliente
gender → Gênero do cliente (masculino ou feminino).
SeniorCitizen → Se o cliente é idoso (1 = Sim, 0 = Não).
Partner → Se o cliente tem parceiro/parceira (Sim ou Não).
Dependents → Se o cliente tem dependentes (filhos, outros familiares).
tenure → Tempo de permanência na empresa (em meses).
PhoneService → Se o cliente possui serviço de telefone (Sim ou Não).
MultipleLines → Se o cliente possui múltiplas linhas telefônicas (Sim, Não ou Não possui serviço telefônico).
InternetService → Tipo de serviço de internet (DSL, fibra ótica ou nenhum).
OnlineSecurity → Se o cliente possui segurança online (proteção contra vírus).
OnlineBackup → Se o cliente possui serviço de backup online.
DeviceProtection → Se o cliente possui proteção para seus dispositivos (manutenção, suporte).
TechSupport → Se o cliente possui suporte técnico.
StreamingTV → Se o cliente possui serviço de streaming de TV.
StreamingMovies → Se o cliente possui serviço de streaming de filmes.
Contract → Tipo de contrato do cliente (mensal, anual, bianual).
PaperlessBilling → Se o cliente recebe a fatura apenas online (sem papel).
PaymentMethod → Método de pagamento (boleto eletrônico, cheque enviado, débito automático, cartão de crédito automático).
MonthlyCharges → Valor da fatura mensal do cliente (em dólares).
TotalCharges → Valor total pago pelo cliente até o momento (em dólares).
Churn → Se o cliente cancelou o serviço (Sim = cancelou, Não = ainda está ativo).

## Organização do repositório

Este repositório está estruturado da seguinte forma:

- **notebooks/**: Contém os notebooks Jupyter (`.ipynb`) utilizados nas etapas do projeto:  
  - `EDA`: Análise exploratória dos dados  
  - `preprocessing`: Pré-processamento dos dados  
  - `featureselection`: Seleção de variáveis  
  - `classifier`: Modelagem e avaliação de classificadores  

- **scripts/**: Contém os scripts Python (`.py`) correspondentes aos notebooks acima, organizados para execução modular e reutilização de código.

- **data/**: Armazena os arquivos de dados utilizados no projeto, no formato `.csv`.


