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

h1{
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
