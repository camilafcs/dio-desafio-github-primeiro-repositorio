# Introdução a criação de websites com HTML5

## ESTRUTURA BÁSICA

 - ELEMENTO
 
Para entender como escrever HTML é necessário entender como funciona um elemento. 
O elemento é a base do HTML. Tudo dentro de um arquivo HTML é um elemento. 
Um elemento HTML começa com uma tag de abertura. Em seguida, você diz qual é o tipo de elemento, o que ele fará na tela. 
A tag pode ter um atributo, que pode ser adicionar uma funcionalidade, mudar a aparência ou dizer alguma coisa ao navegador. 
Dentro da tag temos o conteúdo do elemento. Por fim, temos a tag de fechamento.

A estrutura básica de um documento HTML é bem pequena:

-!DOCTYPE html-
-html lang="pt-br"-
  -head-
    -title-Título da página-/title-
    -meta charset="utf-8"-
  -/head-
  -body-
    Aqui vai o código HTML que fará seu site aparecer.
  -/body-
-/html-

## SEMÂNTICA

A semântica nos permite descrever mais precisamente o nosso conteúdo. Dá significado ao código.

Alguns elementos importantes são:

 - section = representa uma seção genérica de conteúdo, como lista de artigos;

 - header = pode ser o cabeçalho da página ou de parte da página;

 - article = representa um conteúdo independente e relevante dentro da página. Um <article> pode conter outros elementos, como header, cabeçalhos, parágrafos e imagens;

 - aside = representa um conteúdo relacionado com o conteúdo principal da página. Normalmente, é representado por uma barra lateral;

 - footer = rodapé da página ou de parte da página;

 - h1-h6 = representam a importância de um título dentro de uma página.  ATENÇÃO! A única regra é que só pode haver um h1 por página!

## TEXTOS E LINKS EM HTML

Os elementos h1 até h6, falados anteriormente, são essenciais para indicar, visualmente, a importância e a localização de seções de texto na página. 
Contudo, para textos maiores e mais densos, deve ser utilizado o elemento p.

O elemento p representa um parágrafo, mas ele não suporta apenas textos: podemos adicionar imagens, códigos, vídeos e vários outros tipos de conteúdo nele.

Outro elemento muito interessante e extremamente necessário na web é o a, que significa âncora. 
Ele representa um hyperlink, é ele que interliga vários conteúdos e páginas na web. 

##IMAGENS NO SITE

A web também é feita de imagens, e para representa-las temos o elemento img. 
Esse é um elemento que não possui tag de fechamento, é bem simples, tem apenas dois atributos próprios: o “src” e o “alt”.
O “src” é um atributo obrigatório e ele guarda o caminho da imagem. 
O “alt” não é obrigatório, mas é altamente recomendado para melhorar a sensibilidade. Ele mostra a descrição da foto quando ela não é carregada.

## LISTAS EM HTML

As listas servem para agrupar uma coleção de itens. Os elementos relacionados a lista são “ul”, “ol” e “li”:

 - “ul”: representa uma lista em que a ordem dos itens não é importante;
 - “ol”: a ordem dos itens é importante e, por isso, são representados com números, letras ou algarismos romanos;
 - “li”: é um item dessa lista.
 
 
