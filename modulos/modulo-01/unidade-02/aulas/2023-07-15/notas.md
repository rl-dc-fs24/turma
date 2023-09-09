# Resumo - CSS (Cascading Style Sheets)

## 1. O que é CSS?

CSS (Cascading Style Sheets) é uma linguagem de estilo utilizada para definir a aparência e o layout de documentos HTML. Com o CSS, você pode controlar cores, fontes, espaçamento, posicionamento e outros atributos visuais de elementos HTML. A separação entre o conteúdo (HTML) e a apresentação (CSS) permite criar páginas web mais flexíveis e fáceis de manter.

## 2. Como aplicar CSS?

Existem três formas principais de aplicar CSS em um documento HTML:

### - CSS Inline:
Você pode aplicar estilos diretamente a um elemento usando o atributo `style`. Esses estilos são definidos no próprio elemento HTML.

Exemplo de CSS inline:

```html
<p style="color: blue; font-size: 16px;">Este é um parágrafo com estilo inline.</p>
```

### - CSS Interno (em linha):
Você pode inserir estilos CSS dentro da tag `<style>` no cabeçalho do documento HTML. Os estilos serão aplicados a todos os elementos do documento.

Exemplo de CSS interno:

```html
<!DOCTYPE html>
<html>
<head>
  <title>Exemplo de CSS Interno</title>
  <style>
    p {
      color: blue;
      font-size: 16px;
    }
  </style>
</head>
<body>
  <p>Este é um parágrafo com estilo interno.</p>
</body>
</html>
```

### - CSS Externo (em arquivo separado):
Recomenda-se o uso de arquivos CSS externos para melhor organização e reutilização de estilos. Para isso, você cria um arquivo .css separado contendo os estilos e, em seguida, vincula esse arquivo ao documento HTML usando a tag `<link>` no cabeçalho.

Exemplo de CSS externo:

styles.css:
```css
p {
  color: blue;
  font-size: 16px;
}
```

index.html:
```html
<!DOCTYPE html>
<html>
<head>
  <title>Exemplo de CSS Externo</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <p>Este é um parágrafo com estilo externo.</p>
</body>
</html>
```

## 3. Seletor CSS

Os seletores são usados para selecionar os elementos HTML aos quais você deseja aplicar estilos. Existem diferentes tipos de seletores, como seletores de elementos, seletores de classes e seletores de ID.

### Exemplos de seletores CSS:

- Seletor de Elemento:

```css
p {
  /* Estilos aplicados a todos os elementos <p> */
}
```

- Seletor de Classe:

```css
.button {
  /* Estilos aplicados a elementos com a classe "button" */
}
```

- Seletor de ID:

```css
#header {
  /* Estilos aplicados a um elemento com o ID "header" */
}
```

## 4. Box Model

O Box Model é um conceito fundamental no CSS que define como cada elemento HTML é renderizado como um retângulo, composto por conteúdo, preenchimento (padding), borda (border) e margem (margin).

![Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Box_model/css-box-model-standard-small.png)

O tamanho total de um elemento é calculado somando o conteúdo, o preenchimento, a borda e a margem.

Exemplo de uso do Box Model:

```css
div {
  width: 200px; /* Define a largura do elemento */
  padding: 20px; /* Define o preenchimento do elemento */
  border: 1px solid black; /* Define a borda do elemento */
  margin: 10px; /* Define a margem do elemento */
}
```

## 5. Propriedades Comuns do CSS

Algumas propriedades CSS comuns para estilizar elementos:

- `color`: Define a cor do texto.
- `font-size`: Define o tamanho da fonte.
- `font-family`: Define a família da fonte (Arial, Times New Roman, etc.).
- `background-color`: Define a cor de fundo.
- `padding`: Define o preenchimento interno do elemento.
- `margin`: Define a margem externa do elemento.
- `border`: Define a borda do elemento.

## 6. Comentários

Você pode adicionar comentários em um arquivo CSS para explicar ou fazer anotações no código. Comentários são ignorados pelo navegador e não afetam os estilos.

Exemplo de comentário CSS:

```css
/* Este é um comentário CSS */
```