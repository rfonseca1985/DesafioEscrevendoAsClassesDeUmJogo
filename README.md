# Jogo de Heróis

Bem-vindo ao Jogo de Heróis, onde você pode criar e controlar heróis de diferentes tipos em emocionantes aventuras!

## Sobre o Jogo

Este jogo permite que você crie heróis personalizados e os faça realizar ataques baseados em seus tipos. Cada tipo de herói tem um ataque único, proporcionando uma experiência variada durante o jogo.

## Classes e Objetos

### Classe Heroi

A classe `Heroi` representa um herói no jogo e possui as seguintes propriedades:

- `nome`: Nome do herói.
- `idade`: Idade do herói.
- `tipo`: Tipo do herói (ex: guerreiro, mago, monge, ninja).

Além disso, a classe possui um método:

#### `atacar()`

O método `atacar` exibe uma mensagem indicando o tipo de ataque do herói, com base em seu tipo.

## Exemplo de Uso

```javascript
// Criando instância da classe Heroi
const heroi1 = new Heroi('Aragorn', 30, 'guerreiro');

// Chamando o método atacar para o herói
heroi1.atacar();
