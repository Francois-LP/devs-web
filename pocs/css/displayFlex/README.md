# CSS Flexbox
*The Flexible Box Layout Module, makes it easier to design flexible responsive layout structure without using float or positioning.*

## Table of Contents

1. [Examples of use](#examples-of-use)
1. [Tutorials links](#tutorials-links)
1. [Code tricks](#tricks)
1. [Additional links](#additional-links)

### 1. Examples of use
- [Flex Container](flexContainer.html)
    - flex-direction
    - flex-wrap
    - justify-content
    - align-items
    - align-content
    - center perfectly
- [Flex Items](flexItems.html)
    - order
    - flex-grow
    - flex-shrink
    - flex-basis
    - flex
    - align-self

### 2. Tutorials links
* [CSS Flex Container](https://www.w3schools.com/css/css3_flexbox_container.asp)
* [CSS Flex Items](https://www.w3schools.com/css/css3_flexbox_items.asp)

### 3. Code tricks
* display 
    ```css
    .container {
        display: flex; /* or inline-flex */
    }
    ```
* flex-direction
    ```css
    .container {
        flex-direction: row | row-reverse | column | column-reverse;
    }
    ```
* flex-wrap
    ```css
    .container {
        flex-wrap: nowrap | wrap | wrap-reverse;
    }
    ```
* flex-flow
    ```css
    .container {
        flex-flow: column wrap;
    }
    ```
* justify-content
    ```css
    .container {
        justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly | start | end | left | right ... + safe | unsafe;
    }
    ```
* align-content
    ```css
    .container {
        align-content: flex-start | flex-end | center | space-between | space-around | space-evenly | stretch | start | end | baseline | first baseline | last baseline + ... safe | unsafe;
    }
    ```
* align-self
    ```css
    .item {
        align-self: auto | flex-start | flex-end | center | baseline | stretch;
    }
    ```

### 4. Additional links
* [Cheatsheet](https://www.alsacreations.com/xmedia/guidelines/flexbox-cheatsheet.pdf)
* [Cheatsheet (with illustrations)](https://jaetheme.com/wp-content/themes/paris/pdf/flexbox-memo.pdf)
* [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [The Complete CSS Flex Box Tutorial](https://jstutorial.medium.com/the-complete-css-flex-box-tutorial-d17971950bdc)
