# Conceitos-react-native
## Primeiro desafio de react native do bootcamp GoStack.
Nesse desafio foi criado uma aplicação que conecta ao back-end que foi desenvolvido no desafio de NodeJS.
Basicamente é um projeto que armazena os seus repositorios.

## Link do respositorio do back-end.
- https://github.com/Maxmiller-Nunes/conceitos-nodejs

## Como usar?
- Assim que abrir o projeto no editor de codigo execulte um `yarn` para instalar as dependência do projeto.
- Após isso, pode rodar um `yarn start` para execultar o metro-bundler do app.
- Logo depois em outro terminal na pasta do projeto execulte `yarn android` ou `yarn ios` para execultar o app no emulador ou dispositivo fisico.
- #### OBS: Se estiver no emulador Android, ele deve estar aberto.
- Após isso, acesse a pasta do back-end e pode rodar um `yarn dev` para rodar a aplicação que ficará disponível no endereço `http://localhost:3333`.
- Está disponível também os teste, para execultar, basta rodar `yarn test`.

## Funcionalidades feitas no front-end.

- GET `/repositories:` Rota que lista todos os repositórios;

- POST `/repositories/:id/like:` A rota atualiza os likes do repositório desejado;


## Rotas da aplicação que estão disponiveis no bakc-end

- POST `/repositories:` A rota deve receber title, url e techs dentro do corpo da requisição, para criar um repositório;

- GET `/repositories:` Rota que lista todos os repositórios;

- PUT `/repositories/:id:` A rota atualiza um repositório desejado;

- DELETE `/repositories/:id:` A rota deleta um repositório desejado;

- POST `/repositories/:id/like:` A rota atualiza os likes do repositório desejado;
