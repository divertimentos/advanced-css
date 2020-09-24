# CSS Avançado

# Coisas novas que aprendi

## BEM (Block, Element, Modifier)

* `bloco`
* `bloco__elemento`
* `bloco--modificador`
* `bloco__elemento--modificador`

## Calc

* Para que um banner se estendesse por toda a tela (`height: 100vh;`), mas desconsiderasse a altura da navbar, aprendi a usar a função `calc();` para subtrair 72 pixels:

  ```css
  .banner__imagem {
    height: calc(100vh - 72px);
    width: 100%;
  }
  ```

  