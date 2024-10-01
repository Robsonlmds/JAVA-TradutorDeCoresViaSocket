# Tradutor de Cores via Socket

Este projeto implementa um sistema de tradução de palavras relacionadas a cores utilizando comunicação de rede através de sockets.

## Classes

- **Servidor:** Escuta conexões de clientes e realiza a tradução de palavras em inglês para português.
- **Cliente:** Conecta ao servidor, envia palavras para tradução e exibe as respostas recebidas.

## Funcionamento

O aplicativo principal inicializa o servidor e permite que múltiplos clientes se conectem, enviando palavras para tradução e recebendo as respostas em tempo real. A lógica de comunicação é tratada através de sockets, garantindo a troca de mensagens eficiente e o tratamento de erros.
