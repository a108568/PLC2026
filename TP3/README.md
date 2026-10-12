## Titulo

Analisador Léxico

## Autor

- Nome: Henrique Louro Correia
- ID:a108568
<p align="center">
  <img src="./imagem.jpeg" width="150">
</p>


## Resumo

O objetivo deste trabalho foi desenvolver um analisador léxico em Python para uma linguagem de queries.

O programa identifica diferentes tipos de tokens, como variáveis (`?nome`), strings (`"Chuck Berry"`), identificadores (`foaf:name`), números (`1000`) e delimitadores (`{`, `}` e `.`). Também reconhece palavras reservadas, ignora comentários e espaços e identifica caracteres inválidos.

Para isso, utilizei a função `re.finditer()`, os grupos nomeados e o método `groupdict()`. Os tokens reconhecidos são guardados numa lista com o seu tipo, valor, linha e posições no texto.

Por fim, testei o programa com diferentes exemplos para verificar se os tokens eram reconhecidos corretamente.

## Lista de Resultados

- [Resolução](./resolucao.txt)
