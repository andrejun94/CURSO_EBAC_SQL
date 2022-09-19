# CURSO_EBAC_SQL

# Análise exploratoria de dados

## 1.Dados

A tabela que utilizamos tem os seguintes campos:

-Idade = Idade

-Sexo = (F ou M)

-Dependentes = Quantidade de dependentes

-Escolaridade = Nivel de escolaridade

-Estado_civil = (casado, solteiro, divorciado, NA)

-Salario_anual = Salário anual

-Tipo_cartao = Tipo do cartão

-Qtd_produtos = Quantidade de produtos comprados nos últimos 12 meses 

-Iteracoes_12m = Quantidade de iterações/transações nos últimos 12 meses

-Meses_inativo_12m = Quantidade de meses que o cliente ficou inativo

-Limite_credito = Limite de crédito

-Valor_transacoes_12m = Valor das transações nos últimos 12 meses

-Qtd_transacoes_12m = Quantidade de transações nos últimos 12 meses

# 2.Consultando os dados

Essa base contém 2.564 linhas (query: select count(*) from credito;), ela está da seguinte forma (select * from credito limit 10)

![](https://github.com/andrejun94/CURSO_EBAC_SQL/blob/main/query_1.png?raw=true)

Os campos estão da seguinte forma (describe credito) 

![](https://github.com/andrejun94/CURSO_EBAC_SQL/blob/main/query_2.png?raw=true)

# 3.Analisando os dados

Quantidade de clientes por faixa salarial:

![](https://github.com/andrejun94/CURSO_EBAC_SQL/blob/main/query_3.png?raw=true)

Quantidade de clientes por tipo de cartão:

![](https://github.com/andrejun94/CURSO_EBAC_SQL/blob/main/query_6.png?raw=true)

Média do limite de crédito, média de valor transacional e média de quantidade de transacoes por faixa salarial:

![](https://github.com/andrejun94/CURSO_EBAC_SQL/blob/main/query_5.png?raw=true)

# 4.Conclusão

- Temos maior frequencia de clientes que possuem faixa salarial anual menor de 40k

- A média do limite de crédito aumenta conforme a faixa salarial anual aumenta

- A média do valor transacional é maior para a menor faixa salarial anual

- A média da quantidade de transacoes é maior para a menor faixa salarial anual




















