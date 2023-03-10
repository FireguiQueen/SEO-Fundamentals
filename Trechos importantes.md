# Trechos importantes



## Tags semânticas

### Negrito `<strong>`
O negrito é extremamente importante, é ele que da uma relevância maior a determinado trecho, tanto em questões visuais, quanto no próprio código. 
É importe utilizar apenas quando queremos que aquele trecho realmente seja destacado, e é sempre bom utilizar em palavras chaves que estão relacionadas ao conteúdo de sua página.

### Itálico `<em>`
O uso de itálico pode ser mais comum em citações, obras literárias, nomes científicos e estrangeiros, e em algumas linguagens de programação, onde é usado para destacar comandos ou trechos de códigod. Em geral, o itálico também pode ser pensado como um negrito, porém, para trechos que possuem um pouco menos de relevância.

### Marcação `<mark>`
É útil em várias situações, como para destacar uma palavra-chave importante, uma citação notável, um trecho de código, uma data, um endereço ou outro tipo de informação relevante. Ela pode ser usada em conjunto com outras tags HTML, como `<p>`, `<h1>`, `<li>` e outras.
Quando o navegador exibe o conteúdo da página, o texto envolvido pela tag `<mark>` geralmente aparece com um fundo amarelo claro, mas isto pode ser alterado usando a propriedade `background-color` do CSS.

### Sublinhdo `<ins>`
A tag "ins" é mais comumente usada em documentos colaborativos ou em documentos que passaram por revisão, onde é importante indicar claramente o que foi adicionado em relação à versão original. A tag "ins" pode ser combinada com outras tags de formatação de texto, como negrito ou itálico, para enfatizar ainda mais a inserção.

Por exemplo, se um documento original contém o texto "O gato pulou a cerca", e a versão revisada incluiu a palavra "alta" para descrever a cerca, o trecho revisado poderia ser marcado com a tag "ins":
```html
O gato pulou a <ins>cerca alta</ins>.
<!-- Isso tornaria claro para o leitor que a palavra "alta" foi adicionada à versão revisada do texto.
-->
```

### Subscrito/sobrescrito `<sub>`
É usada para representar texto subscrito ou sobrescrito, ou seja, um texto que aparece ligeiramente abaixo ou acima da linha de base comum, como na representação de fórmulas químicas, equações matemáticas e notas de rodapé. Isso ajuda a tornar o texto mais claro e fácil de entender para o leitor, especialmente em casos onde a formatação correta é crucial, como em conteúdo científico e técnico.
Por exemplo, a fórmula da água se escreve "H20", mas o número "2" fica um pouco mais abaixo, você pode usar o `<sub>` para resolver isto. 
```html
H<sub>2</sub>O
```

### Códigos `<code>`
Ela é usada para indicar que o texto contido dentro dela é um trecho de código, como uma linha de código em uma linguagem de programação, por exemplo. A utilização correta da tag `<code>` ajuda a destacar o trecho de código no conteúdo e a melhorar a legibilidade e compreensão do texto. Além disso, a tag faz com que o texto dentro dela tenha uma fonte monoespaçada, o que torna o código mais legível e fácil de ler para os desenvolvedores.

Caso o seu código possua mais linhas, você pode utilizar da tag `pre`. O texto contido dentro dela deve ser apresentado exatamente como está, preservando espaços, indentações, quebras de linha e outros espaçamentos colocados no seu editor de código.

### Citações `<q> ; <blockquote> ; <cite>`
A tag `<q>` é mais utilizada para representar pequenos trechos que foram retirados de outro lugar. Usada para representar uma citação curta (short quotation).

A tag `blockquote` é como se fosse uma tag `<q>`, porém, para citações longas, que ocupam mais de um parágrafo. Então caso queira citar um trecho longo de um livro por exemplo, você usaria da tag `blockquote`.

A tag `<cite>`, por sua vez, é utilizada para indicar a autoria de uma citação ou referência a uma fonte. Ela é geralmente utilizada dentro das tags `<blockquote>` ou `<q>` como um atributo. Mas também pode ser usada em outros contextos, como para citar o autor de um livro ou artigo no corpo do texto.
 
</br>
</br>


## Tags não semânticas 
As tags não semânticas não são muito utilizadas, pois como o próprio nome já diz, ela não possui semântica, e a única coisa que ela fará será apenas uma formatação de um conteúdo, mas isto não irá significar nada ao SEO. 
São mais utilizadas para "substituir" a parte do CSS. Invés de você estilizar um trecho usando o CSS, você apenas irá colocar a tag `<b>`, que serve para fazer um negrito visual. 

- <b> </b> <!-- Adiciona negrito ao conteúdo -->
- <i> </i> <!-- Adiciona itálico ao conteúdo -->
- <u> </u> <!-- Adiciona sublinhado ao conteúdo -->
