# SistemasDistribuidos

## Descrição
A ideia do projeto é desenvolver um chat online de bate papo. O sistema deverá permitir o envio e recebimento de mensagens de diversos outros clientes além de trocas informações com o servidor. 

## Cliente e Servidor
O modelo da aplicação é cliente/servidor (client/server), e os papéis são simples:

**_Servidor_**: Responsável por aguardar conexões dos clientes e ainda por conectar um cliente a vários outros.

**_Cliente_**: É uma interface desktop que se conecta ao servidor, guarda os dados da aplicação e ainda se comunica com outros clientes.

## Testes
**Teste funcional**: Verifica se os requisitos funcionais foram cumpridos, testa as funções e os casos de uso.

**Teste de usabilidade**: É um teste focado na experiencia do usúario (UX). Consiste em avaliar a interface, layout, o acesso as funcionalidades etc.

**Teste de concorrencia**: Responsável por verificar se o servidor é capaz de responder a diversas solicitações simultaneas, ou seja, vários clientes se conectando a aplicação ao mesmo tempo.

**Teste de recuperação de falhas**: Capaz de verificar a robustez e tambem a capacidade de um determinado software para retornar a um estado operacional após estar em um estado de falha.
