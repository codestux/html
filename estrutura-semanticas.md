# Tags de estrutura semânticas

Tags semânticas permitem que seja dado um significado para cada parte da estrutura da página HTML. Uma página HTML pode ter as seguintes tags que definem sua estrutura.

Estas tags, também, informam a agente de usuário o significado de cada parte da página HTML.

## Definição de processamento do navegador para códigos HTML5

No topo da página HTML devemos adicionar a linha: **\<!doctype html>**. Assim, a informação que o navegador recebe é de utilizar a última versão do HTML.

## Definindo o conteúdo HTML para o navegador

A tag **\<html>\</html>** define para o navegador que tudo que estiver no seu interior será renderizado como HTML padrão.

Podemos inserir o atributo **lang="pt-br"** para que o navegador defina qual a língua será usada para exibir o conteúdo da página.

```html
<html lang="pt-br">

<html lang="en">
```

## Passando informações para o navegador

A tag **\<head></head>** define as configurações que podemos enviar para o navagador ao carregar a página.

### meta

A tag **\<meta>** permite informar ao navegador como ele deve ser comportar durante a renderização da página.

1. **<meta charset="UTF-8">**: Permite informar ao navegador que a renderização será realizada
pelo UTF-8

2. **<meta name="viewport" content="width=device-width, initial-scale=1.0">**: Define as configurações de como será a exibição do navegador na tela do dispositivo.

3. **<meta name="description" content="Página do meu serviço">**: Define as informações da página sobre algum contexto.

4. **<meta name="author" content="Tux elixir">**: Define o desenvolvedor da página.

5. **<meta name="keywords" content="test, tux, device, services, hardwares">**: Define palavras-chaves para os mecanismos de busca. Não muito utilizada no momento.

### title

Define um título que será exibido no navegador.

```html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Título da página</title>
</head>
```

### body

A tag **\<body>** é onde ficam os códigos que serão exibidos no navegador para o usuário.

```html
<body>
  <h1>Texto</h1>
  <p>Aqui onde ficam os textos</p>
</body>
```

### Estrutura básica de uma página

```html
<!DOCTYPE html>

<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Título da página</title>
</head>

<body>

</body>

</html>
```

### Tag header

Define o cabeçalho principal de uma página HTML. Pode ser usado em outras tags como a **\<section>** ou **\<article>**.

### Tag nav

Navegação principal da página. Nem todo link deve ficar dentro desta tag.

### Tag main

Conteúdo principal da página. Tudo que não se encaixar no cabeçalho, links e rodapé.

### Tag footer

É o rodape da página. Pode ser usado nas tags **\<section>** ou **\<article>**.

### Tag section

Agrupa um conjunto de informações que estejam relacionadas.

### Tag article

Para conteúdos importantes da página.

### Tag aside

Conteúdo secundário da página. Não está relacionado ao assunto da página.

## Tags não semânticas

### Tag div

Cria um elemento de bloco que permite organizar outros elementos na página. É uma espécie de container.

### Tag span

Cria um elemento de linha que permite organizar o designer ou formatação de elementos na página.
