# Cálculo de Salário

## Enunciado

Faça um algoritmo que receba:

* quantidade de horas trabalhadas;
* quantidade de horas extras;
* valor recebido por hora.

A partir dessas informações, calcule:

* salário bruto;
* desconto do INSS de 9%;
* valor do FGTS de 8%;
* salário líquido.

As horas extras devem ser pagas com **100% de acréscimo** sobre o valor normal da hora.

### Fórmulas

**Salário bruto:**

`(horas trabalhadas × valor da hora) + (horas extras × valor da hora × 2)`

**INSS:**

`salário bruto × 9%`

**FGTS:**

`salário bruto × 8%`

**Salário líquido:**

`salário bruto - INSS`

## Exemplo

**Entrada:**

```text
Quantas horas foram trabalhadas: 160
Digite o numero de horas extras: 10
Informe o valor da sua hora: 20
```

**Saída:**

```text
Seu salário bruto é: 3400.0
O salário líquido é: 3094.0
O FGTS é: 272.0
O INSS é: 306.0
```
