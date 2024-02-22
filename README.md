# Criando uma página estática em HTML

#### Páginas da internet

-   A internet é uma rede de computadores (vários computadores ligados entre si), alguns computadores armazenam (Servidor) as informações outros só consomem essas informações (client).

-   As páginas que acessamos são armazenadas pelos servidores e enviadas para seu computator (client).

-   Essas páginas são como um grande texto e para ler ele e montar a página da forma que vemos precisamos de um programa específico, os navegadores de internet.

-   Esses Textos são construídos utilizando `Tags`

#### Tags HTML

-   As tags html tem a seguinte estrutura.

`<NOME ATRIBUTOS="VALOR"> CONTEÚDO </NOME>`

-   Cada tag tem um `NOME` e uma função.
-   Cada tag também possui `ATRIBUTOS` para mudar seu comportamento ou para referencia-la.
-   A maioria das tags pode receber conteúdos, como: texto e outras tags
-   As tags funcionam de forma similhar aos parênteses. Sempre que abrimos `<NOME>` é preciso fechar `</NOME`.

-   Exemplos:

```html
<h1>Esse é um titulo</h1>
```

-   `h1` é o nome da tag.
-   `Esse é um titulo` é o conteúdo da tag.

#### Estrutura base de uma página HTML

-   Para o computador entender e montar a tela para o usuário é preciso que a página tenha a seguinte estrutura.

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Título da página</title>
    </head>
    <body>
        <!-- Aqui vai o conteúdo da página -->
    </body>
</html>
```

-   Tag `<!DOCTYPE html>` indica o inicio de um documento html

-   Tag `<html lang="en">` indica o inicio da página

-   Dentro da tag `<head>` vai as informações necessárias para configurações da página.

-   Tag `<meta>` é usada para inseir informações de configuração da página (tipo de escrita, tamanho da tela e etc)

-   Tag `<title>` tem a função de definir o titulo da página (fica na barra superio do navegador)

-   Tag `<body>` tem a função de indicar o começo do contéudo da página

#### Principais tags e suas funções

```html
<h1>Título</h1>
<h2>sub-título</h2>
<h3>sub-sub-título</h3>
<h4>sub-sub-...-título</h4>
<h5>sub-sub-...-título</h5>
<h6>sub-sub-...-título</h6>

<p>Parágrafo</p>
<img src="URL" />
<table border="solid"></table>
<thead></thead>
<tr></tr>
<th></th>
<tbody></tbody>
<td></td>
```

-   `<h1>` até o `<h6>` são utilizados para titulos, títulos de seção e subtitulos. O número indica a sua importancia, 1 mais importante e 6 menos importante.

-   `<p>` é usado para parágrafos de texto.

-   `<img>` serve para inserir imagens na página, a origem (onde se encontra a imagem) deve ser colocado no valor do atributo `src`. Exemplo: `src="foto.png"`.

-   `<table>` indica o inicio de uma tabela em html, possui um atributo chamado `border` que define o estilo das linhas de borda da tabela. Exemplo: `border="solid"`.

-   `<thead>` define o inicio do cabeçalho da tabela

-   `<tr>` define o início de uma linha

-   `<th>` define uma coluna do cabeçalho

-   `<tbody>` define o inicio do conteúdo da tabela

-   `<td>` define uma coluna do conteúdo da tabela

-   Exemplo de uso de `<h1>`, `<p>` e `<img>`. [clique aqui](texto.html)

-   Exemplo de uso de `<table>`, `<thead>`, `<tbody>`, `<th>`, `<tr>` e `<td>` [clique aqui](tabela.html)
