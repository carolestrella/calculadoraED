

BIBLIOTECAS UTILIZADAS:

<stdlib.h>
<stdio.h>
<math.h>
<string.h>
"pilha.h"
"calculadora.h"

INSTRUCOES DE COMPILACAO:

Compilar no terminal com:
gcc -c calculadora.c
gcc -c pilha.c
gcc -o main main.c pilha.o calculadora.o -lm

Executar o comando: ./main
