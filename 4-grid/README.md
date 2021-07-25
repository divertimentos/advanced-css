# curso-grid-layout-alura

## Coisas interessantes que aprendi:

### Shorthands

* Podemos usar um *shorthand* para o `background()`. Em vez de:

  ```css
    background-image: url('../img/fortnite.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  ```

  pode-se utilizar apenas:

  ```css
  background: url('../img/fortnite.jpg') center / cover no-repeat;
  ```
  
  

* Há também um shorthand para `grid-column` e `grid-row`. Em vez de:

  ```css
    grid-column-start: 1;
    grid-column-end: 4;
  
    grid-row-start: 1;
    grid-row-end: 3;
  ```

  podemos utilizar:

  ```css
    grid-column: 1 / 4;
    grid-row: 1 / 3;
  ```

  
