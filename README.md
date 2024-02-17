# TEI XML YASnippets

Este repositório contém uma coleção de arquivos YASnippet projetados para uso com nxml-mode no Emacs, especialmente adaptados para a edição de arquivos de texto TEI XML. YASnippet é um sistema de modelo para o Emacs que permite inserir construções de código comumente usadas com apenas algumas teclas.

## Instalação

Para usar esses snippets, você precisará ter o YASnippet instalado em sua configuração do Emacs. Se você ainda não instalou o YASnippet, pode fazê-lo seguindo as instruções na [página do GitHub do YASnippet](https://github.com/joaotavora/yasnippet).

Depois de instalar o YASnippet, você pode clonar este repositório em seu diretório de snippets do YASnippet. Por exemplo, se o diretório de snippets do YASnippet estiver localizado em `~/.emacs.d/snippets`, você pode clonar este repositório usando o seguinte comando:

```sh
git clone https://github.com/arete-estudos-helenicos/tei-yasnippets.git ~/.emacs.d/snippets/nxml-mode
```

Para o Spacemacs:

```sh
git clone https://github.com/arete-estudos-helenicos/tei-yasnippets.git ~/.emacs.d/private/snippets/nxml-mode
```


## Uso

Depois de instalar os snippets, você pode usá-los ao editar arquivos TEI XML no Emacs. Basta digitar a palavra-chave do snippet e pressionar `TAB` para expandir o snippet. Por exemplo, digitar `app` e depois pressionar `TAB` irá expandir o snippet para inserir um elemento de aparato TEI.

## Snippets Disponíveis

- `app`: aparato
- `rdg`: leitura dentro do aparato
- `wit`: testemunha

- `fil`: fala de Filebo
- `prot`: fala de Protarco
- `soc`: fala de Sócrates

- `stephpg`: nova página de Stephanus
- `stephsec`: nova seção de Stephanus

## Contribuindo

Se você tiver snippets XML TEI adicionais que gostaria de contribuir, sinta-se à vontade para fazer um fork deste repositório, adicionar seus snippets e enviar um pull request. Suas contribuições são muito apreciadas!
