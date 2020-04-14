# Ranking Escalada  
Ranking criado apenas para incentivar a mim e um grupo de amigos que pratica escalada indoor a nos manter motivados.

## Editar Ranking  
Para alterar os dados, deve-se editar o arquivo html seguindo as dicas abaixo.

### Novo participante  
Inserir uma nova div com a classe "row-bar" (exemplo abaixo) alterando as informações GRAU, HEX, NOME e PICTURE.
GRAU: Graduação de via de escalada, responsável pelo tamanho da barra do gráfico. possíveis classes são ._4 ._4sup ._5A ._5B ._5C ._6A ._6B.
HEX: Hexadecimal com a cor da barra desejada.
NOME: Nome da pessoa.
PICTURE: Caminho da imagem do rosto da pessoa.

```
<div class="row-bar">
  <div class="bar GRAU" style="background: HEX">
    <span class="climber-name">NOME</span>
    <div class="face"><img src="PICTURE.png"></div>
  </div>
</div>
```

### Editar participante  
Editar as informações (grau, cor da barra, nome e imagem) na "row-bar" do participante desejado.

### Excluir participante
Excluir a "row-bar" do participante desejado.

[post no meu site falando sobre esse projeto](https://mateusmartos.com.br/ranking-de-escalada/)
