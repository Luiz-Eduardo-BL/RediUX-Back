# Guia das Estruturas do Projeto RediUX

Este guia descreve detalhadamente as estruturas do Front-End e Back-End do projeto RediUX, que servem como uma base para o desenvolvimento. É importante ressaltar que essas estruturas são recomendadas, mas não obrigatórias, e podem ser adaptadas de acordo com as necessidades do projeto.


## Estrutura do Front-End

A estrutura do Front-End é projetada para criar uma experiência de usuário fluida e responsiva e segue as seguintes arquiteturas:

- **`public`**: Contém arquivos públicos, como ícones e imagens.

- **`src`**: O núcleo do Front-End.

    - **`assets`**: Recursos estáticos, como imagens e fontes.

    - **`components`**: Componentes reutilizáveis da interface do usuário.

    - **`pages`**: Páginas da aplicação, representando diferentes visualizações.

    - **`routes`**: Definição das rotas da aplicação.

    - **`services`**: Serviços para interação com APIs e tarefas específicas.

    - **`styles`**: Arquivos de estilo (CSS, SCSS) para design.

    - **`utils`**: Funções utilitárias.

    - **`App.js`**: Ponto de entrada da aplicação.

    - **`index.js`**: Inicializa a aplicação.

    - **`routes.js`**: Define as rotas da aplicação.

- **`.gitignore`**: Lista de arquivos e diretórios ignorados pelo Git.

- **`package.json`**: Manifesto de Node.js com dependências e scripts.

- **`README.md`**: Documentação detalhada sobre a estrutura e uso do Front-End.

## Estrutura do Back-End

A estrutura do Back-End fornece uma base sólida para lógica de negócios e gerenciamento de dados e segue as seguintes arquiteturas:


- **`src`**: O núcleo do Back-End.

    - **`app`**: Controladores, middlewares, modelos e rotas da aplicação.

        - **`controllers`**: Lida com solicitações da API.

        - **`middlewares`**: Intercepta solicitações.

        - **`models`**: Define modelos de dados.

        - **`routes`**: Define rotas da API.

        - **`app.js`**: Ponto de entrada Back-End.

    - **`config`**: Configurações específicas da aplicação.

    - **`lib`**: Bibliotecas ou módulos personalizados.

    - **`server.js`**: Inicializa o servidor.

    - **`routes.js`**: Define as rotas da API.

- **`.gitignore`**: Lista de arquivos e diretórios ignorados pelo Git.

- **`package.json`**: Manifesto de Node.js com dependências e scripts da aplicação Back-End.

- **`README.md`**: Documentação detalhada sobre a estrutura e o uso do Back-End.
