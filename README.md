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

## Ambiente de Deploy

O sistema está atualmente em deploy na Vercel. Você pode acessá-lo através do seguinte link:

[Pixel Food App](https://pixel-food-app.vercel.app/)

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
   cd server
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
   cd server
   ```
2. Execute o comando para iniciar o servidor de desenvolvimento:
   ```sh
   npm run dev
   ```

## Regras de Negócio

1. **Cadastro de Pratos:** Apenas administradores podem cadastrar, editar e remover pratos.
2. **Pedidos:** Usuários podem fazer pedidos de pratos disponíveis no cardápio.
3. **Favoritos:** Usuários podem adicionar pratos aos favoritos para fácil acesso posterior.
4. **Histórico de Pedidos:** Usuários podem visualizar um histórico de todos os pedidos realizados.
5. **Gerenciamento de Pedidos:** Administradores podem atualizar o status dos pedidos.

## Cenários de Uso

### Administrador

- **CRUD de Pratos:**
  - **Criar:** Administrador acessa a página de criação de pratos, preenche o formulário com os detalhes do prato e salva.
  - **Atualizar:** Administrador acessa a página de edição de pratos, modifica os detalhes e salva.
  - **Deletar:** Administrador remove um prato da lista de pratos disponíveis.
- **Gerenciamento de Pedidos:**
  - **Visualizar:** Administrador vê a lista de todos os pedidos realizados.
  - **Atualizar Status:** Administrador atualiza o status de um pedido conforme necessário.

### Usuário Normal

- **Fazer Pedido:**
  - **Selecionar Prato:** Usuário navega pelo cardápio, seleciona os pratos desejados e faz o pedido.
- **Favoritar Prato:**
  - **Adicionar Favorito:** Usuário marca um prato como favorito para acesso rápido.
- **Ver Detalhes do Prato:**
  - **Visualizar Descrição:** Usuário vê detalhes completos de um prato, incluindo descrição, ingredientes e preço.
- **Ver Histórico de Pedidos:**
  - **Acessar Histórico:** Usuário visualiza um histórico de todos os pedidos anteriores.
  
