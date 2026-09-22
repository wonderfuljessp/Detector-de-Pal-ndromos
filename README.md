### NOME DO PROJETO
Detector de Palindromos
### DESCRIÇÃO
Um programa modular em C que verifica se uma palavra digitada é um palíndromo (lê-se de igual forma de trás para a frente), ignorando a diferença entre letras maiúsculas e minúsculas.
### LÓGICA UTILIZADA
Implementação de um ciclo for com dois iteradores simultâneos que caminham das extremidades para o centro da palavra. A verificação é interrompida imediatamente com um `break;` caso sejam encontrados caracteres diferentes, poupando processamento. O resultado final é gerido através de uma variável de estado (flag). A biblioteca `<string.h>` foi utilizada para determinar o comprimento do vetor com `strlen()`. Para resolver o problema de capitalização, a função `tolower()` da biblioteca `<ctype.h>` normaliza os caracteres antes de cada comparação.
### COMO EXECUTAR
Compilar o código no terminal com `gcc palindromos.c -o palindromos` e executar com `palindromos.exe` (Windows) ou `./palindromos` (Linux/Mac).  
