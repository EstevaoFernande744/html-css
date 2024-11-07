links necesarios:
github.com/gustavoguanabara
gustavoguanabara.github.io

literaturas:
MDN - Mozilla Developer Network - https://developer.mozilla.org/pt-BR/docs/Web/Reference
W3C - World Wide Web Consortium - https://www.w3.org/standards/
WHATWG Living Standard - Web Hypertext Application Technology Working Group - https://html.spec.whatwg.org
W3Schools - Refsnes Data - https://www.w3schools.com

livros:
O'Reilly - Mark Pilgrim
O'Reilly - Eric Meyer
O'Reilly - Estelle Weyl
Alta Books - Elizabeth Castro e Bruce Hyslop
Alta Books - Jon Duckett
Alta Books - Elizabeth Robson e Eric Freeman
Novatec - Nate Cooper e Kim Gee
Novatec - Mauricio Samy Silva

Para descobrir o ip: https://www.iplocation.net/

HTML - Hypertext Markup Language
CSS - Cascading Style Sheets

HTML - Conteúdo (textos, imagens, vídeos e tabelas...)
CSS - Design (cores, sombras, tamanhos, posicionamentos...)

<h1>Titulo</h1> abertura de tag / conteúdo / fechamento de tag
<p>Parágrafo</p> abertura da tag do parágrafo / conteúdo do paragrafo / fechamento da tag do paragrafo
<img src="foto.png" alt="foto escolhida"> img é a abertura, mas não tem fechamento
src e alt são parâmetros / foto.png e foto escolhida são valores
Parâmetro: src é source que quer dizer origem. O alt é o nome da imgagem.
Valor: o foto.png é o local onde esta a imagem. Caso não tenha a imagem solicitada, vai mostar o texto alternativo que é foto escolhida.

h1 {
    font-family: Arial;
    font-size: 20pt;
    color: blue;
}

todos esses item após o seletor h1 são declarações.
seletor, tem por função selecionar o item que eu quero modificar.
declarações, tem por função modificar o conteudo escrito no html.

font-family: Arial; essa é uma formatação da css, é necessário sempre se utilizar ";" no final da declaração, é necessário também entender para que serve cada declaração.

no caso font-family é uma propriedade e Arial é um valor, então as declarações são compostas por prorpiedades e valores.

font-family: serve para mudar a fonte de Times New Roman (padrão) para outra font a sua escolha.
color: serve para modificar a cor de uma determinada estrutura, texto ou alguma outra coisa.
font-size: serve para modificar o tamnho da fonte.

Entendendo a estrutura de um codigo em HTML:

<!DOCTYPE html> 1° linha, essa linha de comando serve para dizer que vamos montar esse arquivo com a linguagem html.
<html lang="pt-br"> Essa é nossa html em si, o pt-br serve para nos dizer a linguagem do site. 
| 
| |<head>  Cabeça do site, seria a area de configurações.
| |
| | |<meta charset="UTF-8"> Isso me diz que o site vai ser compativel com caracteres em UTF-8 (acentos e etc)
| | |<meta name="viewport" content="width=device-width, initial-scale=1.0"> o navegador vai ocupar 100% da parte branca e não vai abrir com zoom.
| | |<title>Document</title> Titulo do nosso site.
| | 
| |</head>
| |
| |<body> Corpo do site, onde fica o conteudo propriamente dito.
| | 
| | |<h1>Olá, Mundo!</h1> Conteudo do site.
| |
| |</body>
|
</html> com sua tag de fechamento.

Font-end, Back-end e Full stack.

Front-end: Desenvolvedor que utiliza tecnologias como HTML, CSS e JS. Tecnologias que vão trabalhar ao lado do cliente.
Back-end: Desenvolvedor que utiliza tecnologias como PHP, JS, C#, Python.. para trabalhar ao lado do servidor.
Full stack: Desenvolvedor quem domina tanto o Front-end quanto Back-end.

<hr> linha horizontal.
<br> serve para quebraar linhas.
para fazer o <> aparecer precisamos colocar o &lt; e &gt;

<!--Comentario no html-->

[emojipedia.org](https://emojipedia.org/)
https://unsplash.com/pt-br/
https://www.pexels.com/pt-br/

Para gerar emois você precisar usar o codigo do emoji que geralmente vem nesse formato U+1F44D e substituir por &#xF44D;

fortamos de imagem:
jpeg - alto nivel de compactação; (jpg)
png - tem a capacidade de transparencia;

https://www.favicon.cc/ - para desenhar o icone
https://www.favicon.io/ - melhor site para o icone
https://www.iconarchive.com/

<h1></h1> - Primeiro titulo 
<h2></h2> - Subtitulo de h1
<h3></h3> - Subtitulo de h2 e ai por diante.

Existem dois tipos de formas de de deixar uma palavra ou frase em negrito ou itálico, com o <b></b>, <strong></strong> para negrito, <i></i>, <em></em> para itálico.

A diferença desses dessas formas é  semântica, onde os comando <b> e <i> não possuem significado, são apenas comando e o <strong> e <em> possuem semântica.

<mark></mark> - Essa tag tem por finalidade marcar o texto, marcando com amarelo sempre no HTML, já no caso do CSS conseguimos alterar a cor da marcação.

<del></del> - Serve para riscar o texto.

<ins></ins> - Serve para sublinhar e dizer que o texto em questão foi inserido.

<u></u> - Forma não semântica de sublinhar o texto.

<sup></sup> - Para colocar elevado.
<sub></sub> - Para colocar logaritmo e elementos quimicos por exemplo.

<code></code> - Fonte para codigos, fonte mono espaçada.
<pre></pre> - Serve para salvar a formatação.
<q></q> - Significa quote, ou sitação, para colocar as aspas.
<blockquote><blockquote> - Uma forma mais complexa de citar, onde tem um desvio lateral, com o texto destacado.
<abbr></abbr> - Serve para criar um pop-up com o significado da sigla.
<bdo></bdo> - tem a configuração <bdo dir="rtl right to left ou também ltr left to right"></bdo>, as letras começam da esquerda para direito ou da direita pra esquerda.

Para criar listas ordenadas temos o comando <ol></ol> - Para criar uma ordered list, ou seja lista ordenada, dentro disso temos os <li></li> - listed item, ou seja itens listados, podendo também escolher o tipo dessa lista, <ol type=""> os tipos são 1, A, a, I e i, com a opção também de <ol start=""> podendo ser iniciada com a numeração escolhida. 

Para criar listas não ordenadas temos o comando <ul></ul> - unordered list ou seja listas não ordenadas, semelhante as listas ordenadas usamos também o comando <li> também temos o comando type que pode ser <ul type="disc/circle/square">

Podemos colocar uma sublista dentro da lista com a configuração do tipo;

<ul>
    <li>exemplo 1</li>
    <ul type="circle"><!--disc, circle, square-->
        <li>subexemplo 1</li>
    </ul>
    <li>exemplo 2</li>
</ul>

<ol>
    <li>exemplo 1</li>
    <ol type="circle"><!--1, A, a, I, i-->
        <li>subexemplo 1</li>
    </ol>
    <li>exemplo 2</li>
</ol>

Existem também as Listas de Definições que são escritar pelo configuração:

<dl>
        <dt>HTML</dt> <!--Termo--> 
        <dd>Linguagem de marcação para a criação do conteúdo de um site.</dd> <!--Descrição-->
        <dt>CSS</dt>
        <dd>Linguagem de marcação para a criação do design de um site.</dd>
        <dt>JavaScript</dt>
        <dd>Linguagem de programação para a criação de interatividade de um site.</dd>
        
</dl>

onde o dt é para o termo onde vamos descrever, já o dd é a definição do termo.

Para criar um link utilizamos a tag <a></a> - envelopando o texto que queremos para ligar a um link, sendo que podemos implementar também o comando de <a href="URL" target="_blank" rel="external"> <!--_blank para abrir em outra aba-->, <!--rel para indicar ao navegador que é um link externo-->

Para criar um link interno, podemos usar desse codigo <a href="pag002.html" rel="next"> que diz a página na qual desejamos ir ao clickar nesse link, o rel diz que essa página que estou abrindo com o link pe a proxima página do meu site, já na proxima página com o comando <p><a href="index.html" rel="previous"> podemos gerar um link para voltar a pagina anterior e com o comando rel="previous ou prev" dizemos que a pagina anterior a essa atual é a pagina index.htmml. Sendo que esse comando rel é um comando de semântica.

<a href="www.telecab.com.br" target="_blank" rel="nofollow"> esse tipo de rel serve para dizer que você não da o aval para esse conteudo.

Outro comando do target="" que funciona é o _self para abrir na propria página.

Para voltar para a página anterioro no href precisamos colocar o comando href="../nome.do.arquivo".

Para baixar um item podemos usar o comando <li><a href="livro/meulivro.pdf" download="meulivro.pdf" type="application/pdf"> e para descobrir o mida type podemos acessar. (Em alguns navegadores como chrome o comando download não funciona.)

iana.org/assignments/media-types/ - site para types.

<picture></picture> - Espaço para utilizar imagens dinâmicas, quando usamos <source media="(max-width: 00px)" srcset="caminho/nome-da-foto" type="image/png"> <img src="caminho/nome-da-foto" alt="legenda"> - e ai quando rolarmos o navegador substitui a foto, então sempre colocando o source antes da img.

<audio src="caminho/nome-do-audio" autoplay controls loop> <!--MP3 WAV OGG são os formatos do áudio--> o autoplay sendo o comando para tocar automatico, controls para mostrar o controlador de play e loop faz com que o audio fique reiniciando assim que acabar.

<audio>
    <source src="midia/guanacast-33.mp3" type="audio/mpeg">
    <!--<source src="midia/guanacast-33.ogg" type="audio/ogg">
    <source src="midia/guanacast-33.wav" type="audio/wav">--> 
</audio>
Criamos o espaço <audio> colocamos os elementos <source> e depois colocamos o arquivo de áudio de acordo com o formato, segundo sempre a ordem, primeiro mp3, depois os outros dois, pois vai carregar de acordo com a sequencia.

podemos colocar no <audio preload="auto/metadata/none"> onde o preload é para carregar o site quando carregar o áudio, então se colocar auto, pode não carregar nada ou carregar só alguns itens ate abrir o audio, e o metadata é carregar esses alguns nomes e etc.

<video width="500" poster="imagens/limoes-capa.png" controls>
    <sorce src="midia/meu-video.mp4" type="video/mp4"> 
    <sorce src="midia/meu-video.m4v" type="video/m4v"> 
    <source src="midia/meu-video.webm" type="video/webm">
    <sorce src="midia/meu-video.ogv" type="video/ogg"> 
    <p>Seu navegador não tem compatibilidade com reprodução de vídeos.</p>
</video>

Para colocar vídeos temos o espaço <video> o item poster="" vem a ser uma imagem que você queira mostrar antes de começar o video.

Também tem a opção de colocar o vídeo do proprio site, como Youtube simplismente simplismente indo em compartilhar e incorporar.

Cores , color="Rgb(x, x, x)" valores de red, green and blue, também temos o #xxxxxx sistema decimal de cores ou hexadecimal, onde colocamos os 2 primeiros valores vermelho os dois valores posteriores de verde e os ultimos 2 de azul, temos o hsl ou sejá matiz, saturation e luminosity, matiz é o que define as cores, saturação é a intensidade ou pureza de uma cor e liminosidade é seu brilho.

https://color.adobe.com/pt/create/color-wheel

Site para gerar paleta de cores.

https://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF

Site para sugerir design de sites e etc.

https://coolors.co/

Site para sugerir paleta de cores de maneira mais simples.

Podemos fazer um gradiente na pagina com as CSS usando:

body{
    background-image: linear-gradient(45deg, #3198E2, #6D59C0, #B93590, #E33F5F, #FDD579); <!-- Para implementar as cores em forma de degrade -->
    background-attachment: fixed; <!-- Para fixar a imagem no fundo inteiro -->
}

sendo que o graadient pode variar de linear-gradient e radial-gradient, 

*{
    /* configurações globai das CSS */
}

Dentro das CSS podemos fazer o uso de:

background-color: white; <!-- Cria um caixa de fundo -->
border-radius: 15px; <!-- Deixa as bordas aredondadas -->
box-shadow: 5px 5px 15px  #02423c9f; <!-- Deixa sombra na caixa-->
width: 600px; <!-- Diz o tamanho da caixa -->
padding: 10px; <!-- Cria um espaçamento entre o final do texto e a caixa -->
margin: auto; <!-- Deixa a caixa sempre no meio da pagina -->

text-align: center; <!-- Alinha o texto no centro, serve principalmente para títulos -->
text-shadow: 1px 1px 2px #021c27a8; <!-- Cria sombra abaixo do texto com dimenções e cor -->
text-align: justify; <!-- Escolhe tipo de parágrafo -->
text-indent: 50px; <!-- Faz a identação do nosso parágrafo -->

https://www.w3schools.com/cssref/css_websafe_fonts.php

Site para ver o que chamamos de safe combinations font;

Quando usamos o comando font-family, é interessante também usar da seguinte forma;

font-family: Arial, Helvetica, sans-serif;

É uma combinação segura, pois caso o dispositivo não reconheça a fonte Arial, ele substituirá pela Helvetica ou por alguma fonte sans-serif ou sejá sem serifa.

quando vamos trabalhar com muitos titulos no arquivo CSS podemos padronizar todos os titulos usando a virgula;

h1,h2 {
    font-family: Times;
}

/*medidas absolutas 
cm, mm, in, px, pt, pc
    
medidas relativas
em, ex, rem, vw, vh, % */

são recomendadas usar medidas px e em;

a medida de px e em são interligadas, 16px é a medida padrão das telas e etc e 16px é o equivalente a 1em;

Das funções width, height e weight:

Width = refere-se a altura;
height = refere-se a largura;
weight = refere-se a peso;

ou seja o comando font-weight tem por função determinar o peso da fonte, ou o comprimento interno da fonte.

Existem pesos pre-definidos:

lighter
normal
bold
bolder

ou a variação númerica que vai de 100-900;

Nem todas as fontes possuiem essas configurações!

font-style: normal; ou font-style: italic; para deixar a fonte em italico.

text-decoration: underline; para sublinhar o texto.

Existe uma configuração que é padrão para o corpo do texto;

h1 {
    font-family: 'Work Sans', sans-serif;
    font-weight: bolder;
    font-size: 3em;
    font-style: italic;
}

Chamada shorthand font --> font-style -> font-weight -> font-size -> font-family

font: italic bolder 3em 'Work Sans', sans-serif;

podendo também fazer:

font: bolder 3em 'Work Sans'; podendo tirar o italic e etc.

Tipos de formatos para as fontes:
- opentype (otf)
- truetype (ttf)
- embedded-opentype
- truetype-aat (Apple Advanced Typography)
- svg


Sites para identificar fontes em imagens:

https://www.whatfontis.com/ - melhor
https://www.myfonts.com/

Class e e ID:

HTML       CSS
id         # seletor no css (só pode um elemento)
class      . seletor no css (pode vários elementos)

Diferença entre id e class

O id é utilizado para 1 elemento unico, class é utilizado para multiplos seletores;

Qualquer elemento com a class tipo, <h1 class="exemplo"> se pegarmos um <span class="exemplo"> os dois elementos vão ter as caracteristicas da class exemoplo.

Sendo que as configurações utilizadas são substituidas;

Existem os Pseudo classes, um exemplo disso é o 

:hover

quando colocamos um seletor com a pclass :hover, queremos que quando passar o mouse por cima do objeto do seletor, vai ter uma interação;

<p></p>

p:hover {
    color: yellow; 
}

Quando passar o mouse por cima o texto vai ficar amarelo;

Se criarmos um elemento <div> <p></p> </div>

div > p {
    display:none;
}

Se colocarmos esse simbolo, dizemos que esse pargrafo esta dentro da div, com o comando display none para não mostrar o paragrafo, faz com que ele não apareça;

Para mostrar esse texto podemos criar:

div:hover > p {
    display:block;
}

Para mostrar o texto quando passar o mouse;

Pseudo classes

:hover       fazendo quando passar o mouse
:visited     interação quando o site for visitado
:active      quando clicar fazer

Pseudo elemento

::after      depois da ação fazer outra ação
::before     antes da ação fazer outra coisa 

Para melhor descrever configurações nas CSS:

Em vez de trabalhar com:

border-top: ;
border-right: ;
border-bottom: ;
border-left: ;

Se os 4 valores forem iguais então você pode utilziar simplismente border: 10px; por exemplo.

Caso você queira um retangulo onde dois lados são iguais, voice pode colocar da seguinte forma:

border:10px 20px;

Vai ser equivalente a isso:

border-top: 10px;
border-right: 20px;
border-bottom: 10px;
border-left: 20px;

Caso queiramos colocar os 4 valores literalmente também podemos fazer o seguinte;

border: 10px 20px 30px 40px;

Seria equivalente a fazer isso:

border-top: 10px;
border-right: 20px;
border-bottom: 30px;
border-left: 40px;

Podemos reduzir as linhas de codigo também  com essa shorthand:

border: width style color;

Substituimos o width pelas dimensões, Style pelo estilo da borda e color pela cor da borda;

Podendo fazer isso para border, padding, outline, background e etc.

Podemos transformar o display da caixa usando o comando display: inline, block ou inline-block(onde podemos mudar as dimensões e etc ou sejá ele tem algumas caracteristicas de block);

Se acostumar a usar div semâticas como 

<header>    <!-- Para gerar titulo e icone da pagina/site -->
<nav>       <!-- Para colocar o menu/navegação -->
</nav>
</header>

<main>      <!-- Para estrututa principal do corpo -->
<section>   <!-- Para gerar a seção -->
<article>   <!-- Para gerar um artigo -->
<aside>     <!-- Para citar o autor -->
<aside>
</article>
</section>
</main>

<footer>    <!-- Para gerar a nota de rodapé -->
</footer>

essa estrutura pode ser variada;

Bordas personalizadas:

Conseguimos personalizar a borda utilizando os comandos:

border-image-source: url('borda.png'); /* Colocar uma imagem como borda */

border-image-slice: 27; /* Colocar o tamanho da imagem na borda */

border-image-repeat: repeat; /* Para repetir a imagem da borda */

#shorthand = border-image: url('borda.png') 27 repeat;

Site muito bom para configurar o seu projeto de site:

https://mockflow.com

Sites geradores de qr codes:

https://www.qr-code-generator.com/
https://qr.io/dashboard/







<!-- FLEX BOX -->

Existe um eixo principal nas flexbox chamado de main axis, cada eixo tem 2 pontos, o main axis tem o main-start e main-end que seria ponto de inicio e ponto final.

Também tem o chamado eixo transversal ou cross-axis, que seriam os cross-start e cross-end.

em um desenho simples temos:

main-start------------------------------>main-end

cross-start 
     |
     |
     |
     |
     \/
cross-end 


para nosso idioma.

isso para a <!-- flex-direction:row -->;

no caso do <!-- flex-direction: row-reverse -->;;

temos a mudança do main axis:

main-end<------------------------------main-start

em vez de ser da esquerda para a direita ele vai da direita para a esquerda;

para o <!-- Flex direction: column -->;

main-start
     |
     |
     |
     |
    \/
main-end


e 

cross-start------------------------------>cross-end

para o <!-- Flex direction: column-reverse -->;

main-end
    /\
    |
    |
    |
    |
main-start

cross-start------------------------------>cross-end



