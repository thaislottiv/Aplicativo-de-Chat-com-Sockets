# Aplicativo de Chat com Sockets em Java

Este projeto é uma aplicação de chat simples que permite a comunicação entre múltiplos clientes conectados a um servidor. A comunicação é feita utilizando sockets TCP/IP.

## Funcionalidades

- Conexão simultânea de múltiplos clientes ao servidor.
- Envio e recebimento de mensagens em tempo real.
- Mensagens enviadas por um cliente são recebidas por todos os outros.

## Tecnologias

- Java
- Sockets TCP/IP
- Multithreading

## Como Executar

### Servidor

1. Compile o código:
    ```bash
    javac com/thaislotti/chat/ChatServidor.java
    ```

2. Inicie o servidor:
    ```bash
    java com.thaislotti.chat.ChatServidor
    ```

### Cliente

1. Compile o código:
    ```bash
    javac com/thaislotti/chat/ChatCliente.java
    ```

2. Conecte-se ao servidor (substitua `<server-ip>` pelo IP do servidor):
    ```bash
    java com.thaislotti.chat.ChatCliente <server-ip>
    ```

Exemplo:
```bash
java com.thaislotti.chat.ChatCliente 127.0.0.1
