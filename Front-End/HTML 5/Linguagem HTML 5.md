HTML5 é uma linguagem de marcação usada para estruturar e apresentar documentos de hipertexto na World Wide Web. Foi a quinta e última versão HTML principal que agora é uma recomendação aposentada do World Wide Web Consortium. A especificação atual é conhecida como HTML Living Standard.

O HTML5 é a nova versão padrão do HTML com novas Tags e APIs capazes de inserir facilmente um arquivo de áudio ou vídeo em um site. Basicamente o HTML seria o esqueleto do seu site, que deverá ser formatado (ou vestido) utilizando a linguagem CSS (Cascading Style Sheet).


# Criando um site em HTML 5

```
<!DOCTYPE html>
```
###### O DOCTYPE define qual tipo de arquivo você está escrevendo, ela é responsável por informar ao navegador qual é este tipo. É o primeiro código a ser adicionado em uma página. Comando usado para informar os navegadores que o arquivo Web esta em HTML


```
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nome da página Web</title>
</head>
<body>

</body>
</html>
```
# `<htlm>`

A tag html define o início da sua página, nela podemos adicionar o `lang="pt-br"`definindo a linguagem (português, inglês, espanhol, etc) da página. Este atributo ajuda aos leitores de tela a ler corretamente os textos contidos na página, além dos buscadores poderem identificar o idioma e para que o navegador possa utilizar o dicionário gramatical mais correto.
A tag `lang="pt-br"` informa o navegador qual idioma o documento esta escrito.

## [[Conteúdo do HEAD]]

No `<head>` ficarão informações conhecidas como _metadados_, que normalmente são globais, não aparecem na página, mas podem efetuar modificações na mesma, também chamado de área comportamental do código, ou seja, como será configurado o código.

## [[Conteúdo do BODY]]

Por fim, no `<body>` ficarão as tags e informações que serão mostradas ao seu usuário, interpretada pelo navegador, também chamado de área visual do código, tudo que deve aparecer tem que estar no `<body>`.

## Tags HTML e seus Significados

- **DOCTYPE:** define o tipo de documento
- **html:** define o início do documento html, todos as demais tags devem estar dentro desta tag
- **head:** cabeçalho onde ficar os metadados do documento, como metatgs, css e javascript
- **title:** define o título do documento, mostrado na barra de títulos do navegador e como link nos mecanismos de busca
- **base:** define a url base do documento
- **link:** utilizado para linkar um arquivo de imagem ou css a página html
- **script:** utilizado para escrever ou anexar um arquivo normalmente javascript a página
- **meta:** metatags, como charset, description, viewport ou keywords
- **style:** utilizada para adicionar um código css a página
- **body:** corpo ou área principal do documento, dentro deste deve ficar o conteúdo da sua página
- **header:** define um cabeçalho da página ou de uma seção, normalmente pode conter um menu (nav), um logo ou link
- **nav:** define uma área de navegação contendo links, para a formação de menus com hiperlinks
- **footer:** define o rodapé de uma página ou seção
- **main:** define o conteúdo principal da página, deve ser utilizado apenas uma única vez em cada página
- **section:** define uma seção do documento
- **article:** pode ser um post ou notícia de um fórum ou blog, define um conteúdo independente
- **h1 a h6:** representam 6 níveis de títulos, sendo o h1 de maior importância
- **p:** define um parágrafo
- **br:** define uma quebra de linha
- **div:** define uma camada sem formatação, genérico
- **ul:** define uma lista não ordenada
- **li:** define um elemento ou item da lista não ordenada
- **a:** define um link que deve ser apontado com o atributo _href_
- **img:** define a utilização de uma imagem (JPG, GIF, PNG e outras). A imagem deve ser apontada com o uso do atributo _src_
- **strong:** apesar de deixar em negrito, representa a importância deste texto no meio da frase


