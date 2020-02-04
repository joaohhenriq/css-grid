# CSS GRID

- Bidimensional
- Divisão de toda a página em linhas em colunas
- Colocar elementos onde quiser nessa divisão

## GRID ou FLEXBOX

- `Grid`: Duas dimensões (colunas e linhas)
- `Flexbox`: Uma dimensão (ou coluna ou linha)
- Um complementa o trabalho do outro



## Propriedades

### Container
- `display: grid` (inicia o container falando que é um grid)
- `grid-template-columns` (fatia as colunas, diz quantas colunas o grid possui)
- `grid-template-rows` (fatia as linhas, diz quantas linhas o grid vai possuir)
- `grid-gap` (espaçamentos)
    - grid-row-gap (espaçamentos nas linhas)
    - grid-column-gap (espaçamentos nas colunas)
- `grid-template-areas` (delimita areas do grid)


### Item(s)
- `grid-column`
    - grid-column-start
    - grid-column-end
- `grid-row`
    - grid-row-start
    - grid-row-end
- `grid-area`



## Grid: Alinhamento

Existem 6 propriedades para alinhamento:
1. `justify-content`
2. `align-content`
3. `justify-items`
4. `align-items`
5. `justify-self`
6. `align-self`

Vamos separá-los em 2 grupos
1. `justify` e `align`
2. `content`, `items` e `self`

### Justify e Align

Sabendo que o grid é bidimensional, nós temos o eixo x e o y.

### Content, Items e Self
