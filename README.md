# Projeto de Consumo de API Rest com ReactJS

Este projeto é uma aplicação web desenvolvida em ReactJS que consome uma API Rest hospedada no Heroku. Ele utiliza diversas tecnologias populares, incluindo Redux, Redux Saga, Axios, React Router Dom, Styled Components, React Toastify, entre outras.

## Funcionalidades Principais

- Consumo de uma API Restful para exibir e manipular dados.
- Gerenciamento de estado utilizando Redux para manter um estado global consistente.
- Utilização do Redux Saga para lidar com efeitos colaterais, como chamadas de API assíncronas.
- Persistência de dados do Redux com Redux Persist para manter o estado da aplicação mesmo após recarregamento da página.
- Navegação entre diferentes páginas da aplicação utilizando React Router Dom.
- Estilização dos componentes utilizando Styled Components para uma melhor organização e manutenção do código.
- Exibição de notificações utilizando React Toastify para feedback ao usuário.

## Tecnologias Utilizadas

- ReactJS: Biblioteca JavaScript para construção de interfaces de usuário.
- Redux: Biblioteca para gerenciamento de estado.
- Redux Saga: Middleware para gerenciar efeitos colaterais em aplicações Redux.
- Redux Persist: Biblioteca para persistência de estado do Redux.
- Axios: Cliente HTTP baseado em Promises para fazer requisições para a API.
- React Router Dom: Roteamento de URLs na aplicação React.
- Styled Components: Biblioteca para estilização de componentes utilizando CSS-in-JS.
- React Toastify: Biblioteca para exibição de notificações na aplicação React.

## Deploy

A aplicação frontend está hospedada em um servidor Nginx, enquanto a API está hospedada no Heroku.

### Frontend (Nginx)

O frontend da aplicação está hospedado em um servidor Nginx. Para fazer o deploy, siga os seguintes passos:

1. Clone o repositório para o seu ambiente local.
2. Execute `npm install` para instalar as dependências.
3. Execute `npm run build` para gerar a versão de produção da aplicação.
4. Configure o servidor Nginx para servir os arquivos estáticos gerados na pasta `build`.

### Backend (Heroku)

A API está hospedada no Heroku. Para mais informações sobre a API e como fazer deploy, consulte o repositório da API.

