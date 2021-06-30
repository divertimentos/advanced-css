# CSS Avançado

# Arquitetura CSS: Descomplicando os problemas (Curso 1/6)

![screenshot](https://github.com/guilherme-learning-center/advanced-css/blob/main/1-arquitetura-css/arquitetura-css-assets/assets/img/screenshot.jpg)

## Coisas novas que aprendi

### BEM (Block, Element, Modifier)

* `bloco`
* `bloco__elemento`
* `bloco--modificador`
* `bloco__elemento--modificador`

### Calc

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

# Sass e Compass: Descomplicando o  CSS (Curso 2/6)

![sass-screenshot](https://github.com/guilherme-learning-center/advanced-css/blob/main/2-sass-compass/media/sass-screenshot.png)



# Flexbox: Posicione elementos na tela (Curso 3/6)

# CSS Grid: Simplificando Layouts (Curso 4/6)

# Web Design Responsivo: Páginas que se adaptam do mobile ao desk (Curso 5/6)

# Layouts Responsivos: Trabalhando com layouts mobile (Curso 6/6)

()P.S.: a branch padrão agora é a Main)

