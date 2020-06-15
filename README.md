![Github Explorer Logo](./src/assets/logo.svg) <br />
## Aplicação desenvolvida em _ReactJS_ para explorar repositórios do Github ##

![CapturarGitHubExplorer01](https://user-images.githubusercontent.com/60238162/84607663-e76fc780-ae84-11ea-9166-5a75de3f5a3a.PNG)<br />
> Página inicial da aplicação, onde o usuário pode buscar os repositórios que desejar

### Como a aplicação funciona? ###
Ao abrir, o usuário digita o nome do repositório. Então haverá uma requisição ajax para a API disponibilizada pelo Github.
Se o repositório for encontrado, o app irá listá-lo na tela de dashboard. Para ver os detalhes do repositório, basta o usuário clicar 
na lista para ser direcionado à segunda página da aplicação: a página que mostra alguns dados do repositório, como stars, forks e issues abertas.


![CapturarGitHubExplorer02](https://user-images.githubusercontent.com/60238162/84607677-fb1b2e00-ae84-11ea-8189-f91cb2645110.PNG) <br />
> Página que detalha o repositório escolhido pelo usuário

### Quais as tecnologias utilizadas? ###
✓ Typescript <br />
✓ ReactJS <br />
✓ Styled Components <br /> 
✓ Axios <br />
✓ API Rest do Github <br />

### Como executar a aplicação? ###
> O comando yarn também pode ser usado para seguir as instruções

- Dê o comando `npm install` dentro do diretório do projeto para que seja feito o download das dependências.
- Após instalado, execute o comando `npm start` para inicializar o projeto, que deve ser aberto em `localhost:3000`.
