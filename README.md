# Calculadora de Partidas Rankeadas

## Descrição
Este projeto consiste em uma função que calcula o saldo de vitórias de um jogador e determina seu nível com base na quantidade de vitórias obtidas.

## Tecnologias Utilizadas
- JavaScript

## Como Funciona
A função `calcularNivel(vitorias, derrotas)` recebe como parâmetros a quantidade de vitórias e derrotas do jogador. Em seguida, ela calcula o saldo de vitórias e determina o nível do jogador de acordo com as seguintes regras:

- **Ferro**: menos de 10 vitórias
- **Bronze**: entre 11 e 20 vitórias
- **Prata**: entre 21 e 50 vitórias
- **Ouro**: entre 51 e 80 vitórias
- **Diamante**: entre 81 e 90 vitórias
- **Lendário**: entre 91 e 100 vitórias
- **Imortal**: 101 ou mais vitórias

Por fim, o programa exibe uma mensagem com o saldo de vitórias e o nível do jogador.

## Exemplo de Uso
```javascript
calcularNivel(85, 20);
// Saída: O Herói tem um saldo de 65 vitórias e está no nível de Diamante
```

## Como Executar
1. Copie o código para um ambiente JavaScript (navegador ou Node.js).
2. Chame a função `calcularNivel(vitorias, derrotas)` passando os valores desejados.
3. Veja a saída no console.

## Autor
Projeto desenvolvido para fins de aprendizado e prática de lógica de programação.

