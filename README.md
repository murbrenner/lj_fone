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
