# Tradutor de Cores via Socket

## Estrutura do Código:

### Classes:

- **Client:** Estabelece uma conexão com o servidor, envia uma solicitação de tradução e imprime a resposta.
- **Attendant:** Thread responsável por gerenciar a comunicação com o cliente, recebendo a palavra a ser traduzida e enviando a resposta.
- **Server:** Escuta na porta especificada, aceita conexões de clientes e delega a comunicação a instâncias da classe Attendant.

## Técnicas Utilizadas:

- **Sockets:** Implementação de comunicação de rede via TCP utilizando Socket e ServerSocket.
- **Threads:** Uso de threads para gerenciar múltiplas conexões simultâneas com clientes, permitindo que o servidor atenda várias solicitações.
- **Mapas:** Utilização de HashMap para armazenar pares de tradução (inglês-português) de forma eficiente.
