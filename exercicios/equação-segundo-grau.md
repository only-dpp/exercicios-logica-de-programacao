# Equação do Segundo Grau

Faça um algoritmo que receba os valores de `a`, `b` e `c` de uma equação do segundo grau:

```text
ax² + bx + c = 0
```

Calcule o valor de `delta` e, de acordo com o resultado, informe as raízes reais da equação.

### Regras

* Se `a = 0`, informe que o valor de `a` não pode ser zero.
* Se `delta < 0`, informe que a equação não possui raízes reais.
* Se `delta = 0`, informe que a equação possui uma raiz real.
* Se `delta > 0`, informe que a equação possui duas raízes reais.

Utilize a fórmula de Bhaskara para calcular as raízes:

```text
Δ = b² - 4ac
```

```text
x₁ = (-b + √Δ) / 2a

x₂ = (-b - √Δ) / 2a
```

### Exemplo

Entrada:

```text
Digite o valor de a: 1
Digite o valor de b: -5
Digite o valor de c: 6
```

Saída:

```text
valor do delta: 1
existem duas raizes reais.
a raiz x1 e: 3.0
a raiz x2 é: 2.0
```
