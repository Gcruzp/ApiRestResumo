# API REST e RESTful
Introdução
Uma API REST (Interface de Programação de Aplicações baseada em Transferência de Estado Representacional) é um conjunto de normas que define como aplicativos ou dispositivos podem se conectar e comunicar entre si. Projetada para seguir os princípios de design do REST, a API REST fundamenta-se na arquitetura de Transferência de Estado Representacional (REST).

## REST vs RESTful
REST refere-se aos princípios de design que compõem uma API, enquanto RESTful é uma abordagem específica para implementar esses princípios em um sistema. Em resumo, todas as APIs REST são baseadas em RESTful, mas nem toda API RESTful adere estritamente ao REST.

## Diferenças entre REST e RESTful
A principal diferença entre REST e RESTful reside na aderência aos princípios REST. Uma API RESTful adere estritamente a esses princípios, incluindo uma interface uniforme, desacoplamento cliente-servidor, ausência de estado, capacidade de armazenamento em cache, arquitetura em camadas e, opcionalmente, código sob demanda.

## Verbos HTTP
Os métodos HTTP (também conhecidos como verbos HTTP) são utilizados em uma API REST para indicar a ação a ser executada em um recurso. Alguns dos principais métodos incluem:

GET: Recupera a representação de um recurso.
POST: Submete dados a um recurso, causando uma mudança de estado ou efeitos colaterais no servidor.
PUT: Substitui todas as representações atuais do recurso de destino pelos dados da requisição.
DELETE: Remove um recurso específico.
PATCH: Aplica modificações parciais em um recurso.
E outros, como HEAD, OPTIONS, CONNECT e TRACE.
Códigos de Status HTTP
O Código de Status HTTP é uma parte essencial da comunicação entre cliente e servidor, indicando o resultado da tentativa de solicitação. Alguns códigos comuns incluem:

2xx (Sucesso): Indica que a ação foi recebida, compreendida e aceita com sucesso.
3xx (Redirecionamento): Indica que mais ações precisam ser tomadas para completar a solicitação.
4xx (Erro do Cliente): Indica que a solicitação contém sintaxe incorreta ou não pode ser atendida.
5xx (Erro do Servidor): Indica que o servidor falhou em cumprir uma solicitação aparentemente válida.

Gabriel Cruz Pereira Viegas - 01514331
