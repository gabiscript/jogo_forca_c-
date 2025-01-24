# Jogo da Forca em C++

Um jogo da forca simples, implementado em C++, com suporte a banco de palavras dinâmico.

## Funcionalidades
- **Jogo da Forca**: Adivinhe a palavra secreta com até 5 erros permitidos.
- **Banco de Palavras**: As palavras são armazenadas no arquivo `palavras.txt`.
- **Adição de Novas Palavras**: Após vencer o jogo, você pode adicionar palavras ao banco.

## Requisitos
- Compilador C++ (GCC, Clang, etc.).
- Um arquivo `palavras.txt` no mesmo diretório do executável, contendo:
  - Primeira linha: número de palavras.
  - Demais linhas: as palavras.

### Exemplo do arquivo `palavras.txt`:
```
3
melancia
banana
abacaxi
```

## Como Jogar
1. Compile o programa:
   ```bash
   g++ -o jogo_da_forca jogo_da_forca.cpp
   ```
2. Execute:
   ```bash
   ./jogo_da_forca
   ```
3. Siga as instruções no terminal para adivinhar a palavra secreta.
4. Ao vencer, você poderá adicionar novas palavras ao banco.

## Regras do Jogo
- Cada chute correto revela letras na palavra.
- 5 chutes errados levam à derrota.
- O jogo é vencido ao adivinhar todas as letras da palavra.

## Observações
- Certifique-se de que `palavras.txt` está configurado corretamente.
- Se o arquivo não for acessível, o programa exibirá um erro e encerrará.

## Melhorias Futuras
- Suporte a caracteres especiais.
- Interface gráfica para maior interatividade.
- Validação mais robusta para entradas de usuário.

## Licença
Este projeto é de uso livre e tem fins educativos.

Divirta-se jogando!

