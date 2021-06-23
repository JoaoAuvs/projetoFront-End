## Front-end Sistema de Gestão de Ambientes

O SG-Ambientes é uma solução web com o propósito de gerir a segurança e o controle de acesso dos usuários aos ambientes educacionais. A aplicação foi estruturada em um módulo web e outro embarcado. A aplicação possibilita manter as informações dos ambientes (localizaçao física, tipos de ambiente, capacidade pessoas suportadas), o acionamento remoto dos equipamentos instalados no ambiente (luzes, ar condicionado, datashow e multimídia) e o controle acesso por RFID dos usuários autorizados. O módulo embarcado permitirá a liberação da porta do ambiente mediante a autenticação por RFID. A aplicação foi implementada em Java, utilizando o Framework Spring Boot, Spring Security, Angular e Ionic.

## Tecnologias

- node: 14.16.0
- ionic cli: 6.13.1
- angular cli: 11.2.4

## Como instalar

- Baixe ou clone este repositório usando `git@github.com:JoaoAuvs/projetoFront-End.git`.
- Dentro do diretório, execute `npm install @ionic-native/native-storage` para instalar as dependências.

## Como executar

- Dentro do diretório, execute ionic serve para executar a versão de desenvolvimento.
