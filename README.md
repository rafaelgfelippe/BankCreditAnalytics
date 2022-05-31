![](figures/ProfitCard.png)

Este é um projeto de classificação.  

O conjunto de dados utilizado está disponível [neste link](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients). 

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

# Entendimento do Negócio

A ProfitCard é uma instituição financeira em expansão, que fornece empréstimos e financiamentos a seus clientes. Desde a sua fundação, a empresa sempre adotou uma cultura orientada a dados visando sempre otimizar seus resultados e tornar a experiência de seus clientes muito mais completa.

Devido ao grande aumento no volume de solicitações de crédito, a empresa decidiu iniciar um novo projeto de ciência de dados com o objetivo de implementar um programa de aconselhamento aos clientes mais propensos a inadimplir. Nesse programa, o principal objetivo é fornecer um aconselhamento individualizado para o titular da conta de modo a encorajá-lo a acertar suas pendências.

Logo, essa análise tem como objetivo identificar quais clientes possuem as maiores probabilidades de serem contatados e consequentemente pagarem suas dívidas, ou seja, a decisão que o modelo ajudará a tomar é de sim ou não: **Esse cliente deve passar pelo programa de aconselhamento da ProfitCard?**

# Dicionário de Dados

Em relação ao conjunto de dados, as seguintes informações foram disponibilizadas:

- Os dados estão em formato estruturado e serão disponibilizados em um arquivo "xls".
- Os dados financeiros estão em dólares taiwaneses e serão convertidos para facilitar a análise.
- Cada registro do conjunto de dados representa a conta de um cliente, sendo assim, não deve haver registros duplicados.

Além disso, também foi disponibilizado o dicionário de dados:

**OBS:** os significados dos valores de cada variável estão disponíveis no notebook.

| Variáveis                        | Descrição                                       | 
| -------------------------------- | ------------------------------------------------| 
| ID                               | Identificação da conta do cliente               | 
| LIMIT_BAL                        | Valor do crédito fornecido                      | 
| SEX                              | Sexo do cliente                                 | 
| EDUCATION                        | Grau de instrução educacional do cliente        | 
| MARRIAGE                         | Estado civil do cliente                         | 
| AGE                              | Idade do cliente                                |            
| PAY[1 a 6]                       | Status do pagamento mensal                      | 
| BILL_AMT[1 a 6]                  | Valor da fatura mensal                          |
| PAY_AMT[1 a 6]                   | Valor do pagamento mensal realizado             |
| default payment next month       | Variável target                                 |
