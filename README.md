# Sistema de Níveis para Heróis

Este projeto em JavaScript é uma lógica simples de classificação de heróis com base em seus pontos de experiência (XP). De acordo com a quantidade de XP, o herói recebe uma classificação em diferentes níveis, como Ferro, Bronze, Prata, entre outros, até o nível máximo de Radiante.

## Descrição do Código

O código define um herói com o nome {name} e um valor de experiência {xp}`. Com uma série de instruções `if...else`, ele determina o nível do herói com base em faixas de XP predefinidas e exibe o resultado no console.

### Níveis de Classificação

Os níveis de experiência estão organizados da seguinte maneira:

- **Ferro**: XP inferior a 1000
- **Bronze**: XP entre 1001 e 2000
- **Prata**: XP entre 2001 e 5000
- **Ouro**: XP entre 5001 e 7000
- **Platina**: XP entre 7001 e 8000
- **Ascendente**: XP entre 8001 e 9000
- **Imortal**: XP entre 9001 e 10000
- **Radiante**: XP superior a 10000

### Funcionamento

1. O código verifica a quantidade de XP.
2. Baseado no valor de XP, ele classifica o herói em um dos níveis acima.
3. A classificação é exibida no console com uma mensagem indicando o nome do herói, seu XP e o nível correspondente.

### Exemplo de Saída

No caso do herói `"Sofia"` com `19748` pontos de experiência, a saída será:

```plaintext
O herói Sofia tem 19748 pontos de experiência e está no nível Radiante.
