# Fancy Todo List

Este é um projeto de lista de tarefas desenvolvido com React, Material-UI e Dexie.js. Ele permite criar, visualizar e gerenciar listas de tarefas de forma eficiente.

## Estrutura do Projeto

```
.DS_Store
.eslintrc.cjs
.gitignore
.prettierrc.json
index.html
package.json
READ.ME
src/
  components/
    AllTodoLists.jsx
    App.jsx
    AppHeader.jsx
    CurrentTodoList.jsx
    NewListDialog.jsx
  hooks/
    useTodoList.js
    useTodoLists.js
  main.jsx
  providers/
    AppState.jsx
  utils.js
vite.config.js
```

## Instalação

1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/fancy-todo-list.git
   ```

2. Navegue até o diretório do projeto:
   ```sh
   cd fancy-todo-list
   ```

3. Instale as dependências:
   ```sh
   npm install
   ```

## Scripts Disponíveis

No diretório do projeto, você pode executar:

### `npm run dev`

Executa o aplicativo no modo de desenvolvimento.
Abra [http://localhost:3000](http://localhost:3000) para visualizá-lo no navegador.

### `npm run build`

Compila o aplicativo para produção na pasta `dist`.

### `npm run lint`

Executa o linter para verificar problemas no código.

### `npm run preview`

Visualiza a versão de produção do aplicativo.

## Estrutura dos Componentes

- **App.jsx**: Componente principal que encapsula toda a aplicação.
- **AppHeader.jsx**: Cabeçalho da aplicação com a opção de adicionar novas listas.
- **AllTodoLists.jsx**: Exibe todas as listas de tarefas.
- **CurrentTodoList.jsx**: Exibe a lista de tarefas atual selecionada.
- **NewListDialog.jsx**: Diálogo para criar uma nova lista de tarefas.

## Hooks

- **useTodoList.js**: Hook para gerenciar uma lista de tarefas específica.
- **useTodoLists.js**: Hook para gerenciar todas as listas de tarefas.

## Estado Global

- **AppState.jsx**: Provedor de estado global para gerenciar a lista de tarefas atual.

## Utilitários

- **utils.js**: Contém funções utilitárias para interagir com o banco de dados Dexie.

## Configuração do Vite

- **vite.config.js**: Configuração do Vite para o projeto.

## Configuração do ESLint

- **.eslintrc.cjs**: Configuração do ESLint para manter a qualidade do código.

## Configuração do Prettier

- **.prettierrc.json**: Configuração do Prettier para formatação de código.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

Feito com ❤️ por Seu Nome