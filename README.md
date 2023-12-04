# **ÁGUA INVISIVEL** (<small>[leia aqui](https://aguainvisivel.fehla.xyz/)</small>)

Projeto final da disciplina **Análise Exploratória de Dados II**, ministrada pelo Profº André Felipe de Moraes, no Master em Jornalismo de Dados, Automação e Storytelling, do Insper. As análises foram desenvolvidas a partir dos cruzamentos dos valores de pegada hídrica e da produção agrícola vegetal de todos os municípios do Brasil em 2022.

## **BASE DE DADOS:**

- **Pegada hídrica:** [Water to Food](https://www.watertofood.org/), da Politécnica de Turim (Itália).

- **Produção agrícola vegetal:** [Produção Agrícola Municipal](https://sidra.ibge.gov.br/tabela/5457), do IBGE, com foco nos dados da produção agrícola vegetal de todos os municípios do Brasil em 2022.

## **FERRAMENTA:**

Para a manipulação das bases de dados mencionadas, foi utilizada a linguagem Python, através da plataforma Google Colab.

## De onde vem a pegada hídrica do Brasil?

Encontramos bases de dados, que nos levaram a perguntas secundárias durante a análise:
- qual a pegada hidrica de cada produto produzido no Brasil?
- qual os municípios que estão por traz dessas produções?

Ao avaliar individualmente os dados, buscamos responder uma pergunta mais urgente que apareceu na apuração: **quais os municípios com maior pegada hidrica do Brasil?**

Encontramos que:

- 232 municípios foram responsáveis por 50% da pegada hidrica do Brasil em 2022. 
- desses, a maior parte está no Centro-Oeste

Para contextualizar melhor o impacto disso no dia a dia, recorremos ao Índice de Segurança Hídrica (ISH). Percebemos que dos 232 municípios que concentram metade da pegada hídrica, 14 municípios tiveram o índice categorizado mínimo ou baixo em 2017. O indicador varia de Alta – ideal – para Mínima – que acende um alerta.  

Pensamos em olhar por bioma para procurar _insights_, mas, como um município poderia estar em mais de um bioma, essa saída poderia trazer ruído e descartamos. 

*Visualização*
Nossa principal dificuldade foi mostrar todos os municípios de uma vez para que eles pudessem ser comparados. e que apesar do mapa coropletico ser uma boa alternativa, esse gráfico de símbolo gradual facilita melhor a compreensão ao reproduzir em spikes a pegada hidrica.

#### **BIBLIOTECA E MÓDULOS UTILIZADOS:**

- Pandas
- Missingno
- Altair
- OS


**Para mais informações, entre em contato com a equipe:**

Cindy Damasceno (cindymdj@insper.edu.br)

Nicole Lacerda ()

Paulo Fehlauer ()

Rute Damascena (rutessd@al.insper.edu.br)
