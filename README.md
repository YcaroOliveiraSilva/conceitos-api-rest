# conceitos-api-rest

## respostas de sucesso

As requisições consistem dos seguintes elementos:

    Um método HTTP, geralmente é um verbo como GET, POST, DELETE, PUT, etc, ou um substantivo 
    como OPTIONS ou HEAD que define qual operação o cliente quer fazer. Tipicamente, 
    um cliente que pegar um recurso (usando GET) ou publicar dados de um formulário HTML (usando POST), 
    embora mais operações podem ser necessárias em outros casos.

    O caminho do recurso a ser buscado; a URL do recurso sem os elementos que são de contexto, 
    por exemplo sem o protocolo protocol (http://), o domínio domain (aqui como developer.mozilla.org), 
    ou a porta port TCP (aqui indicada pelo 80 que é ocultado por ser o número da porta padrão)




![tab_verbos_http.jpg](https://www.matera.com/br/wp-content/uploads/2016/03/tab_verbos_http.jpg)



## status code

##### Os códigos de status das respostas HTTP indicam se uma requisição HTTP foi corretamente concluída. As respostas são agrupadas em cinco classes:

    Respostas de informação (100-199),
    Respostas de sucesso (200-299),
    Redirecionamentos (300-399)
    Erros do cliente (400-499)
    Erros do servidor (500-599).

![tab_status_code1.jpg](https://www.matera.com/br/wp-content/uploads/2016/01/tab_status_code1.jpg)


## visão http


HTTP é um protocolo (protocol) que permite a obtenção de recursos, tais como documentos HTML. 
É a base de qualquer troca de dados na Web e um protocolo cliente-servidor, 
o que significa que as requisições são iniciadas pelo destinatário, geralmente um navegador da Web. 
Um documento completo é reconstruído a partir dos diferentes sub-documentos obtidos, 
como por exemplo texto, descrição do layout, imagens, vídeos, scripts e muito mais.

Clientes e servidores se comunicam trocando mensagens individuais (em oposição a um fluxo de dados). 
As mensagens enviadas pelo cliente, geralmente um navegador da Web, são chamadas de solicitações 
(requests), ou também requisições, e as mensagens enviadas pelo servidor como resposta são 
chamadas de respostas (responses).

![visaoHTTP.png](https://media.prod.mdn.mozit.cloud/attachments/2016/08/09/13677/d031b77dee83f372ffa4e0389d68108b/Fetching_a_page.png)


![HTTP & layers.png](https://media.prod.mdn.mozit.cloud/attachments/2016/08/09/13673/6d339b54f6873b97728986a2d9d930dd/HTTP%20%26%20layers.png)




## Componentes de sistemas baseados em HTTP


HTTP é um protocolo (protocol) que permite a obtenção de recursos, tais como documentos HTML. 
É a base de qualquer troca de dados na Web e um protocolo cliente-servidor, 
o que significa que as requisições são iniciadas pelo destinatário, geralmente um navegador da Web. 
Um documento completo é reconstruído a partir dos diferentes sub-documentos obtidos, 
como por exemplo texto, descrição do layout, imagens, vídeos, scripts e muito mais.

Clientes e servidores se comunicam trocando mensagens individuais (em oposição a um fluxo de dados). 
As mensagens enviadas pelo cliente, geralmente um navegador da Web, são chamadas de solicitações 
(requests), ou também requisições, e as mensagens enviadas pelo servidor como resposta são 
chamadas de respostas (responses).

![Client-server-chain.png](https://media.prod.mdn.mozit.cloud/attachments/2016/08/09/13679/f99e6e5172b5911ac594f7a7395797b0/Client-server-chain.png)



## Requisições



Exemplo de uma requisição HTTP:

A basic HTTP request

As requisições consistem dos seguintes elementos:

    Um método HTTP, geralmente é um verbo como GET, POST, DELETE, PUT, etc, ou um substantivo 
    como OPTIONS ou HEAD que define qual operação o cliente quer fazer. Tipicamente, 
    um cliente que pegar um recurso (usando GET) ou publicar dados de um formulário HTML (usando POST), 
    embora mais operações podem ser necessárias em outros casos.

    O caminho do recurso a ser buscado; a URL do recurso sem os elementos que são de contexto, 
    por exemplo sem o protocolo protocol (http://), o domínio domain (aqui como developer.mozilla.org), 
    ou a porta port TCP (aqui indicada pelo 80 que é ocultado por ser o número da porta padrão)

    A versão do protocolo HTTP.

    Cabeçalhos opcionais que contém informações adicionais para os servidores.
    Ou um corpo de dados, para alguns métodos como POST, similares aos corpos das respostas, que contém o recurso requisitado.




![HTTP_Request.png](https://media.prod.mdn.mozit.cloud/attachments/2016/08/09/13687/5d4c4719f4099d5342a5093bdf4a8843/HTTP_Request.png)





## Respostas

 Exemplo de resposta HTTP:

Respostas consistem dos seguintes elementos:

    A versão do protocolo HTTP que elas seguem.
    Um código de status, indicando se a requisição foi bem sucedida, ou não, e por quê.
    Uma mensagem de status, uma pequena descrição informal sobre o código de status.
    Cabeçalhos HTTP, como aqueles das requisições.
    Opcionalmente, um corpo com dados do recurso requisitado.



![HTTP_Response.png](https://media.prod.mdn.mozit.cloud/attachments/2016/08/09/13691/58390536967466a1a59ba98d06f43433/HTTP_Response.png)
