# Comentários

* Não irá afetar o seu código
* Ajuda a lembar blocos de códigos
* Deixa dicas para leitura
* Ajuda outros a entenderem
* Nuca esqueça de fechar um comentário aberto

Comentários começam com `/*` e terminam com `*/`.

```css

/* Básico */
/*-------------------------*/

body{
    font: 1em/150% Helvetica, Arial, sans-serif;
    padding: 1em;
    margin: 0 auto;
    max-width: 33em;
}

@media(min-width: 70em){
    /* Lets special case the global font size.On large screen or windown, we increase the font size for better readability */
    body{
    font-size: 130%;
    }
}

h1{font-size: 1.sem;}

/* Elementos especificos */
/* ---------------*/
div p, #id: first-line {
    background-color: red;
    border-radius: 3px
}

div p + p {
    padding-top: 0;
}

```

* Você poderá usar para desabilitar partes do seu código

```css

/* .special{
    color:red;
} */

p{
    color: blue;
}