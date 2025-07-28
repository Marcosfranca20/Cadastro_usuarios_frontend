# Cadastro de Usuários

Este projeto é uma aplicação React criada com Vite para cadastro, listagem e remoção de usuários. Utiliza integração com uma API backend para persistência dos dados.

## Funcionalidades

- Cadastro de usuários com nome, idade e e-mail
- Listagem dos usuários cadastrados
- Remoção de usuários
- Interface moderna e responsiva

## Tecnologias utilizadas

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Axios](https://axios-http.com/)
- [ESLint](https://eslint.org/)

## Como executar

1. Instale as dependências:
   ```sh
   npm install
   ```
2. Inicie o servidor de desenvolvimento:
   ```sh
   npm run dev
   ```
3. Acesse [http://localhost:5173](http://localhost:5173) no navegador.

## Estrutura de pastas

```
cadastro-usuarios/
  src/
    pages/
      home/
        index.jsx
        style.css
    services/
      api.js
    assets/
      trash.svg
    main.jsx
    index.css
  public/
    vite.svg
  index.html
  package.json
  vite.config.js
  eslint.config.js
  README.md
```

## Backend

A aplicação espera que a API backend esteja rodando em `http://localhost:3000` com os endpoints:

- `GET /usuarios` — lista usuários
- `POST /usuarios` — cadastra usuário
- `DELETE /usuarios/:id` — remove usuário

## Licença

Este projeto é open-source e está sob a licença MIT.