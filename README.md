# Tradutor de Cores via Socket

Este projeto consiste em um sistema de tradução de palavras relacionadas a cores, utilizando comunicação de rede através de sockets. O servidor aguarda conexões de clientes e traduz palavras em inglês para português, utilizando um dicionário simples. O cliente se conecta ao servidor, envia uma palavra para tradução e exibe a resposta recebida. Este sistema exemplifica a interação entre cliente e servidor, enfatizando a troca de mensagens e o tratamento de erros durante a comunicação.

## Estrutura do Código:

### Classes:

- **Client:** Estabelece uma conexão com o servidor, envia uma solicitação de tradução e imprime a resposta.
- **Attendant:** Thread responsável por gerenciar a comunicação com o cliente.
- **Server:** Escuta na porta especificada e aceita conexões de clientes.

## Técnicas Utilizadas:

- **Sockets:** Comunicação de rede via TCP.
- **Threads:** Gerencia múltiplas conexões simultâneas.
- **Mapas:** Armazena pares de tradução de forma eficiente.
