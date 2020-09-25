# CSS Avançado

![screenshot](https://github.com/guiemi-learning-center/Advanced-CSS/blob/master/1-arquitetura-css/arquitetura-css-assets/assets/img/screenshot.jpg)

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

  

## Media queries (Responsividade)

```css
@media screen and (min-width: 768px) {
  .selector {
    padding: 2.5rem;
  }
};
```

