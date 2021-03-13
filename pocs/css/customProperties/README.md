# CSS custom properties (variables)
*Custom properties (sometimes referred to as CSS variables or cascading variables) are entities defined by CSS authors that contain specific values to be reused throughout a document.*

## Table of Contents

1. [Syntax](#syntax)
1. [Examples of use](#examples-of-use)
1. [Links](#links)

### 1. Syntax
* Declaring a custom property
    ```css
    :root {
      --main-bg-color: blue;
    }
    ```

* Using a custom property
    ```css
    element {
      background-color: var(--main-bg-color);
    }
    ```

* Redefine a custom property locally
    ```css
    element {
      --main-bg-color: red;
      background-color: var(--main-bg-color);
    }
    ```

### 2. Examples of use 
- [Basic use cases](basicUseCases.html)
- [Theme of an element](themeOfAnElement.html)
- [Theme of multiple elements](themeOfMultipleElements.html)

### 3. Links
* [Custom properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)
* [Basic use cases tutorial](https://www.youtube.com/watch?v=pi-jnnNFTiQ)
* [Theme of   one or multiple elements tutorial](https://blogs.infinitesquare.com/posts/web/css-vars-le-guide-complet)
