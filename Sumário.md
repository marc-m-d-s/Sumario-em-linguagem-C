# 1. Introdução - em atualização

A linguagem C é uma linguagem de programação de nível médio, ou seja, ela fica entre o alto nível (como Python) e o baixo nível (como Assembly). Ela permite acesso direto à memória, uso de ponteiros e controle fino sobre o hardware, mas ainda assim com sintaxe legível.

Características principais:

- Simples, poderosa e rápida;
- Portável entre plataformas (Unix, Windows, Linux, microcontroladores);
- Ideal para sistemas operacionais, drivers, compiladores e jogos.

# 2. História

1969–1972 - Criada por Dennis Ritchie nos Laboratórios Bell (EUA), evoluindo da linguagem B;
1973 - O sistema operacional UNIX começou a ser reescrito em C (antes era Assembly);
1978 - Publicado o livro clássico “The C Programming Language” por Kernighan e Ritchie;
1989 - ANSI padroniza o C como ANSI C (C89);
1999 - Surge o padrão C99 com novas funcionalidades;
2011 e 2018	Padrões C11 e C18 introduzem melhorias modernas.

# 3. Conceitos Básicos

## 3.1. Compilador e interpretador:
## 3.2. Estrutura de um programa em C:

## 3.3. Primeiros comandos:

- 3.3.1. // - // Comentário com apenas uma linha;
- 3.3.2. /**/ - // Comentário em bloco (mais de uma linha), a frase deve estar entre asteriscos;

- 3.3.3. Bibliotecas

    - include <stdio.h> - // É uma biblioteca para entrada e saída padrão, usada para imprimir na tela (printf) e ler do teclado (scanf);
    - include <stdlib.h> - // É uma biblioteca que contém funções para alocação de memória, conversões e controle de processos, como malloc, free e atoi;
    - include <math.h> - // É uma biblioteca padrão da linguagem C que fornece funções matemáticas para realizar cálculos mais complexos do que os operadores básicos (+, -, *, /). Oferece funções matemáticas avançadas como potência, raiz quadrada e funções trigonométricas;
    - include <string.h> - // É uma biblioteca que fornece funções para manipulação de strings, incluindo cópia, concatenação e comparação de textos;
    - include <ctype.h> - // É uma biblioteca que contém funções para testar e converter caracteres, como verificar se é letra ou número e converter maiúsculas/minúsculas;
    - include <time.h> - // É uma biblioteca que fornece funções para manipulação de data e hora, incluindo obtenção do tempo atual e medição de intervalos;
    - include <stdbool.h> - // É uma biblioteca que define o tipo booleano em C, permitindo usar true e false para valores lógicos;
    - include <limits.h> - // É uma biblioteca que declara constantes que indicam os limites máximos e mínimos dos tipos primitivos da linguagem;
    - include <errno.h> - // É uma biblioteca que contém macros para identificar códigos de erro gerados por chamadas de sistema e funções da biblioteca.

- 3.3.4. Ponto de entrada de execução de um código em C:

int main() {
    // Código aqui
    return 0;
}

- 3.3.5. printf("Olá, mundo!\n"); - // <printf> É uma função da biblioteca <stdio.h> Serve para imprimir (exibir) uma mensagem na tela, geralmente no terminal/console. O nome vem de "print formatted" (imprimir com formatação).

    - 3.3.5.1. "Olá, mundo!\n" - // É uma string, ou seja, uma sequência de caracteres entre aspas duplas. É o que será exibido na tela. O conteúdo aqui é: Olá, mundo!;
    - 3.3.5.2. \n - // É um caractere especial de escape que representa uma quebra de linha. Faz com que o cursor vá para a linha de baixo depois de imprimir o texto;
    - 3.3.5.3. (;) - // Finaliza a instrução. Toda linha de código em C deve terminar com ponto e vírgula (;), a menos que esteja abrindo um bloco ({).

# 4. Variáveis e Tipos de Dados

- Tipos primitivos
- Conversões e modificadores

# 5. Operadores e Expressões

- Aritméticos
- Relacionais
- Lógicos

# 6. Estruturas de Controle

- Condições: `if`, `else`, `switch`
- Laços: `for`, `while`, `do...while`

# 7. Funções

- Declaração e chamada
- Escopo e retorno

# 8. Vetores e Matrizes

# 9. Ponteiros

# 10. Estruturas (`struct`)

# 11. Manipulação de Arquivos

# 12. Modularização e Organização

# 13. Criando uma Biblioteca em C

