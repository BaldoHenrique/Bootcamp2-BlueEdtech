btc2-blue-g4
# Repositório do Grupo 4

## Integrantes do grupo:
- Henrique Grandi Baldo
- Paulo
- Flávio
- Gabriel

# Projeto
## Bootcamp - Pesquisa de impacto do Coronavirus 2020

SARS-CoV-2, Coronavirus Disease 2019 - Dados de múltiplas origens

COVID-19 (do inglês: coronavirus disease 2019, em português: doença por coronavírus 2019) é uma doença infeciosa causada pelo coronavírus da síndrome respiratória aguda grave 2 (SARS-CoV-2). Os sintomas mais comuns são febre, tosse seca e cansaço. Entre outros sintomas menos comuns estão dores musculares, dor de garganta, dor de cabeça, congestão nasal, conjuntivite, perda do olfato e do paladar e erupções cutâneas. Cerca de 80% das infeções pelo SARS-CoV-2 confirmadas têm sintomas ligeiros de COVID-19 ou são assintomáticos, e a maioria recupera sem sequelas. No entanto, 15% das infeções resultam em COVID-19 severa com necessidade de oxigênio e 5% são infeções muito graves que necessitam de ventilação assistida em ambiente hospitalar. Os casos mais graves podem evoluir para pneumonia grave com insuficiência respiratória grave, sepse, falência de vários órgãos e morte. Entre os sinais de agravamento da doença estão a falta de ar, dor ou pressão no peito, dedos de tom azul ou perturbações na fala e no movimento. O agravamento pode ser súbito, ocorre geralmente durante a segunda semana e requer atenção médica urgente - .

**COVID-19 Dataset , Kaggle**
Este conjunto possui dados do número de casos confirmados, mortes e recuperados por dia em vários países entre Janeiro de 2020 a Julho de 2020.

**Twitter API** A rede social Twitter é uma ótima plataforma de busca por percepções dos usuários sobre assuntos diversos. Pelas características da plataforma, o uso de textos curtos e diretos permitem encontrar e realizar estudos com grande quantidade de dados.

**WebScraping** Utilização da técnica de extração de dados de sites, como Wikipédia.

## Objetivo
Neste projeto, o objetivo é a realização de um estudo sobre o COVID19 por país. Correlacione os dados de COVID19 do Kaggle com uma análise de sentimento realizado com os dados extraídos do Twitter. Enriqueça o seu trabalho também correlacionando com os dados extraídos da Wikipédia. Apresente os insights encontrados em forma de texto, gráficos e tabelas.

Neste projeto, atuem como uma equipe de pesquisa interna de uma empresa, que deve apresentar os impactos da pandemia nos países onde há filiais.

## Sobre este projeto
Os principais pontos que serão avaliados:
- Extração de dados
- Análise descritiva dos dados
- Levantamento de hipóteses
- Manipulação de dados e criação de gráficos
- Desenvolvimento de um modelo forecast por país
- Desenvolvimento de um modelo de análise de sentimento
- Apresentação do trabalho

## Preparação do ambiente
- Para este projeto, serão necessários os seguintes dados:
  - Acessem o  e baixem os seguintes arquivos:
    - country_wise_latest.csv
    - covid_19_clean_complete.csv
    - day_wise.csv
    - full_grouped.csv
    - worldometer_data.csv Caso você não tenha uma conta no Kaggle, crie uma e retorne para esse ponto para realizar o download. Descompacte os arquivos.
  - Entrem na  e criem uma conta.
    - Leiam a  de uso da API e sobre busca de tweets
    - Usem como palavra-chave da busca:
      - covid, covid19, covid-19, coronavirus, corona virus
    - Filtrem os tweets para o intervalo de Janeiro de 2020 a Julho de 2020
    - Limitem a 2.000 tweets por país
  - Extraiam dados dos seguintes páginas e os correlacione com os demais dados extraídos:
    - Lista de países por população
    - Lista de países or PIB nominal per capita
- Utilizem dados somente dos seguintes países:
  - Espanha
  - Equador
  - Chile
  - México
  - Argentina
- Vocês podem buscar outros conjuntos de dados sobre COVID19 e adicione ao seu projeto, não se esqueça de manter o intervalo de Janeiro a Julho de 2020 e aos países indicados
- Organizem os dados em uma estrutura Medallion e a camada Gold deverá estar organizada por Star Schema
- Criem o projeto no Github
- Usem o cookiecutter para organizar o projeto
- Leiam todo o material disponibilizado no Kaggle para entender esses dados
- Caso precisem, leiam outros projetos que usaram este mesmo conjunto de dados
- Os conjuntos de dados poderão conter erros, avaliem como tratá-los
- Construam um dashboard em Power BI

## Gerenciamento do tempo
- Apliquem a metodologia CRISP-DM junto ao quadro Kanban para organizar as tarefas de cada fase do projeto e para a definição das responsabilidade de cada membro da equipe. Na terceira semana, comecem a elaborar o pitch e fazer treinos de apresentação. Haverá uma pré-banca, aproveitem o momento para receber um feedback do seu trabalho.

## Apresentação
- Utilizem um editor de slides e construa sua apresentação, caso precisem, usem templates gratuitos de apresentação disponibilizados no site . O site  disponibiliza milhares de ícones gratuitamente. Sempre coloque no final da apresentação a referência do uso do template e dos ícones, pois isso ajuda a divulgar o trabalho destes sites.

- A apresentação deverá seguir a estrutura de um projeto. Durante as sprints será demonstrado o que esperamos deste material.

## Projeto
- Disponibilizem o link do repositório do seu projeto para ser avaliado. Lembrem-se de utilizar a pasta 'playground' para realizar experimentos sobre suas ideias e a pasta 'report' para colocar o notebooks principais. Escrevam o arquivo README sobre o projeto.
- Construam um dashboard que contenha os dados de COVID19, a projeção de novos casos, a análise de sentimento e outras informações que a equipe julgar importantes para apresentar.
