ref# Challenge-TelecomX
O principal objetivo deste projeto é desenvolver minhas habilidades em ETL (Extract, Transform, Load) com Python

# :computer: Análise de Evasão de Clientes (Churn Analysis) :chart_with_upwards_trend:

# :open_file_folder: Descrição do Projeto
Este projeto tem como objetivo analisar os dados de clientes da empresa TELECOM X para identificar os fatores que mais contribuem para a evasão de clientes (churn). 
Através da exploração e transformação dos dados, buscamos entender o comportamento dos clientes que cancelam seus serviços e desenvolver insights para estratégias de retenção.

:game_die: Conjunto de Dados
O conjunto de dados utilizado neste projeto é o TelecomX_Data.json, disponível em https://raw.githubusercontent.com/alura-cursos/challenge2-data-science/refs/heads/main/TelecomX_Data.json. 
Ele contém informações sobre diversos aspectos dos clientes, incluindo dados demográficos, serviços contratados e informações da conta.

# :hammer: Análise Realizada
A análise incluiu as seguintes etapas:

* Extração e Carregamento: Os dados foram extraídos do arquivo JSON e carregados em um DataFrame pandas.

* Exploração e Entendimento dos Dados: Realizamos uma análise exploratória para entender a estrutura do dataset, tipos de dados e significados das variáveis.

* Verificação e Tratamento de Inconsistências: Identificamos e tratamos valores ausentes, duplicados e inconsistências em algumas colunas (como 'Churn' e 'Charges.Total').

* Transformação e Padronização: Normalizamos o DataFrame, renomeamos colunas para melhor legibilidade e convertemos valores textuais em binários (onde aplicável). Criamos a coluna "Contas_Diarias" para uma análise mais detalhada.

* Análise Descritiva: Calculamos métricas descritivas para variáveis numéricas e categóricas, além de analisar a correlação entre variáveis numéricas.

* Análise de Evasão: Exploramos a distribuição da variável 'Rotatividade' (Churn) e analisamos como a evasão se relaciona com variáveis categóricas e numéricas através de visualizações.

# :mag: Principais Descobertas
As principais descobertas da análise indicam que os clientes com maior probabilidade de cancelar o serviço geralmente apresentam as seguintes características:

* Idoso têm maior tendência a cancelar
* Utilizam o serviço de internet "Fiber optic".
* Não assinam serviços adicionais online (Segurança Online, Backup Online, etc.).
* Têm contratos "Month-to-month".
* Optam por faturamento eletrônico.
* Utilizam "Electronic check" como forma de pagamento.
* Possuem menor tempo de permanência na empresa.
* Têm cobranças mensais e diárias mais altas.

# :wrench: Como Executar o Projeto

:loudspeaker:Para replicar a análise, você pode seguir os passos no notebook Python ([Challenge-TelecomX](https://github.com/LipeSilva83/Challenge-TelecomX)). Certifique-se de ter as bibliotecas necessárias instaladas (pandas, matplotlib, seaborn).

# :pushpin: Tecnologias Utilizadas

* Python
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/> 

* google colab  
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)

* Pandas
  
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

* Matplotlib        
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
  
* Seaborn   
![Seaborn](https://img.shields.io/badge/Seaborn-008080?style=for-the-badge&logo=seaborn&logoColor=white)

* Numpy
  
 ![Numpy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white)

