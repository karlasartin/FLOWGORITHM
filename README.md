# Flowgorithm — Lógica e Pensamento Computacional

### Algoritmos • Fluxogramas • Lógica de Programação • Resolução de Problemas

Este repositório reúne **exercícios, fluxogramas, atividades práticas e projetos desenvolvidos utilizando o Flowgorithm** como ferramenta de apoio à aprendizagem de **Algoritmos e Pensamento Computacional**.

A proposta é utilizar a representação visual dos algoritmos para compreender a **lógica de uma solução antes de concentrar a atenção na sintaxe de uma linguagem de programação**.

---

## Objetivo

O principal objetivo deste repositório é apoiar o desenvolvimento do **pensamento computacional** por meio da construção e execução visual de algoritmos.

Ao trabalhar com o Flowgorithm, buscamos desenvolver habilidades como:

- interpretação de problemas;
- decomposição de problemas;
- identificação de entradas e saídas;
- construção de sequências lógicas;
- utilização de variáveis;
- tomada de decisão;
- repetição;
- elaboração de algoritmos;
- testes e depuração;
- representação de soluções por fluxogramas.

---

# Por que utilizar o Flowgorithm?

Ao iniciar os estudos de programação, o estudante precisa compreender duas dimensões diferentes:

1. **a lógica utilizada para resolver o problema;**
2. **a sintaxe da linguagem utilizada para implementar a solução.**

O Flowgorithm permite concentrar inicialmente a atenção na primeira dimensão.

Em vez de começar diretamente com código, podemos representar visualmente o raciocínio:

```text
PROBLEMA
   ↓
ANÁLISE
   ↓
ALGORITMO
   ↓
FLUXOGRAMA
   ↓
TESTE
   ↓
RESULTADO
```

Depois que a lógica estiver compreendida, podemos avançar para sua implementação em uma linguagem de programação.

---

# O que é Flowgorithm?

O **Flowgorithm** é uma ferramenta educacional que permite desenvolver algoritmos utilizando **fluxogramas executáveis**.

Os comandos são representados graficamente por símbolos, permitindo visualizar a sequência de execução do algoritmo.

Com ele podemos trabalhar conceitos como:

- declaração de variáveis;
- atribuição;
- entrada de dados;
- saída de dados;
- expressões;
- operadores;
- decisões;
- estruturas de repetição;
- funções.

---

# Do problema ao programa

Uma das ideias centrais deste repositório é desenvolver a seguinte progressão:

```text
COMPREENDER O PROBLEMA
          ↓
IDENTIFICAR ENTRADAS E SAÍDAS
          ↓
DECOMPOR O PROBLEMA
          ↓
CONSTRUIR O ALGORITMO
          ↓
REPRESENTAR NO FLOWGORITHM
          ↓
EXECUTAR
          ↓
TESTAR
          ↓
CORRIGIR
          ↓
VALIDAR A SOLUÇÃO
          ↓
IMPLEMENTAR EM UMA LINGUAGEM
```

---

# Conceitos trabalhados

## 1. Entrada e saída de dados

Um algoritmo geralmente recebe informações, realiza algum processamento e apresenta um resultado.

```text
ENTRADA
   ↓
PROCESSAMENTO
   ↓
SAÍDA
```

Exemplo:

```text
Digite a nota 1
Digite a nota 2
       ↓
Calcular média
       ↓
Exibir resultado
```

---

## 2. Variáveis

As variáveis permitem armazenar dados utilizados durante a execução do algoritmo.

Exemplos:

```text
idade
nota
media
nome
resultado
```

---

## 3. Operadores

Durante a construção dos algoritmos são utilizados diferentes operadores.

### Operadores aritméticos

```text
+
-
*
/
```

### Operadores relacionais

```text
>
<
>=
<=
==
!=
```

### Operadores lógicos

```text
AND
OR
NOT
```

---

# Estruturas de decisão

As estruturas condicionais permitem que o algoritmo escolha caminhos diferentes dependendo de uma condição.

Exemplo:

```text
        NOTA
          ↓
     nota >= 6?
       /      \
     SIM      NÃO
      ↓        ↓
  APROVADO  REPROVADO
```

Esse tipo de estrutura permite trabalhar:

- condições;
- comparações;
- operadores relacionais;
- operadores lógicos;
- decisões simples;
- decisões compostas.

---

# Estruturas de repetição

Nem sempre queremos executar uma operação apenas uma vez.

As estruturas de repetição permitem executar um conjunto de instruções várias vezes.

Podemos trabalhar situações como:

```text
INÍCIO
   ↓
contador = 1
   ↓
contador <= 10?
   ↓
SIM → executar operação
   ↓
contador = contador + 1
   ↓
voltar para condição
```

As estruturas de repetição são fundamentais para compreender posteriormente comandos como:

```text
for
while
do-while
```

---

# Hands On

As atividades **Hands On** são utilizadas para transformar os conceitos apresentados em problemas que precisam ser efetivamente resolvidos.

Durante essas atividades, o estudante deverá:

1. compreender o problema;
2. identificar os dados de entrada;
3. identificar o resultado esperado;
4. definir o processamento necessário;
5. construir o fluxograma;
6. executar o algoritmo;
7. testar diferentes entradas;
8. identificar possíveis erros;
9. corrigir a solução;
10. validar o resultado.

> **Algoritmos são aprendidos construindo, testando, errando, corrigindo e reconstruindo soluções.**

---

# Tipos de atividades

Este repositório poderá conter exercícios envolvendo:

### Nível 1 — Algoritmos sequenciais

- entrada e saída;
- variáveis;
- operações matemáticas;
- conversões;
- cálculos simples.

### Nível 2 — Estruturas condicionais

- `if`;
- `if / else`;
- condições compostas;
- operadores relacionais;
- operadores lógicos.

### Nível 3 — Estruturas de repetição

- contadores;
- acumuladores;
- `while`;
- repetições controladas por condição.

### Nível 4 — Problemas integradores

- calculadoras;
- sistemas de classificação;
- menus;
- validação de dados;
- pequenos sistemas;
- problemas envolvendo múltiplas estruturas.

---

# Exemplo de problema

## Cálculo da média

Desenvolver um algoritmo que:

1. leia duas notas;
2. calcule a média;
3. verifique a situação do estudante;
4. apresente o resultado.

### Entrada

```text
nota1
nota2
```

### Processamento

```text
media = (nota1 + nota2) / 2
```

### Decisão

```text
media >= 6?
```

### Saída

```text
Média
Situação
```

Antes de transformar esse problema em código, podemos representá-lo visualmente no Flowgorithm.

---

# Estrutura do Repositório

```text
flowgorithm/
│
├── aulas/
│
├── exemplos/
│
├── exercicios/
│
├── hands-on/
│
├── desafios/
│
├── projetos/
│
├── materiais/
│
└── README.md
```

---

# Organização dos arquivos

Uma possível padronização para os arquivos é:

```text
01-entrada-saida.fprg
02-variaveis.fprg
03-operadores-aritmeticos.fprg
04-operadores-relacionais.fprg
05-estrutura-condicional.fprg
06-condicional-composta.fprg
07-while.fprg
08-contadores.fprg
09-acumuladores.fprg
10-projeto-integrador.fprg
```

Isso facilita a identificação dos conteúdos e permite acompanhar a progressão da aprendizagem.

---

# Do Flowgorithm para a programação

O Flowgorithm não é o objetivo final.

Ele funciona como uma **ponte para a programação**.

```text
PROBLEMA
   ↓
PENSAMENTO COMPUTACIONAL
   ↓
ALGORITMO
   ↓
FLOWGORITHM
   ↓
COMPREENSÃO DA LÓGICA
   ↓
LINGUAGEM DE PROGRAMAÇÃO
```

Quando o estudante compreende a estrutura lógica do algoritmo, torna-se mais fácil entender sua implementação em linguagens como:

```text
C
Python
C++
Java
```

---

# Competências desenvolvidas

As atividades deste repositório buscam desenvolver:

- raciocínio lógico;
- pensamento computacional;
- abstração;
- decomposição de problemas;
- reconhecimento de padrões;
- elaboração de algoritmos;
- representação por fluxogramas;
- resolução de problemas;
- testes;
- depuração;
- autonomia na construção de soluções.

---

# Take Away

Ao final de cada atividade, é importante responder:

> **Qual conceito de programação utilizamos para resolver este problema?**

A proposta pode ser resumida pela sequência:

```text
COMPREENDER
     ↓
DECOMPOR
     ↓
MODELAR
     ↓
CRIAR O ALGORITMO
     ↓
VISUALIZAR
     ↓
EXECUTAR
     ↓
TESTAR
     ↓
CORRIGIR
     ↓
RESOLVER
```

---

# Relação com Algoritmos e Pensamento Computacional

Este repositório complementa os estudos da disciplina **Algoritmos e Pensamento Computacional**.

Enquanto o repositório principal organiza os conteúdos da disciplina, este espaço concentra as atividades e experimentações realizadas utilizando **Flowgorithm**.

A proposta é estabelecer uma transição progressiva:

**Pensamento Computacional → Algoritmo → Fluxograma → Flowgorithm → Código**

---

## Professora

**Profa. Karla Roberto Sartin**

**Computação | Engenharia | Inteligência Artificial | Educação**

---

> **Antes de escrever código, precisamos aprender a estruturar uma solução.**
