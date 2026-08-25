# Cálculo do Perímetro de uma Circunferência — Flowgorithm

## Sobre a atividade

Este exercício foi desenvolvido utilizando o **Flowgorithm** com o objetivo de praticar conceitos iniciais de **lógica de programação e construção de algoritmos**.

O programa solicita ao usuário o valor do **raio de uma circunferência**, calcula seu perímetro e acrescenta **1 cm** ao resultado.

---

## Objetivos de aprendizagem

Com esta atividade, são trabalhados os seguintes conceitos:

- construção de algoritmos;
- declaração de variáveis;
- tipos de dados;
- entrada de dados;
- saída de dados;
- atribuição;
- operadores aritméticos;
- expressões matemáticas;
- sequência lógica de execução.

---

## Problema

Desenvolver um algoritmo que receba o valor do raio de uma circunferência, calcule seu perímetro e acrescente **1 cm** ao resultado.

A fórmula utilizada é:

```text
P = 2 × π × r
```

Como o exercício solicita acrescentar 1 cm:

```text
P = (2 × π × r) + 1
```

No algoritmo foi utilizado:

```text
π ≈ 3.14156
```

Portanto:

```text
perimetro = (2 * raio * 3.14156) + 1
```

---

# Estrutura do algoritmo

O funcionamento do programa pode ser representado por:

```text
INÍCIO
   ↓
Declarar as variáveis
raio e perimetro
   ↓
Solicitar o raio
   ↓
Ler raio
   ↓
Calcular
perimetro = (2 × raio × 3.14156) + 1
   ↓
Exibir resultado
   ↓
FIM
```

---

## Variáveis utilizadas

### `raio`

Armazena o valor do raio informado pelo usuário.

Tipo:

```text
Real
```

### `perimetro`

Armazena o resultado do cálculo do perímetro acrescido de 1 cm.

Tipo:

```text
Real
```

---

# Entrada de dados

O algoritmo apresenta a mensagem:

```text
Digite o valor do raio em cm.
```

Em seguida, o valor informado pelo usuário é armazenado na variável:

```text
raio
```

---

# Processamento

O cálculo realizado pelo algoritmo é:

```text
perimetro = (2 * raio * 3.14156) + 1
```

Podemos decompor essa expressão:

```text
2 × raio × π
```

calcula o perímetro da circunferência.

Depois:

```text
+ 1
```

acrescenta **1 cm** ao resultado.

---

# Saída de dados

Após realizar o cálculo, o programa apresenta:

```text
O valor do perímetro + 1cm é:
```

seguido do valor armazenado na variável:

```text
perimetro
```

e da unidade:

```text
cm
```

---

# Exemplo de execução

Considere:

```text
raio = 5 cm
```

O algoritmo realiza:

```text
perimetro = (2 × 5 × 3.14156) + 1
```

```text
perimetro = 31.4156 + 1
```

```text
perimetro = 32.4156 cm
```

Portanto, a saída será aproximadamente:

```text
O valor do perímetro + 1cm é: 32.4156 cm
```

---

# Entrada → Processamento → Saída

Este exercício também permite visualizar uma estrutura fundamental da programação:

```text
┌───────────────────────┐
│        ENTRADA        │
│                       │
│       raio (cm)       │
└───────────┬───────────┘
            ↓
┌───────────▼───────────┐
│     PROCESSAMENTO     │
│                       │
│ P = (2 × π × r) + 1  │
└───────────┬───────────┘
            ↓
┌───────────▼───────────┐
│         SAÍDA         │
│                       │
│  perímetro + 1 cm     │
└───────────────────────┘
```

---

# Conceitos de programação utilizados

## 1. Declaração de variáveis

Foram declaradas duas variáveis:

```text
raio
perimetro
```

Ambas são do tipo:

```text
Real
```

---

## 2. Entrada

O comando de entrada recebe o valor informado pelo usuário e o armazena em:

```text
raio
```

---

## 3. Atribuição

A variável `perimetro` recebe o resultado da expressão:

```text
(2 * raio * 3.14156) + 1
```

---

## 4. Saída

O resultado é apresentado ao usuário utilizando um comando de saída.

---

# Arquivo

O algoritmo está disponível no arquivo:

```text
calculo perimetro de circulo.fprg
```

O arquivo `.fprg` pode ser aberto e executado utilizando o **Flowgorithm**.

---

# Hands On

Depois de executar o algoritmo original, experimente modificar o programa.

### Desafio 1

Altere o valor do raio e observe como o perímetro se modifica.

### Desafio 2

Crie uma variável:

```text
pi
```

e armazene nela:

```text
3.14156
```

Depois utilize:

```text
perimetro = (2 * raio * pi) + 1
```

### Desafio 3

Modifique o algoritmo para calcular também a área do círculo:

```text
A = π × r²
```

### Desafio 4

Faça o programa apresentar:

```text
Raio:
Perímetro:
Área:
```

---

# Take Away

Neste exercício podemos observar uma das estruturas mais importantes de um algoritmo:

```text
ENTRADA
   ↓
PROCESSAMENTO
   ↓
SAÍDA
```

O usuário fornece o **raio**, o algoritmo realiza uma **expressão matemática** e apresenta o **resultado**.

> Antes de desenvolver programas mais complexos, é fundamental compreender como dados entram no algoritmo, são processados e produzem uma saída.

---

## Disciplina

**Algoritmos e Pensamento Computacional**

### Profa. Karla Roberto Sartin

**Computação | Engenharia | Inteligência Artificial | Educação**
