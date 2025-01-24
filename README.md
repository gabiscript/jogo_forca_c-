# Jogo da Forca em C++

Este é um simples jogo da forca implementado em C++. O programa permite ao jogador adivinhar palavras e gerencia um banco de palavras que pode ser atualizado diretamente durante o jogo.

## Funcionalidades

- **Jogo da Forca**: O jogador tenta adivinhar uma palavra secreta com um limite de 5 erros.
- **Banco de Palavras**: As palavras são armazenadas em um arquivo `palavras.txt`, que é carregado ao iniciar o jogo.
- **Adição de Novas Palavras**: O jogador pode adicionar novas palavras ao banco ao final do jogo.

## Requisitos

- Um compilador C++ (como GCC ou Clang).
- Um arquivo `palavras.txt` na mesma pasta do executável, contendo as palavras e o número de palavras na primeira linha.

### Exemplo do arquivo `palavras.txt`

3 melancia banana abacaxi

r
Copiar
Editar

## Como Jogar

1. Compile o código:
   ```bash
   g++ -o jogo_da_forca jogo_da_forca.cpp
Execute o programa:
bash
Copiar
Editar
./jogo_da_forca
Siga as instruções no terminal para adivinhar a palavra secreta.
Ao final do jogo, você pode optar por adicionar novas palavras ao banco.
Regras do Jogo
Cada letra correta revela sua posição na palavra secreta.
Cada chute incorreto adiciona um erro. Após 5 erros, o jogo termina.
O jogador vence se descobrir todas as letras antes de alcançar 5 erros.
Observações
Certifique-se de que o arquivo palavras.txt está acessível e formatado corretamente.
Caso o programa não consiga acessar o arquivo, ele exibirá uma mensagem de erro e encerrará a execução.
