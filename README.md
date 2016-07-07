Escrever e versionar um livro com markdown, seguindo um padrão de estrutura, para que um webapp suporte a importação desse repositório, e gere o livro para leitura, semelhante ao google books.

## Estrutura do livro

* front-cover.png = capa da frente (optional)
* back-cover.png = capa de tras (optional)
* fake-branding.md = falsa folha de rosto (optional)
* branding.md = folha de rosto (required)
* branding-verse.md = verso da folha de rosto (optional)
* dedication.md = dedicatória (optional)
* epigraph.md = epígrafe, citação, pensamento (optional)
* figure-list.md = lista de figuras (optional)
* abbreviation-list.md = lista de abreviações e siglas (optional)
* preface.md = prefácio (optional)
* acknowledgment.md = agradecimentos (optional)
* introduction.md = introdução (optional)
* book.md = descrição e configurações do livro, titulo, descricao, autor, sumário automatico...
* pages/ = pasta com as paginas
  pages/1.captule-name.md = nome do arquivo é um slug do capítulo
* figures/ = pasta com as ilustrações


### convert to Markdown

many to md = http://pandoc.org/

word to md = https://word-to-markdown.herokuapp.com/

word to md = http://www.writage.com/


### Markdown editor

https://stackedit.io/editor

https://markable.in/

http://dillinger.io/

### ideas

* suporte a gif
* previa dos links que nem o telegram facebook faz quando posta algum link.
* previa de videos youtube vimeo etc
* um pequeno chat global dentro do livro, tipo o chat do google docs, com os leitorem que estão lendo no momento.
* offline mode
* reportar erro (criar uma issue no repositorio)
* modo revisor (enviar pull request, basear no revisor do google docs)
* buscar por livros ja adicionados antes
* livros privados, obter acesso atraves de APIs
* aceitar doações nos livros ou pagamentos por livros privados.
* Favoritar
* Classificações
* adicionar livros atraves da conta do github/bitbucket
* validador de livros
* Identificar se existe o livro igual ou semelhante para evitar copias


### criar um arquivo de configuração para o livro que nem o composer.json

* title text (required)
* description text (optional)
* categories list (default none) (optional)
* summary boolean (default true) (optional)
* adult content false or integer age (default false) (optional)
* contributors list (required)
* donation link (optional)
* captule-separate-page boolean (default false) (optional) (capitulo separado em uma pagina ou junto com o conteúdo)
