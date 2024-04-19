# css-grid
Repositório para a demonstração das propriedades do CSS Grid.

# Pseudo Classes

- `:first-child` -> 1º Filho
- `:last-child` -> Último Filho
- `:nth-child(n)` -> Enésimo Filho

primeiro    -> 1º   -> first    -> 1st
segundo     -> 2º   -> second   -> 2nd
terceiro    -> 3º   -> third    -> 3rd
quarto      -> 4º   -> fourth   -> 4th
quinto      -> 5º   -> fifth    -> 5th

- estilizando o 2º elemento <p> descendente do elemento <div>:
~~~css
div p:nth-child(2){}
~~~
Ex:
~~~html
<body>
    <p>paragrafo</p>
    <div>
        <p>paragrafo</p>
        **<p>paragrafo</p>**
    </div>
</body>
~~~

- estilizando o 2 <p> que é filho da <div>

~~~css
div>p:nth-child(2){}
~~~
Ex:
~~~html
