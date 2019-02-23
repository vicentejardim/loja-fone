# HTML 5

É uma linguagem de marcação que tem as seguintes responsabilidades:

- Conteúdo (cuida tudo que é conteúdo do site, demarca conteúdo);
- Semântico(tags);
- Estrutura

`<h1>` - heading 1 - 6
Usamos ele quando queremos definir títulos

`<a>` - Link (a - anchor)
Usamos para definir a navegação do usuário. Se você tem um texto que você quer que o usuário clique e ele vá para outro lugar você pode usar essa tag junto com o atributo `href`. Exemplo de um `a` que o usuário é direcionado para o site da collabcode.training:

```
<a href="http://www.collabcode.training">CollabCode.Training</a>
```

# CSS

É uma linguagem de estilo que tem as seguintes responsabilidades

- Visual;

inherit: faz com que uma tag herde uma atributo da tag pai
Float: cria um novo contexto.
Float nunca esconde conteúdo.
O tamanho do elemento é o conteúdo.

Respiros Internos e Externos
Respiro é um termo usado em Design e se refere ao espaço entre os elementos de um layout. O respiro pode ocorrer entre a borda de um elemento e o limite da tela ou entre elementos (respiro externo) ou entre o elemento e o conteúdo interno a este elemento (respiro interno)

Para criar respiros externos no CSS é usada a propriedade `margin`. Ex:
margin-left: 50px; cria um respiro externo de 50px entre o elemento e a borda da tela.
margin-right: 60px ; cria um respiro externo de 60px entre o elemento e a borda da tela.

Os respiros internos são criados com a propriedade `padding`. Ex:
padding-top: 55px; cria um respiro interno de 55px entre a extremidade superior do elemento e seu conteúdo.
padding-bottom: 95px; cria um respiro interno de 95px entre a extremidade inferior do elemento e seu conteúdo.

O padding e o margin podem ser definidos para todas as extremidades de uma única vez, usado apenas o atributo padding sem referir-se a qualquer extremidade.

/_ padding: top right bottom left; _/
padding: 60px 60px 60px 95px;

A definição acima atribui valores para os respiros internos e refere-se as extremidades de cima (top), direita (right), esquerda (left) e baixo (bottom), ou seja, define os 4 respiros numa única linha.

Aproveitando este conceito, o padding tem as seguintes variações para definição dos respiros:

/_ padding top/bottom right/left _/
padding: 60px 60px;
Quando o mesmo respiro será usado para cima/baixo e direita/esquerda.

/_ padding top right/left bottom _/
padding: 60px 60px 95px;
Para valores de respiros diferentes entre cima, baixo e o par direita/esquerda

/_ padding top/right/bottom/left _/
padding: 60px;
Quando um único valor de respiro será usado para todas as extremidades.

O margin pode ser usado da mesma forma
