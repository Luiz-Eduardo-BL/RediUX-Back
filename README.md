![RediUX Logo](/assets/favicon.svg)

## Sobre o Projeto

O RediUX é uma aplicação web que tem como objetivo simplificar o compartilhamento de conteúdo educacional. Ele serve como um Repositório Digital de User Experience, armazenando materiais didáticos fornecidos pela professora da disciplina de UX para alunos interessados em consumir aulas, artigos, postagens e vários tipos de mídia que auxiliam na aprendizagem.

## Equipe

Este projeto foi desenvolvido por uma equipe multidisciplinar dedicada à criação de soluções educacionais eficientes e acessíveis:

- **Orientadora do Projeto**:
  - [Ingrid Teixeira](https://www.linkedin.com/in/ingrid-teixeira-monteiro-47b68012)

- **Designers**:
  - [Beatriz Vasconcelos](https://www.linkedin.com/in/beatrizvasconceloss)
  - [Weydla Alves](https://github.com/weydlaalves)

- **Desenvolvedores**:
  - [Edoardo Nogueira](https://github.com/edoardonog)
  - [Hugo Maciel](https://www.linkedin.com/in/hugo-maciel-coelho)
  - [Luiz Eduardo](https://github.com/Luiz-Eduardo-BL)
  - [Jefferson Uchoa](https://www.linkedin.com/in/jefferson-uchoa-b264b3186)

## Guia de Commits

Para manter um histórico claro e organizado do desenvolvimento deste projeto, seguimos as seguintes convenções de mensagens de commit: [Guia de Commits](https://github.com/Luiz-Eduardo-BL/QuixHouse/blob/main/COMMIT_GUIDE.md)

## Tecnologias Utilizadas

- **Front-End**: React
- **Back-End**: Node.js
- **Banco de Dados**: Firebase Firestore

## Criação de Projetos

Para criar os projetos Front-End e Back-End, recomendamos o uso da ferramenta Vite. O Vite é um construtor de projetos rápido e flexível para o desenvolvimento web moderno. Você pode encontrar a documentação do Vite [aqui](https://vitejs.dev/).

## Estrutura do Projeto

Para um detalhamento completo sobre as pastas e arquivos, consulte o [Guia de Estruturas](/STRUCTURE_GUIDE.md).

### Estrutura Front-End

A estrutura do Front-End é projetada para criar uma experiência de usuário fluida e responsiva, seguindo as melhores práticas de desenvolvimento. Está organizada da seguinte forma:

``` bash
├── public
├── src
│   ├── assets
│   ├── components
│   ├── pages
│   ├── routes
│   ├── services
│   ├── styles
│   ├── utils
│   ├── App.js
│   ├── index.js
│   └── routes.js
├── .gitignore
├── package.json
└── README.md
```

### Estrutura Back-End

A estrutura do Back-End fornece uma base sólida para lógica de negócios e gerenciamento de dados e segue a arquitetura MVC (Model-View-Controller). Está organizada da seguinte forma:

``` bash
├── src
│   ├── app
│   │   ├── controllers
│   │   ├── middlewares
│   │   ├── models
│   │   ├── routes
│   │   └── app.js
│   ├── config
│   │   └── database.js
│   ├── lib
│   │   └── app.js
│   ├── server.js
│   └── routes.js
├── .gitignore
├── package.json
└── README.md
```

A estrutura do Back-End segue os princípios da arquitetura MVC (Model-View-Controller), onde os controladores (`controllers`) lidam com as solicitações da API, os modelos (`models`) definem a estrutura dos dados e as rotas (`routes`) gerenciam as diferentes endpoints da aplicação. O arquivo `server.js` é responsável por iniciar o servidor.

## Como Executar o Projeto

Para executar o projeto, siga os passos abaixo:

1. Clone este repositório para sua máquina local.
2. Configure o ambiente de desenvolvimento conforme especificado na seção "Ambiente de Desenvolvimento".
3. Certifique-se de ter todas as dependências instaladas executando `npm install` nas pastas do Front-End e do Back-End.
4. Inicie o Front-End e o Back-End separadamente com os comandos apropriados.
5. Acesse a aplicação no navegador usando o endereço local especificado durante a execução.

## Contribuições

Contribuições para o projeto são bem-vindas. Sinta-se à vontade para abrir problemas (issues) e enviar solicitações de pull (pull requests) para melhorias, correções de bugs ou novos recursos. Juntos, podemos tornar o Repositório Digital de User Experience (RediUX) uma plataforma educacional excepcional.
