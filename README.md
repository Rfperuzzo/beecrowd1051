# 💰 Beecrowd 1051 — Imposto de Renda

Solução desenvolvida em **Java** para o exercício **1051 — Imposto de Renda**, da plataforma Beecrowd.

O objetivo do exercício é calcular o valor do imposto de renda de uma pessoa de acordo com sua faixa salarial.

---

## 📚 Objetivo

Este exercício trabalha principalmente com:

- Entrada de dados;
- Variáveis do tipo `double`;
- Estruturas condicionais;
- `if`, `else if` e `else`;
- Operadores relacionais;
- Cálculos percentuais;
- Formatação de valores monetários;
- Lógica de cálculo por faixas.

---

## 🧠 Lógica do problema

O programa recebe um valor que representa o salário de uma pessoa.

A partir desse valor, o imposto é calculado de forma progressiva, utilizando diferentes porcentagens para cada faixa de renda.

As faixas utilizadas são:

| Faixa de renda | Imposto |
|---|---:|
| Até R$ 2.000,00 | Isento |
| De R$ 2.000,01 até R$ 3.000,00 | 8% |
| De R$ 3.000,01 até R$ 4.500,00 | 18% |
| Acima de R$ 4.500,00 | 28% |

O percentual não é aplicado sobre todo o salário, mas somente sobre a parte correspondente a cada faixa.

---

## 💡 Exemplo de cálculo

Para uma renda de:

```text
3002.00
