# Calculadora Científica em C

Este projeto é uma **Calculadora Científica completa**, desenvolvida em **Linguagem C**, capaz de realizar operações básicas, avançadas, funções trigonométricas, logaritmos, cálculos especiais e até operações com matrizes.  
Também possui **histórico de operações**, registrando tudo o que o usuário faz.

---

##  Funcionalidades

A calculadora contém **24 tipos diferentes de operações**, incluindo:

###  Operações Básicas
- Soma  
- Subtração  
- Multiplicação  
- Divisão  

###  Funções Matemáticas Avançadas
- Potência  
- Raiz quadrada  
- Logaritmo natural (ln)  
- Logaritmo base 10  
- Seno  
- Cosseno  
- Tangente  
- Exponencial (e^x)  
- Valor absoluto  
- Arredondamentos: ceil, floor e round  
- Conversão: graus ↔ radianos  
- Cálculo da hipotenusa  
- Área do círculo  

###  Outras Funções
- Fatorial  
- Histórico de cálculos  
- Soma de matrizes 3x3  
- Multiplicação de matrizes 3x3  

---

##  Estrutura do Código

O programa é dividido em funções para melhorar organização:

- `fatorial()` — calcula o fatorial de um número  
- `soma_matrizes()` — realiza a soma de matrizes 3x3  
- `multiplicacao_matrizes()` — multiplica matrizes 3x3  
- `registrar_historico()` — salva uma operação no histórico  
- `exibir_historico()` — exibe todas as operações realizadas  
- `main()` — menu e lógica principal  

---

##  Como Compilar e Executar

###  1. Compilar
Se estiver usando **GCC**:
gcc calculadora.c -o calculadora -lm

**Observação:**  
O `-lm` é necessário por causa das funções matemáticas da biblioteca `math.h`.

###  2. Executar

No Linux ou macOS:  
./calculadora

No Windows (MinGW):  
calculadora.exe

---

## Exemplo de Execução

## Menu principal:
Soma

1-Subtração
2-Multiplicação
3-Divisão
4-Exibir Histórico
5-Soma de Matrizes
6-Multiplicação de Matrizes
7-Sair

## Exemplo de cálculo:
Digite dois números: 8 2
Resultado: 10.0000

---

##  Histórico de Cálculos

A calculadora registra:

- Tipo da operação  
- Valores digitados  
- Resultado obtido  

Exemplo:
Soma: 8.0000 2.0000 = 10.0000
Fatorial: 5 = 120
Seno: 90° = 1.0000

---

## Tecnologias Utilizadas

- Linguagem C  
- `stdio.h`, `math.h`, `stdlib.h`  
- Lógica estruturada  
- Matrizes 3x3  
