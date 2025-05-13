# Case
Esse repositório contém uma análise de dados de uma empresa fictícia de varejo.
> Difficulty: ⭐⭐

> Techs: ![SQL](https://img.shields.io/badge/-sql-red?style=for-the-badge&logo=html&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)

---

## Objetivo
 Uma equipe da área de Produtos de uma empresa do varejo deseja entender os padrões de vendas dos produtos, buscando insights para tomar decisões estratégicas.

## Sobre as Bases
* `Raw`: tabela fato em que cada linha representa uma transações
* `Master Atributos`: tabela dimensão com características dos produtos
* `Master Lojas`: tabela dimensão com localização das lojas
* `Master Clientes`: tabela dimensão com características dos clientes

## Tratamentos
* Tabela `Master Atributos` transformada para que houvesse apenas um ProdID por linha, transformando as linhas da  `descricao_dtributo` em colunas.
* UF’s nulos na tabela `Master Lojas` preenchidos utilizando o `CodigoCidade`.

## Questões resolvidas em Py e SQL
1. Filtrando apenas clientes da classe social que mais comprou produtos no período, quantos clientes compraram peças em promoção em cada unidade da federação?
2. Filtrando apenas as transações de peças da cor azul realizadas por clientes que compraram peças da cor azul em apenas uma unidade da federação, qual foi o tamanho que mais vendeu peças?
3. Filtrando apenas o tipo de item que vendeu mais peças da cor vermelha em 2023 do que em 2022 (em todas as UFs), qual foi o valor vendido no RS em 2022 para esse tipo de item (para peças de qualquer cor)?

## Análises utilizando Matplotlib
1. Como foi a evolução das vendas no ano de 2023?
2. Como estão as vendas em relação ao ano anterior?
3. Quais produtos foram os mais vendidos e os mais rentáveis em 2023?
4. Qual foi o ticket médio das vendas em 2023?
5. Para qual público vendemos mais?
6. Qual é a faixa etária que mais compra nossos produtos?
7. Qual loja vende mais produtos?
8. Qual é o total de vendas por estado?
9. A empresa possui sazonalidade?
10. Existe algum padrão que se destaca nas vendas?
11. Qual é a receita por categoria da pirâmide mercadológica?

## Conclusões
Crescimento dos resultados em 2023 em relação a 2022 em 20.7%;

Público predominante: feminino, classe C, entre 25 e 45 anos;

Principais localidades: SP e RS;

Sazonalidade: aumento nas trocas de estação;

Tipos de produto mais vendidos: peças lisas e core.
