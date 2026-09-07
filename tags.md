# Tags

São as marcações responsáveis pela criação da estrutura HTML. Elas atribuem significado para um conteúdo, ou seja, semântica.

Temos as tags aninhadas que são tags dentro de tags e que precisamos de atenção nas aberturas e fechamentos dessas tags.


## Comentário de código

A tag **\<!-- -->** é responsável por comentar um trecho ou linha de código. O conteúdo que estiver entre essas tags não serão renderizados pelo browser(navegador).


```html
<!-- texto comentado -->
```

## Criando títulos

A tag **\<h1>\</h1>** é responsável por criar títulos para o texto de um HTML. São seis níveis de tamanhos. Quanto maior a numeração do **\<h1>** menor é o tamanho do título.

```html
<h1>Título 1</h1>
<h2>Título 2</h2>
<h3>Título 3</h3>
<h4>Título 4</h4>
<h5>Título 5</h5>
<h6>Título 6</h6>
```

## Criando parágrafos

A tag **\<p>\</p>** é responsável pela criação de parágrafos no texto. Ao usar essa tag, uma quebra de linha é inserida.

```html
<p>Texto sobre.....</p>
```

## Adicionar quebra de linha

A tag que insere uma quebra de linha é a **\<br>**. Ela irá forçar o deslocamento do texto após a tag para a próxima linha abaixo.

```html
<p>A tag <br> deve ser escrita entre o texto ou final da linha para deslocar para a parte abaixo.</p>
```

A tag que insere uma quebra de linha e insere uma linha horizontal é a **\<hr>**. Ela irá forçar o deslocamento do texto após a tag para a próxima linha abaixo.

```html
<hr>
<p>Texto aqui...</p>
```

## Destacar textos

Algumas tags podem dar ênfase a uma palavra ou conjunto de palavras em um texto. São elas.

### Itálico

Transforma o texto em itálico.

```html
<i>Text here...</i>

<p>O texto com destaque é: <i>Text here...</i></p>
```

Transforma o texto em itálico semântico.

```html
<em>Text here...</em>

<p>O texto com destaque é: <em>Text here...</em></p>
```

### Negrito

Transforma o texto em negrito.

```html
<b>Text here...</b>

<p>O texto com destaque é: <b>Text here...</b></p>
```

Transforma o texto em negrito semântico.

```html
<strong>Text here...</strong>

<p>O texto com destaque é: <strong>Text here...</strong></p>
```

### Destaque especial

Representa um trecho de destaque especial no texto em seu contexto.

```html
<mark>Text here...</mark>

<p>O texto com destaque é: <mark>Text here...</mark></p>
```

## Links

A tag **\<a>\</a>** cria links para outras páginas HTML. Ela aceita atributos que definem o comportamento do link ao ser acionado.

Se existir um elemento com mesmo id do atributo **href** do link na mesma página, o link acessará este elemento.

```html
<a href="https://www/...com.br" title="anything" target="_blank">Conteúdo</a>
<a href="home.html" title="anything">Conteúdo</a>
<a href="#secao" title="anything">Conteúdo</a>
<a href="mailto: user@me.in" title="anything">Conteúdo</a>
```

### Arquivo externo CSS

Define o link para um arquivo externo de CSS, JavaScript, etc. Ele fica definido na parte **\<head>\</head>** do documento HTML.

```html
<link rel="stylesheet" href="style.css">
```

### Arquivo externo Javascript

Define a fonte de uma arquivo JavaScript que será carregado no HTML.

```html
<script src="js/myscript.js"></script>
```

## Listas

Temos alguns tipos de listas no HTML. Dentro da tag **\<li>** podemos colocar outras tags, mas nem todas fazem sentido e devemos ter cuidados.

### Lista ordenadas

O código a seguir cria uma lista ordenada de itens.

```html
<ol>
  <li>item 1</li>
  <li>item 2</li>
  <li>item 3</li>
</ol>
```

### Lista não ordenada

O código a seguir cria uma lista não ordenada de itens.

```html
<ul>
  <li>item 1</li>
  <li>item 2</li>
  <li>item 3</li>
</ul>
```

### Lista aninhada

São as listas dentro de outra lista.

```html
<ul>
  <li>item 1</li>
  <li>item 2
    <ul>
      <li>item 2.1</li>
      <li>item 2.2</li>
      <li>item 3.2</li>
    </ul>
  </li>
  <li>item 3</li>
</ul>
```

### Lista de definição

São listas utilizadas quando precisamos definir um termo ou algo.

```html
<dl>
  <dt>Termo</dt>
    <dd>Detalhe do termo</dd>
</dl>
```

```html
<dl>
  <dt>Termo</dt>
    <dd>Detalhe do termo</dd>
    <dt>Termo</dt>
      <dd>Detalhe do termo</dd>
</dl>
```

```html
<dl>
  <dt>Termo</dt>
  <dt>Termo</dt>
  <dt>Termo</dt>
    <dd>Detalhe do termo</dd>
</dl>
```
