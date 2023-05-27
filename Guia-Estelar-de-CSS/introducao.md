# Introdução

## O que significa CSS ?

* Cascading Style Sheet
* Código para criar estilos no HTML
* HTML é a estrutura , e o CSS é a beleza 
* Não é linguagem de programação;
* É uma linguagem style sheet

## Vamos ao exemplo

Comentários começam com `/*` e terminam com `*/`

```css

/*Básico*/
/*-----------------------------------------------------*/

body {
    font: 1em/150% Helvetica,Arial, sans-serif;
    padding: 1em;
    margin: 0 auto;
    max-width: 33em;
}

@media (min-width: 70em) {
    /*let'sspecial case the global font size On large screen or window, we increase the font size for better redability*/
    body {
        font-size: 130%;
    }
}

 h1{
    font-size: 1.5em;   
 }

 /*Elementos espicificos /*
 /*-----------------------------------------------*/

 div p, #id:first-line {
    background-color: red;
    border-radius: 3px; 
 }

 div p {
    margin: 0;
    padding: 1em;
 }

 div p + p {
    padding-top: 0;
 }
 ```

 * Você poderá usar para desbilitar partes de seu código
 ```css

 /*.special {
    color: red;     
 }*/

 p  {
    color:blue;
 }
 ```