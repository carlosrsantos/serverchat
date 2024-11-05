# ServerChat - Chat em Tempo Real com SignalR

Este é um exemplo simples de uma aplicação de chat em tempo real utilizando [SignalR](https://dotnet.microsoft.com/apps/aspnet/signalr) e [ASP.NET Core](https://dotnet.microsoft.com/apps/aspnet). A aplicação permite que clientes se conectem ao servidor e troquem mensagens instantaneamente por meio de WebSockets, permitindo a criação de sistemas de chat em tempo real.

## Requisitos

- [.NET 6 ou superior](https://dotnet.microsoft.com/download)
- [Node.js](https://nodejs.org/) (caso você queira testar com um cliente front-end)

## Descrição

A aplicação é composta por uma API que utiliza o SignalR para gerenciar as conexões de chat. O servidor SignalR é configurado para aceitar requisições apenas de um cliente específico (no caso, `http://localhost:3000`) para fins de segurança.

### Funcionalidades

- Conexão via SignalR com o servidor de chat.
- Comunicação bidirecional em tempo real entre cliente e servidor.
- Configuração de CORS para permitir requisições do front-end local (`localhost:3000`).

## Como rodar a aplicação

### 1. Clonando o repositório

Se ainda não fez, clone este repositório:

```bash
git clone https://github.com/carlosrsantos/serverchat.git
cd <diretório-do-repositório>
```

### 2. Baixar dependências do código:

```
dotnet restore
```

### 3. Executar a aplicação:

```
dotnet run
```
