# API Inteligente de Orçamento Financeiro - Spring Boot + Spring AI

Projeto desenvolvido como Desafio de Projeto do Bootcamp Itaú - Java com Inteligência Artificial da DIO.

## O que o projeto faz

Uma API REST de orçamento financeiro que integra Inteligência Artificial para:
- Receber comandos de voz (áudio) via endpoint REST.
- Transcrever áudio em texto usando o modelo Whisper da OpenAI.
- Interpretar a intenção do usuário com IA (ChatClient + Tool Calling).
- Executar ações reais (criar ou listar transações financeiras no banco de dados).
- Responder em áudio (Text-to-Speech) com o resultado da operação.

## Tecnologias utilizadas

- Java 25
- Spring Boot 4.0.5
- Spring AI 2.0.0-M4 (OpenAI)
- Spring Data JPA + MySQL
- Docker Compose
- Lombok
- Gradle

## Como executar

1. Configure sua chave da OpenAI:
   export OPENAI_API_KEY="sua_chave_aqui"
