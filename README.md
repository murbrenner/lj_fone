<!-- @format -->

# HTML

É uma linguagem de marcação que tem as seguintes responsabilidades:

- Conteúdo;
- Semântico (tags);
- Estrutura;

- `h1>` - heading: de 01 a 06 (no máx h3)
  Usamos ele quando queremos definir titulos

- `<a>` - Link (a - anchor)
  Usamos ela para definir a navegação do usuario. Se vc tem um texto que vc quer que o usuario clique e ele va pra outro lugar, vc pode usar essa tag junto com o atributo `href`. Exemplo:

```
<a href="http://www.google.com.br">Busca</a>
```

# CSS

é uma linguagem de estilo, isso quer dizer que ela tem as seguintes responsabilidades:

- Visual;

`float` = puxa o elemento pra frente, e automaticamente eles ficam na mesma linha;

- o outro elemento de baixo vem pra trás;
- no float o texto nao é escondido.
- o tamanho começa a respeitar o tamanho do conteudo apenas, deserdando do pai.

`overflow` = recalcula o contexto;

- hidden - faz o pai reconsiderar os filhos;

`margin` - rspiro externo;

`padding` - respiro interno;

`padding/margin` - para ambos, pode-se utilizar de 1 a 4 variaveis, sempre respeitando o sentido horario, exceto para a de 2 variaveis, que fica top/left e right/bottom.

`nome_da_tag` = apenas digitar o nome da tag da sintaxe do html.
no html: `<html>`
no css: html {}

`#nome_da_id` = um por pagina, pra chamar a id no css, usa-se "#".

`.nome da class` = pra chamar a class no css, usa-se ".".

- usada para comportamentos repetitivos. fuja da `id`.

`display inline` = deixa elementos na mesma linha;
nao consegue definir `width` e `height`;

`display block` = manda o elemento para a linha de baixo;
define `width` e `height` tranquilo;

`display inline-block` = deixa elementos na mesma linha;
define `width` e `height` tranquilo;

`position: absolute` = cria um novo contexto;

- quem define width e height é o conteudo;
- utiliza-se propriedades `top bottom left e right` para mover-se em relacao a pagina;
- a referencia base para movimentacao é o pai do elemento;
- ele tbm se referencia pelo lado esquerdo (da esquerda para a direita de cima para baixo, modo de leitura padrao)

`transform: translateX(+-XX%);` - "remove" a porcentagem para a centralizacao do elemento alinhado pelo `top bootom left e right` do comando anterior.

`div` = divisão visual de conteúdo. pode ajudar a organizar utilizando com algumas "class" no html.

`MDN` - site para consultar duvidas de valores para html.

- link: https://developer.mozilla.org/pt-BR/

`vertical align` - funciona com `display: inline-block` (um do lado do outro). o padrao é `baseline` (vertical-align: baseline;)

- é permitido colocar top, bottom, left e right para manipular as referencias e resetar posicoes.

`box-sizing: border-box` - o padrao é `content box`.

- pra fazer a borda se tornar parte da "caixa" coloca-se `border-box`
- isso implica no line height pq vai somar com a borda após isso.

No `HTML` toda classe que começa com "-" é uma variação. Precisa de uma base e dps dessa base add um recurso que vai fazer a diferença da base.

- No `CSS` fica ".-second" para chamar uma classe variante de outra.

`SELETOR E` - Pra fazer com q o `CSS` entenda e tenha pré-requisitos pra carregar uma classe pode-se digitar `.button-store.-second` onde button store e second sao requisitos para q aquela config do CSS funcione. se nao tiver qqr uma delas, a config nao funciona. alem disso vc pode criar outra classe "-second" e apenas usar esse estilo de pre-requisitar a outra para q funcione especificamente nessa second criada dps.

`<dl> - description list` = usada para descrição de produtos em sites, a descrição completa.

`<dt> - description title` = usada para descrição de produtos em sites, especificamente para TÍTULOS, o inicio de tudo.

`<dd> - define description` = definicao do que esta sendo escrito.
