# Mercado Livre Test

Olá, este é um pequeno teste realizado com a API disponibilizada pelo Mercado Livre, onde é possível realizar consultas de produtos anunciados.

Nesse App, é possível realizar buscas através da barra de busca, será exibido 4 produtos para você, ao clicar em cada um deles você é redirecionado para a página do produto, na qual contém uma foto do produto, descrição, valor e outras informações.

O App foi construído em ReactJS e NodeJS, o backend construído faz uma busca a api, filtrando alguns dados básicos, o front recebe e exibe as informações.

Confesso que foi um tanto desafiador realizar a parte de buscas, a qual funciona tanto pela barra quanto pelo url, quebrei a cabeça pra descobrir como passar parâmetros de um componente para outro através de query params.

## Novas features !

Novas features foram adicionadas para complementar a aplicação como um todo a partir do commit 21.

- Agora é possivel adicionar itens aos favoritos, estes itens sao visualizados na pagina principal.
- Cada item visualizado é acrescentado a lista "Mais Visitados" na pagina inicial, com no maximo de 9 items
- Ao fazer uma pesquisa, é possivel navegar por varias páginas, não sendo mais limitado como antes.
- Temos um carousel main na pagina principal, no qual exibe itens aleatorios com base no ultimo item visualizado !
- Ajustado alguns bugs encontrados.

# Rodando em seu computador

Basicamente, após clonar o repositório, basta apenas executar os seguintes comandos:

```sh
$ cd BackEnd
$ yarn
$ yarn dev
```

Então, abra outra aba no seu terminal, entre na do projeto e execute:

```sh
$ cd FrontEnd
$ yarn
$ yarn start
```

O comando yarn citado acima, é apenas para atualizar as dependencias do projeto.
Pronto! agora é só acessar localhost:3000 em seu navegador e dar uma olhadinha :)

<p align="center">
  <img width="460" height="300" src="http://www.fillmurray.com/460/300">
</p>
