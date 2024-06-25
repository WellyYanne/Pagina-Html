
# Tags mais utilizadas em HTML



## 📚 Indice 
 - Estrutura Básica do HTML
 - Exemplo de atributos das Tags
 - Exemplo HTML de texto das Tags
 - Exemplo Listas em HTML






## 💻Estrutura Básica do HTML

![estrutura do html](https://pensandonaweb.com.br/content/images/2014/Aug/html-hierarchy.png)

A estrutura básica do HTML começa com a tag `html`, que envolve todo o conteúdo da página. Dentro dela, temos a `head`, onde são incluídos elementos como o título da página, metadados (como a codificação de caracteres e a definição da*viewport*), e links para outros recursos como folhas de estilo `*CSS*` e scripts `*JavaScript*`. No `body`, local onde são feitas as alterações visíveis para o usuário, podemos utilizar uma variedade de tags para estruturar o conteúdo da página. Por exemplo, a tag `div` é usada para agrupar e estruturar blocos de conteúdo, enquanto as tags de cabeçalho `h1`a `h6` são usadas para títulos e sub-títulos de diferentes níveis de importância. As tags `p` são usadas para parágrafos de texto,`img` para imagens, a para links,`ul` e `ol` para listas não-ordenadas e ordenadas, respectivamente, e `form` para formulários interativos. Cada uma dessas tags desempenha um papel crucial na criação de uma página web estruturada e acessível.


## 🧑‍💻 Exemplo de atributos das Tags

Um atributo em HTML é uma parte de uma tag que fornece informações adicionais sobre como um elemento deve ser exibido ou comportar-se na página da web. Cada atributo consiste em um nome e um valor, separados por um sinal de igual (=), e são usados para personalizar ou configurar elementos específicos em uma página. Segue alguns exemplos.

- O atributo `href` é essencial na taga, permitindo definir o destino de um link. Ele pode ser usado para direcionar os usuários para outras páginas da web, seções dentro da mesma página (âncoras), ou até mesmo para downloads de arquivos.

```bash
  <a href="https://www.exemplo.com" Exemplo!</a>
```

- O atributo `type` é essencial para definir o comportamento e o tipo de entrada de elementos em HTML, como campos de formulário, botões e links. Escolher o tipo correto de `type `é crucial para garantir a funcionalidade correta e a usabilidade dos elementos em uma página web.

```bash
  <input type="text" id="nome" name"nome">
```

- O atributo `alt` é usado em elementos `<img>` e `<area>`. Ele fornece um texto alternativo que é exibido quando a imagem não pode ser carregada ou quando o usuário utiliza um leitor de tela para acessar o conteúdo da página. O texto alternativo também é importante para a acessibilidade, ajudando usuários com deficiência visual a entender o conteúdo das imagens.

```bash
  <img src="imagem.jpg"alt="Descrição da imagem">
```

- O atributo `class` é usado para aplicar uma ou mais classes CSS a um elemento HTML. As classes são utilizadas para agrupar elementos que têm estilos semelhantes definidos em uma folha de estilo CSS externa ou interna. Isso permite aplicar estilos de forma consistente em vários elementos HTML sem precisar repetir o mesmo código CSS.

```bash
  <class="destaque">Este é um parágrafo destacado.</p >
```

- O atributo `style` é usado para aplicar estilos CSS inline diretamente em um elemento HTML. Ao contrário do uso de classes, que separam o estilo do conteúdo, o `style` permite aplicar estilos diretamente no próprio elemento. Isso pode ser útil para estilizar elementos individualmente ou para ajustes rápidos.

```bash
<p style="color: red; font-size: 18px;">Estilo inline.</p>
```

- O atributo `title` é usado para fornecer informações adicionais sobre um elemento quando o usuário passa o mouse sobre ele. Isso geralmente aparece como uma dica de ferramenta (tooltip) que contém o texto especificado no atributo `title`. É útil para dar explicações adicionais ou descrições breves sobre um elemento.

```bash
<a href="#"title="Clique para mais informações">Informações</a>
```


## 🧑‍💻Exemplo HTML de texto das Tags

As tags de texto em HTML são usadas para estruturar e formatar o conteúdo textual em uma página web. Elas são fundamentais para apresentar informações de maneira clara e organizada. Aqui estão algumas das principais tags de texto em HTML e suas funções básicas:

-  A tag <p> em HTML é essencial para estruturar e organizar o conteúdo textual em uma página da web. Ela é usada para definir parágrafos de texto, agrupando blocos coesos de informações que formam unidades completas de pensamento ou explicação.

```bash
<p> Este é um exemplo de parágrafo em HTML.</p>
```


- As tags `<h1>` a `<h6>` em HTML são usadas para definir cabeçalhos ou títulos de diferentes níveis de importância dentro de um documento HTML. Cada uma dessas tags representa um nível hierárquico de título, com `<h1>` sendo o mais importante e `<h6>` o menos importante. O `<h1>` é geralmente utilizado para o título principal da página ou seção, enquanto `<h2>` é usado para subtítulos importantes dentro dessa seção principal.

```bash
<h1> Título de nível 1 </h1>

<h2> Título de nível 2 </h2>
```
- A tag `<u>` em HTML é utilizada para aplicar sublinhado ao texto dentro dela. Originalmente, era comum seu uso para indicar que o texto deveria ser sublinhado visualmente em navegadores antigos que não suportavam estilos CSS avançados. No entanto, com o avanço das práticas modernas de desenvolvimento web e acessibilidade, seu uso para estilização visual foi desencorajado.

```bash
Este documento foi assinado de forma _digital_
```
- A tag `<blockquote>` é usada para representar uma citação longa ou bloco de texto que deve ser destacado do restante do conteúdo. É comumente utilizado para citações de outros autores.

```bash
             Esta é uma citação longa que deve ser destacada.
```

- A tag `<sup>` é usada para definir texto sobrescrito, que aparece acima da linha de base normal do texto. É comumente usado para notações matemáticas, notas de rodapé ou outras informações que precisam ser exibidas acima do texto normal.
```bash
       E=mc²
```


## 🧑‍💻Exemplo Listas em HTML

Em HTML, as listas são usadas para organizar informações de maneira estruturada. Existem dois tipos principais de listas: listas não ordenadas `(<ul>)` e listas ordenadas `(<ol>)`.

- **Listas Não Ordenadas `(<ul>)`:** As listas não ordenadas são usadas quando a ordem dos itens não é importante. Cada item é precedido por um marcador, geralmente um ponto.



       ° Primeiro item
       ° Segundo item
       ° Terceiro item 

- **Listas Ordenadas `(<ol>)`:** As listas ordenadas são usadas quando a ordem dos itens é significativa. Cada item é numerado sequencialmente.

      1. Primeiro item
      2. Segundo item
      3. Terceiro item 
- **Elemento `<li>`:** A tag `<li>` é usada dentro de `<ul>` e `<ol>` para cada item da lista. Ela define o conteúdo de cada item da lista. As listas em HTML são úteis para estruturar informações de forma organizada e semântica em uma página web, facilitando a compreensão e a navegação para os usuários.




## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/welly-candido-8a525a1ab)


