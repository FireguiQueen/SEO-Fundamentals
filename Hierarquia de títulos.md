# Títulos em HTML 

No HTML, temos 6 níveis de títulos.: h1, h2, h3, h4, h5, h6.  </br>
A letra "h" significa "heading", e o número ao lado é o nível deste título. 
A tag h1 por exemplo, é a tag utilizada para títulos principais, e isto é uma regra 
quando você deseja fazer um site semântico e bem estruturado. 

É importante lembrar que, mesmo tendo a opção de colocar a tag h2 como título principal do site, e depois modificar o tamanho e espesssura no CSS para ficar que nem uma h1, você jamais deve fazer isto. Não há o menor problema em estilizar as tags de título usando o CSS, mas jamais estilize para poder usar uma tag h2 como uma tag h1 por exemplo. 

Sempre respeite a hierarquia, jamais coloque as tags de títulos de maneira desorganizada. Como por exemplo.:
```html
<h1> </h1>
<h3> </h3>
<h2> </h2>
```

Sua página pode possuir mais de uma h1, mas é importante separar por sections.
```html
<section class="">
    <h1>Sobre mim </h1> 
</section>
<section>
    <h1>Contato</h1>
</section>
```

Uma hierarquia de títulos bem organizada ajuda os leitores a entender o conteúdo de forma clara e eficiente, além de ser uma boa prática de SEO, já que os motores de busca valorizam páginas que usam títulos de forma adequada e hierárquica.