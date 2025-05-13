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

## Conclusões
Crescimento dos resultados em 2023 em relação a 2022 em 20.7%;

Público predominante: feminino, classe C, entre 25 e 45 anos;

Principais localidades: SP e RS;

Sazonalidade: aumento nas trocas de estação;

Tipos de produto mais vendidos: peças lisas e core.
