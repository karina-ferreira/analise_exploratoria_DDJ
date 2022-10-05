# Projeto Final - Disciplina Análise Exploradora de Dados- Insper 2022 

:pencil: Passo-a-passo do projeto final da disciplina de Análise Exploradora de Dados, do Master em Jornalismo de Dados, Automação e Data Storytelling do Insper. A tarefa consiste em  escolher um conjunto de dados e explorá-los, estabelecendo questionamentos sobre eles e possíveis relações entre as variáveis. O convite foi de explorarmos os dados e gerarmos algumas hipóteses sobre eles. 

**Integrantes:**
- Ingrid Fernandes - [@indgris](https://github.com/indgris)
- João Leite - [@joaogpleite](https://github.com/joaogpleite)
- Karina Ferreira - [@karina-ferreira](https://github.com/karina-ferreira)
- Will Araújo - [@will](https://github.com/link)

:unlock: Vamos lá:


## :dart: Escolha

Escolhemos o banco de dados da Secretaria de Segurança Pública do Estado de São Paulo, com informações sobre as ocorrências registradas por cidade, entre os anos de 2002 e 2021. Os dados estão disponíveis no [basededados.org](https://basedosdados.org/dataset/br-sp-gov-ssp?bdm_table=ocorrencias_registradas), e o dicionário pode ser acessado lá mesmo. 

## :point_up: Perguntas
Ao subir os dados para o *Orange*, abrimos um *data table* para fazer a primeira visualização dos dados. O primeiro passo foi entender a tabela, com ajuda do dicionário. Passamos então a pensar em duas modalidades de perguntas: as que vinham à mente, e as que poderiam ser respondidas com os dados que disponíveis. Fizemos algumas visualizações usando ferramentas do *Orange* como *group by*, *box plot*, *distribution*, etc. Demos match nas perguntas das duas cateorias e chegamos à seguinte lista:

1. Qual tipo de ocorrência mais se repete?
2. Qual tipo de ocorrência mais se repete em cada ano da série histórica (2002-2021)?
3. Quais cidades registraram maior número de ocorrências? São elas sempre as mesmas na série histórica?
4. Há crimes diminuindo em quantidade e outros aumentando ao longo dos anos? Quais?
5. Existem meses com maior número de registros de ocorrências?
6. Existe ano com ausência de registro para alguma modalidade de crime?
7. Existem manchas de criminalidade em cidades próximas?
8. Qual a modalidade de homicídio que mais tem registros?
9. A mancha de criminalidade aumentou em uma cidade em detrimento de outra próxima?
10. Existem missing datas? Como são descritos?
11. Na evolução dos anos, o número de vítimas fatais diminuiu diante da quantidade de homicídios, se manteve constante ou aumentou enquanto a soma de registros da modalidade diminuiu?
12. Qual a moda entre os anos?
13. A partir de que ano cada tipo de ocorrência começou ser catalogada?

## :put_litter_in_its_place: Limpeza
Embora grandes esntusiastas do *Orange*, podemos dizer que a paixão foi apagando conforme fomos apresentados à outras possibilidades de interação com os dados. O queridinho da vez é o *DB Browser*, onde utilizamos a linguagem *SQL* para construir *queries* que respondessem nossas perguntas. O primeiro e único passo da limpeza foi classificarmos as colunas que, para a maioria das perguntas, não seriam necessárias serem analisadas, como as que indicavam número de vítimas, ou as que somavam outras duas ou mais categorias. Para isso, fizemos a seuinte *querie*:

`colar o código aqui`

## :bar_chart: Visualização

Texto texto.

## :bulb: Hipóteses

Texto texto.
