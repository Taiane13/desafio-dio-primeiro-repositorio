# HTML e CSS
---
## HTML5

>Com o HTML definimos o significado e a estrutura do conteúdo da web.
- ## Estrutura Básica
~~~
<DOCTYPE html>
<html>
     <head>
     </head>
     <body>
     </body>
</html>
~~~
>Através do código _**lang**_ informamos ao navevegador o idioma do site.
- ## Elementos:
  - **head**: contém meta dados e conteúdos a serem lidos pelo navegador, o JS com a tag *script* o CSS com a tag <ins>*style*</ins> e <ins>*link*</ins> e o título com a tag <ins>*title*</ins>.
  - **body**: colocamos todo conteúdo visível: *textos, vídeos, imagens*.
- ## Semântica
  *< section >* Seção genérica de conteúdo
  
  *< header >* "Cabeçalho" contém logotipos, menus, campos de busca

  *< article >* Conteúdo relevante, artigo, blog

  *< aside >* Conteúdo relacionado, nome do autor, links
  
  *< footer >* Rodapé da página ou de parte dela

  *< h1 >* à *< h6 >* Títulos

  *< p >* Conteúdo do artigo

  *< a >* Link
- ### Adicionando links
  ~~~
  <a href="link" target="_blank">Frase em que o link estará contido</a>
  ~~~
>Ao ultilizar o target o link será aberto em outra aba.
+ Também é possível adicionar imagens ao site com html usando a tag
  ~~~
  <img scr="img.jpg" alt="Texto alternativo para descrever a imagem"> 
  ~~~
- ## Listas
  *< ul >* lista onde a ordem dos itens não importa

  *< ol >* lista enumerada

  *< li >* itens da lista
>### Id e Classes
~~~
-> A tag ID deve ser usada apenas uma vez.

    <header id="header"></header>

-> Atribuimos uma classe a uma tag para identificá-la.

    <header class="nome da classe"></header>
~~~
---
## CSS5
> ### Estiliza o código
  - Adicionar no *head* do **HTML**
  ~~~
  <link rel="stylesheet" href="style.css">
  ~~~
### Para dar estilo a um código:
- Adicionamos um ou mais seletores e atribuimos a eles características.
  ~~~
  a, p, h1, h3{
      color: blue;
      font-size: 14px;
  }
  ~~~
- **Em CSS usamos . para representar o *ID* e **#** para a *classe*.**

- ### Estilizando Elemento
  - *padding* : Espaço entre borda e conteúdo.
  - *margin* : Margens.
  - *border* : Bordas.
  - *content* : Conteúdo.
>Podemos mudar, cor, tipo, largura e altura de todas as tags acima. Com a tag **border-radius: 50%** transformos as linhas em círculo.
- ### Estilizando Texto
  - *font-family:* Altera a fonte.
     - **ex:** Verdana;
  - *font-size:* Tamanho do texto.
    - **ex:** 18px;
  - *font-style:* Altera estilo. 
    - **ex:** *italic*;
  - *font-weigt:* Peso da fonte.
     - **ex:** negrito;
  - *text-transform:* Modifica o texto.
     - **ex:** capitalize;
  - *text-decoration:* Decora texto.
     - **ex:** underline;
- ### Estilizando Listas
>Podemos modificar o formato, tipo de número ou figura.
~~~
ul {
    list-style-type: square;
}
ol {
    list-style-type: upper-roman;
}
ul {
    list-style-type: url("rocket.png");
}
~~~
- ### Dimensão e Alinhamento
  - *width*: largura.
  - *height*: altura.
  - *max-width*: largura máxima.
  - *max-height*: altura máxima.
  - *text-align*: alinha texto.
    - **ex:** *left, right, center, justfy;*