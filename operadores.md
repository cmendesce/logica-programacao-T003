
# Operadores

Esta seção descreve os operadores e contém informações sobre precedência de operadores.

## Atribuição `=`

```javascript
x = y;
```

## Adição `+`

```javascript
x = x + y;

// Mesmo que

x += y;
```

## Subtração `-`

```javascript
x = x - y;

// Mesmo que

x -= y;
```

## Multiplicação `*`

```javascript
x = x * y;

// Mesmo que

x *= y;
```

## Divisão `\`

```javascript
x = x / y;

// Mesmo que

x /= y;
```

## Resto `%`

Retorna o inteiro restante da divisão dos dois operandos.

```javascript
x = x % y;

// Mesmo que

x %= y;

```

## Exponecial `**`

```javascript
x = x ** y;

// Mesmo que

x **= y;
```

## Incremento `++`

Adiciona um ao seu operando. Se usado como operador prefixado (`++x`), retorna o valor de seu operando após a adição. Se usado como operador pósfixado (`x++`), retorna o valor de seu operando antes da adição.

Se `x` é 3, então `++x` define `x` como 4 e retorna 4, enquanto `x++` retorna 3 e, somente então, define `x` como 4.

## Decremento

Subtrai um de seu operando. O valor de retorno é análogo àquele do operador de incremento.

Se `x` é 3, então `--x` define `x` como 2 e retorna 2, enquanto `x--` retorna 3 e, somente então, define `x` como 2.

# Operadores de Comparação

## Igual `==`

Retorna verdadeiro caso os **operandos sejam iguais**.

```javascript
var ehIgual;

ehIgual = 3 == 3;
document.write(ehIgual);

ehIgual = "3" == 3;
document.write(ehIgual);

ehIgual = 3 == '3';
document.write(ehIgual);
```

## Não igual `!=`

Retorna verdadeiro caso os **operandos não sejam iguais**.

```javascript
var ehIgual;

ehIgual = 1 != 4;
document.write(ehIgual);

ehIgual = 1 != "3";
document.write(ehIgual);
```

## Estritamente Igual `===`

Retorna verdadeiro caso os operandos sejam iguais e do mesmo tipo.

```javascript
var ehIgual = 3 === 3;
document.write(ehIgual);
```

## Estritamente não Igual `!==`

```javascript
var ehIgual;

ehIgual = 3 !== 3;
document.write(ehIgual);

ehIgual = "3" !== 3;
document.write(ehIgual);

ehIgual = 3 !== '3';
document.write(ehIgual);
```

## Maior que `>`

```javascript
var var1 = 2;
var var2 = 3;

var ehMaior = var2 > var1;
document.write(ehMaior);
```

## Maior que ou igual `>=`

```javascript
var var1 = 2;
var var2 = 3;

var ehMaiorIgual = var1 >= var2;

document.write(ehMaiorIgual);
```

## Menor que `<`

```javascript
var var1 = 2;
var var2 = 3;

var ehMenor = var1 <= var2;

document.write(ehMaiorIgual);
```

## Menor que ou igual `<=`

```javascript
var var1 = 2;
var var2 = 3;

var ehMenorIgual = var1 <= var2;

document.write(ehMenorIgual);
```


# Exercícios

1. Ler um valor e escrever a mensagem É MAIOR QUE 10! se o valor lido for maior que 10, caso contrário escrever NÃO É MAIOR QUE 10! 
2. Ler um valor e escrever se é positivo ou negativo (considere o valor zero como positivo).
3. As maçãs custam R$ 1,30 cada se forem compradas menos de uma dúzia, e R$ 1,00 se forem compradas pelo menos 12. Escreva um programa que leia o número de maçãs compradas, calcule e escreva o custo total da compra.
4. Ler as notas da 1a. e 2a. avaliações de um aluno. Calcular a média aritmética simples e escrever uma mensagem que diga se o aluno foi ou não aprovado (considerar que nota igual ou maior que 6 o aluno é aprovado). Escrever também a média calculada. 
5. Ler dois valores (considere que não serão lidos valores iguais) e escrever o maior deles.
