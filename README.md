# Sistema de Restaurante

Este é um sistema de gerenciamento de restaurante desenvolvido utilizando React para o front-end e Node.js para o back-end. O sistema possui duas interfaces principais: uma para administradores e outra para usuários normais.

## Funcionalidades

### Administrador
- **CRUD de Pratos:** O administrador pode criar, ler, atualizar e deletar pratos do cardápio.
- **Gerenciamento de Pedidos:** Visualizar e gerenciar pedidos realizados pelos usuários.

### Usuário Normal
- **Fazer Pedidos:** Usuários podem selecionar pratos e fazer pedidos.
- **Favoritar Pratos:** Usuários podem adicionar pratos aos favoritos.
- **Ver Detalhes dos Pratos:** Visualizar detalhes de cada prato.
- **Histórico de Pedidos:** Visualizar histórico de pedidos realizados.

## Tecnologias Utilizadas

- **Front-end:** React
- **Back-end:** Node.js, Express
- **Banco de Dados:** SQLite (ou outra de sua escolha)
- **Gerenciamento de Pacotes:** npm

## Instruções para Configuração

### Pré-requisitos

- Node.js instalado
- npm instalado

### Instalação

#### Front-end

1. Navegue até o diretório do front-end:
    ```sh
    cd web
    ```
2. Instale as dependências:
    ```sh
    npm install
    ```

#### Back-end

1. Navegue até o diretório do back-end:
    ```sh
    cd backend
    ```
2. Instale as dependências e realize as migrações do banco de dados:
    ```sh
    npm install && npm run migrate
    ```

### Executando o Projeto

#### Front-end

1. Navegue até o diretório do front-end:
    ```sh
    cd web
    ```
2. Execute o comando para iniciar o servidor de desenvolvimento:
    ```sh
    npm run dev
    ```

#### Back-end

1. Navegue até o diretório do back-end:
    ```sh
    cd backend
    ```
2. Execute o comando para iniciar o servidor de desenvolvimento:
    ```sh
    npm run dev
    ```
