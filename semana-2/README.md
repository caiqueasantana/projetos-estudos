# Semana 2: Fundamentos de Linguagem Java

## Objetivos da Semana:
- Compreender a **sintaxe básica** da linguagem Java e os **tipos de dados** disponíveis.
- Aprender sobre **operadores** e como utilizá-los em expressões.
- Estudar as **estruturas condicionais** (`if`, `switch`) para controle de fluxo em programas.
- Familiarizar-se com as **estruturas de repetição** (`for`, `while`) para executar blocos de código repetidamente.
- Compreender a importância de **métodos** e como implementar a **sobrecarga de métodos**.

---

## O que aprendi:

### 1. Sintaxe Básica e Tipos de Dados:
- A sintaxe básica inclui a declaração de variáveis, o uso de ponto e vírgula para finalizar instruções e a necessidade de definir o tipo de dado ao declarar uma variável.
- Os principais tipos de dados em Java incluem:
  - **`int`**: para números inteiros.
  - **`double`**: para números de ponto flutuante.
  - **`String`**: para cadeias de caracteres.

### 2. Operadores:
- Os **operadores** são símbolos que realizam operações em variáveis e valores. Aprendi sobre:
  - **Operadores aritméticos**: `+`, `-`, `*`, `/`.
  - **Operadores relacionais**: `==`, `!=`, `<`, `>`, `<=`, `>=`.
  - **Operadores lógicos**: `&&`, `||`, `!`.

### 3. Estruturas Condicionais:
- A estrutura **`if`** é utilizada para tomar decisões com base em condições.
  
    ```java
    if (condicao) {
        // ações
    }
    ```

- O **`switch`** é útil para selecionar entre várias opções com base no valor de uma variável.

    ```java
    switch (variavel) {
        case valor1:
            // ação
            break;
        // outros casos
    }
    ```

### 4. Estruturas de Repetição:
- A estrutura **`for`** permite iterar sobre uma sequência de valores.

    ```java
    for (int i = 0; i < 10; i++) {
        // ações
    }
    ```

- O **`while`** permite repetir ações enquanto uma condição for verdadeira.

    ```java
    while (condicao) {
        // ações
    }
    ```

### 5. Métodos e Sobrecarga de Métodos:
- **Métodos** são blocos de código que executam uma tarefa específica e ajudam a modularizar programas.
  
    ```java
    public int somar(int a, int b) {
        return a + b;
    }
    ```

- A **sobrecarga de métodos** permite ter múltiplos métodos com o mesmo nome, contanto que seus parâmetros sejam diferentes, facilitando a reutilização de código.

---

## Desafios e Lições Aprendidas:
- Enfrentei desafios ao implementar estruturas condicionais e percebi a importância de utilizá-las corretamente para o fluxo de execução dos programas.
- A prática com estruturas de repetição me ajudou a entender como executar blocos de código de forma eficiente.
- A experiência com métodos e sua sobrecarga me mostrou como organizar melhor o código, tornando-o mais legível e fácil de manter.

---

## Próximos Passos:
- Praticar mais a construção de métodos e a sua sobrecarga, criando programas que utilizam múltiplas versões de um método.
- Explorar conceitos mais avançados de Java, como tratamento de exceções e classes.

---

## Links Úteis:
- [Documentação Oficial do Java](https://docs.oracle.com/en/java/)
- [Java Tutorials - Oracle](https://docs.oracle.com/javase/tutorial/)

---

## Tarefas da Semana:
- Implementar os exercícios práticos e submetê-los para revisão.
- Desenvolver uma calculadora simples em Java utilizando métodos para diferentes operações (soma, subtração, etc.).
- Realizar um estudo mais aprofundado sobre estruturas de controle de fluxo e suas condições.