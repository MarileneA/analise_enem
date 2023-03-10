# Enem

O Exame Nacional do Ensino Médio (Enem) é a maior prova do Brasil, aplicada anualmente para mais de 5 milhões de estudantes do ensino médio. A prova do Enem é realizada em dois domingos consecutivos e se divide em quatro áreas: Linguagens e Códigos; Ciências Humanas; Ciências da Natureza; Matemática.


## 1. Case 

Neste trabalho foram apresentados e explorados os dados do ENEM 2017 contidos em um conjunto de dados que pode ser encontrado no site do [Inep](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem).

O significado de cada feature também pode ser visto no Dicionário de Dados no site do Inep

Esta análise tem como objetivo responder as seguintes perguntas:

- Média de notas por cidade, estado e/ou região
- Histograma por cidade, estado e/ou região e com detalhamento por área/disciplina
- Mapa geográfico com pontuações (pontos)
- Classificação das 10 melhores e das 10 piores pontuações por cidade, estado e/ou região
- Curva linear de pontuações por população (em milhares)
- mapa de calor de correlação entre a média das pontuações e o índice IDH
- Cidades com maior população tendem a ter piores pontuações na média?

## Ferramentas Utilizadas

- Python;
- Jupyter Notebook;
- SQlite;
- Git e Github;
- SQLite
- Power BI

##  Estratégia de solução

O projeto foi desenvolvido aplicando os seguintes passos:

**Passo 01 - Carregar os Dados:** Com a ajuda do dicionário de dados, pude verificar as colunas existentes e me ater apenas as que interessariam para a análise.

**Passo 02 - Descrição dos dados** O objetivo desta etapa é obter novos uma primeira impressão dados, para decidir os passos futuros

**Passo 03 - Limpeza dos dados:** O objetivo desta etapa foi filtrar linhas e excluir colunas que não são relevantes para a análise

**Passo 04 - Análise Exploratória de Dados:** O objetivo desta etapa foi explorar melhor os dados para entender melhor o perfil dos inscritos e saber o quanto influencia na nota média

**Passo 05 - Respondendo as Perguntas de Negócio** Esse passo o objetivo foi responder as perguntas de negócio.

**Top 3 insights:**

As Regiões Norte e Nordeste estão abaixo da Média Nacional

![2023-01-01 (2)](https://user-images.githubusercontent.com/87071331/210171749-aa726612-2fc5-4a42-911d-3cf1a1c78c2b.png)

As Notas entre as disciplinas tem forte correlação positiva

![2023-01-01 (1)](https://user-images.githubusercontent.com/87071331/210171870-5f8fe61b-6840-4731-8b61-740d8a02e461.png)

Quando comparado nota x IDH do Município a correlação é fraca.

![2023-01-01 (3)](https://user-images.githubusercontent.com/87071331/210171969-743374d4-6f0e-440a-865b-96c96e0e5fea.png)


**Passo 06 - Construir um Banco de Dados para subir pra Cloud.** Nesta etapa eu construí um banco de dados com os dados tratados, usando sqlite3.


## Próximos Passos
Conectar o banco de dados na Nuvem  e 
Melhorar a visualização dos dados e disponibilizar via cloud

