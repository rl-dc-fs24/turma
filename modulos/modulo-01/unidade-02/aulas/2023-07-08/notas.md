# Notas - 2023-07-08

## 1. HTML (HyperText Markup Language)

HTML é a linguagem de marcação padrão utilizada para criar páginas web. Ele permite definir a estrutura e o conteúdo da página, bem como incorporar elementos multimídia, links, formulários e muito mais.

## 2. Estrutura Básica de um Documento HTML

Um documento HTML deve começar com a declaração do tipo de documento (doctype) seguido pela tag `<html>`, que contém todas as informações da página. O documento é organizado em duas principais seções: `<head>` e `<body>`.

```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Metadados, links para estilos CSS, scripts, etc. -->
    <title>Título da Página</title>
  </head>
  <body>
    <!-- Conteúdo visível da página -->
    <h1>Título Principal</h1>
    <p>Este é um parágrafo de exemplo.</p>
  </body>
</html>
```

## 3. Tags HTML

As tags HTML são elementos que definem a estrutura e o conteúdo da página. Elas são representadas por marcadores `<tag>` e podem conter atributos para ajustar o comportamento e a aparência dos elementos.

Exemplos de tags HTML:

- `<h1>`, `<h2>`, `<h3>`, ... `<h6>`: Títulos e subtítulos.
- `<p>`: Parágrafos de texto.
- `<a href="URL">`: Links para outras páginas ou recursos.
- `<img src="caminho/para/imagem.jpg" alt="Texto alternativo">`: Imagens com um texto alternativo.
- `<ul>`: Lista não ordenada.
- `<ol>`: Lista ordenada.
- `<li>`: Item da lista.
- `<table>`, `<tr>`, `<td>`: Tabelas.

## 4. Comentários

Você pode adicionar comentários em um documento HTML para explicar ou fazer anotações no código. Comentários são ignorados pelo navegador e não são exibidos na página.

```html
<!-- Este é um comentário HTML -->
```

## 5. Elementos Vazios

Alguns elementos HTML não possuem conteúdo e são chamados de elementos vazios. Eles não têm tag de fechamento e, em vez disso, são fechados com uma barra inclinada antes do sinal de maior que `/>`.

Exemplo de elemento vazio:

```html
<img src="logo.png" alt="Logo" />
```

## 6. Atributos Globais

A maioria das tags HTML pode ter atributos. Alguns atributos são globais e podem ser aplicados em várias tags.

Exemplo de atributo global:

```html
<div class="container">
  <!-- Conteúdo do div -->
</div>
```

## Listas

Listas em HTML são usadas para organizar informações em forma de itens. Existem dois tipos principais de listas: listas não ordenadas (`<ul>`) e listas ordenadas (`<ol>`).

### Listas Não Ordenadas (`<ul>`)

As listas não ordenadas são utilizadas quando a ordem dos itens não é importante. Cada item da lista é representado pela tag `<li>` (item de lista).

Exemplo de uma lista não ordenada:

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

### Listas Ordenadas (`<ol>`)

As listas ordenadas são utilizadas quando a ordem dos itens é importante. Assim como nas listas não ordenadas, cada item da lista é representado pela tag `<li>`.

Exemplo de uma lista ordenada:

```html
<ol>
  <li>Primeiro Item</li>
  <li>Segundo Item</li>
  <li>Terceiro Item</li>
</ol>
```

## 2. Tabelas

Tabelas em HTML são utilizadas para exibir dados em formato de linhas e colunas. Elas são compostas por três elementos principais: `<table>` (tabela), `<tr>` (linha) e `<td>` (célula de dados).

### Exemplo de Tabela Simples:

```html
<table>
  <tr>
    <td>Nome</td>
    <td>Idade</td>
    <td>Email</td>
  </tr>
  <tr>
    <td>João</td>
    <td>30</td>
    <td>joao@example.com</td>
  </tr>
  <tr>
    <td>Maria</td>
    <td>28</td>
    <td>maria@example.com</td>
  </tr>
</table>
```

### Cabeçalho de Tabela (`<th>`)

A tag `<th>` é usada para definir células de cabeçalho em uma tabela. Ela é similar à tag `<td>`, mas indica que o conteúdo é um cabeçalho para uma ou mais colunas ou linhas da tabela.

Exemplo de utilização de cabeçalhos de tabela:

```html
<table>
  <tr>
    <th>Nome</th>
    <th>Idade</th>
    <th>Email</th>
  </tr>
  <tr>
    <td>João</td>
    <td>30</td>
    <td>joao@example.com</td>
  </tr>
  <tr>
    <td>Maria</td>
    <td>28</td>
    <td>maria@example.com</td>
  </tr>
</table>
```

Ao utilizar a tag `<th>`, os navegadores geralmente aplicam estilos diferentes para destacar os cabeçalhos das demais células da tabela, tornando-os mais visíveis e legíveis.

## Onde posso saber mais?

- [https://developer.mozilla.org/pt-BR/docs/Web/HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [https://www.w3schools.com/html/](https://www.w3schools.com/html/)
- [https://www.youtube.com/watch?v=E6CdIawPTh0](https://www.youtube.com/watch?v=E6CdIawPTh0)
- [https://www.freecodecamp.org/portuguese/news/manual-de-html-aprendizagem-de-html-para-iniciantes/](https://www.freecodecamp.org/portuguese/news/manual-de-html-aprendizagem-de-html-para-iniciantes/)