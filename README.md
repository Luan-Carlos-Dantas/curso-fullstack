# Curso FullStack Rocketseat 🚀
## CSS
Cascadin Stylesheet

---

## O que é CSS

  - Folha de estilo em cascata
  - Propriedade e valor
  - Estilos para o HTML
  - Arquivos em `.css`

## Valores e unidades de medida
  - Cada propriedade possui valores
  `property: value`
  `<data-type>`

## display: block

1. Ocupa toda a linha, como um `bloco`;
2. `width` e `height` são aplicados;
3. `padding`, `margin` e `border` funcionam por completo;

> elementos
`<div>, <main>, <p> e etc.`

## display: inline

1. Ocupa apenas o espaço do elemento;
2. Elementos poderão ficar em `linha`;
3. `width` e `height` não se aplicam;
4. Aplicamos apenas os valores horizontaios de `margin`, `padding` e `border`

> elementos
`<a>, <span>, <strong> e etc.`

## GRID

Todo grid é composto de 2 principais grupos
`contatiner` o pai e `itens` os filhos

---
### Container
 - `display:grid`
 - `grid-template;`
  - `grid-template-columns;`
  - `grid-template-rows`
  - `grid-template-areas`

--
### Itens
  - `grid-column;`
    - `grid-column-start;`
    - `grid-column-end;`
  - `grid-row;`
    - `grid-row-start;`
    - `grid-row-end;`
  - `grid-area`

  --

  ### Propriedades de alinhamento

  Existem 9 propriedades fundamentais

  **6 aplicadas em containers**
  `align-content`
  `justify-content`
  `place-content`

  `align-items`
  `justify-content`
  `place-content`

  **3 aplicadas em items**
  `align-self`
  `justify-self`
  `place-self`

  Então podemos separar em 3 grupos:
  `align`, `justify`, `place`

  E cada um deles irá observar ou
  - conteúdo
  - item
  - pai

## CSS Functions
  ### Funçoes aplicadas como valores
    - not()
    - :has()

  ### Transform
    - translate()
    - rotate()
    - scale()

  ### Math
    - basic arithmetic
      - calc()
    - comparison
      - min(unit 1, unit 2)
      - max(unit 1, unit 2)
      - clamp(min, middle, max)
    - outhers

  ### Filter
    - hue()
    - saturation()
    - brightness()
    - contrast()
    - drop-shadow()
    - opacity()
    - invert()
    - hue-saturation()
    - saturate()

  ### Color
    - rgba(red, green, blue, alpha)
    - hsla(hue, saturation, lightness, alpha)
    - color-mix()
    - #fff

  ### Gradient
    - linear-gradient(deg, red, green, blue)
    - radial-gradient()

  ### References
    - var()
    - url()
    - attr()

## Responsividade
  ### Media Queries
    `@media screen and min/max{}`
    `<meta name="viewport" content="width=device=width, initial-scale-1.0">`
    - @media
      - breakpoints
        - px
        - rem
        - named
      - rules
        - min
        - max
      - range
        - > >= <= <
        - width < 480px
