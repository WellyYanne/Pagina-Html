# Tags mais utilizadas em HTML
- [Estrutura Básica do HTML: Tags HTML, Head e Body](#estrutura)
- [Exemplo de atributos das Tags](#exemplo_atributo)
- [Exemplo HTML de texto das Tags](#exemplo_texto)
- [Exemplo Listas em HTML](#exemplo_lista)

- # Estrutura Básica do HTML: Tags HTML, Head e Body

![estrutura do html](https://pensandonaweb.com.br/content/images/2014/Aug/html-hierarchy.png)


A estrutura básica do HTML começa com a tag `<html>`, que envolve todo o conteúdo da página. Dentro dela, temos a `<head>`, onde são incluídos elementos como o título da página, metadados (como a codificação de caracteres e a definição da *viewport*), e links para outros recursos como folhas de estilo CSS e scripts JavaScript. No `<body>`, local onde são feitas as alterações visíveis para o usuário, podemos utilizar uma variedade de tags para estruturar o conteúdo da página. Por exemplo, a tag `<div>` é usada para agrupar e estruturar blocos de conteúdo, enquanto as tags de cabeçalho `<h1>` a `<h6>` são usadas para títulos e sub-títulos de diferentes níveis de importância. As tags `<p>` são usadas para parágrafos de texto, `<img>` para imagens, `<a>` para links, `<ul>` e `<ol>` para listas não-ordenadas e ordenadas, respectivamente, e `<form>` para formulários interativos. Cada uma dessas tags desempenha um papel crucial na criação de uma página web estruturada e acessível.

# Exemplo de atributos das Tags

Um atributo em HTML é uma parte de uma tag que fornece informações adicionais sobre como um elemento deve ser exibido ou comportar-se na página da web. Cada atributo consiste em um nome e um valor, separados por um sinal de igual (=), e são usados para personalizar ou configurar elementos específicos em uma página. Segue alguns exemplos.

- O atributo **href** é essencial na tag **a**, permitindo definir o destino de um link. Ele pode ser usado para direcionar os usuários para outras páginas da web, seções dentro da mesma página (âncoras), ou até mesmo para downloads de arquivos.

  ```html
  <a href="https://www.exemplo.com">Exemplo!</a>

- O atributo **type** é essencial para definir o comportamento e o tipo de entrada de elementos em HTML, como campos de formulário, botões e links. Escolher o tipo correto de type é crucial para garantir a funcionalidade correta e a usabilidade dos elementos em uma página web.

  ```html
  <input type="text" id="nome" name="nome">
  

- O atributo **alt** é usado em elementos `<img>` e `<area>`. Ele fornece um texto alternativo que é exibido quando a imagem não pode ser carregada ou quando o usuário utiliza um leitor de tela para acessar o conteúdo da página. O texto alternativo também é importante para a acessibilidade, ajudando usuários com deficiência visual a entender o conteúdo das imagens. Além disso, motores de busca utilizam o texto alternativo para indexar e entender o conteúdo das imagens.

```markdown
<img src="imagem.jpg" alt="Descrição da imagem">
