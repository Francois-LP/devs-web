# CSS Grid
*CSS grid layout is a new layout model optimized for two-dimensional layouts.<br>
It's ideal for website layouts, forms, image galleries, and anything that requires precise and responsive positioning.*

## Table of Contents

1. [Examples of use ](#examples-of-use)
1. [Code tricks](#tricks)
1. [Additional links](#additional-links)

### 1. Examples of use 
- [Pages layouts](pages/)
- [Galleries layouts](galleries/)
- [Cards layouts](cards/)

### 2. Code tricks
* Define the number (and the widths) of columns in a grid layout
    ```css
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr;

    /* shorter equivalent code */
    grid-template-columns: repeat(6, 1fr);
    ```

* Define starting and ending column for an grid item 
    ```css
    grid-column-start: 2;
    grid-column-end: span 4;
     
    /* shorter equivalent code */
    grid-column: 2 / 6;     
    ```

* Define grid gap between columns and rows
    ```css
    grid-column-gap: 24px;
    grid-row-gap: 24px;

    /* shorter equivalent code */
    gap: 24px;
    ```

### 3. Additional links
* [Cheatsheet](https://formation.webdevpro.net/display-grid/grid-cheatsheet.pdf)
* [Les concepts de base](https://developer.mozilla.org/fr/docs/Web/CSS/CSS_Grid_Layout/Les_concepts_de_base)
* [Guide complet](https://la-cascade.io/css-grid-layout-guide-complet/)
* [Code : auto-fill vs auto-fit](https://codepen.io/SaraSoueidan/pen/JrLdBQ)
* [Code : alignement](https://formation.webdevpro.net/display-grid/08-alignement.html)
