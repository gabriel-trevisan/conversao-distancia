# conversao-distancia

Este desafio visa desenvolver habilidades em contêinerização usando Docker para uma aplicação de conversão de distância.

## Cenário

A **FakeShop** está em um processo de modernização e migrando suas aplicações para contêineres para otimizar a escalabilidade e padronizar ambientes. Você faz parte da equipe responsável por essa modernização, e sua tarefa inicial é configurar um ambiente Docker para uma aplicação de conversão de métricas de distância (metros para quilômetros, milhas para metros, entre outras). A aplicação foi desenvolvida em Python.

## Objetivo do Desafio

O desafio consiste em usar Docker para executar um ambiente piloto para a aplicação de conversão de distâncias, verificando o funcionamento básico e distribuindo a imagem em um repositório Docker.

---

## Tarefas do Desafio

### 1. Configuração do Ambiente

1. **Fork do Repositório**:
   - Realize um **fork** do repositório original e clone o repositório do GitHub: [KubeDev/conversao-distancia](https://github.com/KubeDev/conversao-distancia).

2. **Criação do Dockerfile**:
   - No repositório, crie um **Dockerfile** que atenda aos requisitos da aplicação, permitindo que ela seja executada dentro de um contêiner Docker.

### 2. Criação e Teste do Contêiner

1. **Geração da Imagem Docker**:
   - Crie uma imagem Docker a partir do Dockerfile que você configurou.

2. **Execução do Contêiner**:
   - Execute um contêiner a partir da imagem gerada. A aplicação deverá estar acessível na **porta 5000**.

3. **Testes de Funcionalidade**:
   - Realize testes básicos para verificar se a aplicação está funcionando e realizando corretamente as conversões de métrica de distância.

### 3. Distribuição do Contêiner

1. **Publicação da Imagem**:
   - Publique a imagem gerada em um repositório Docker (Docker Hub ou outro de sua escolha).

2. **Envio para Verificação**:
   - Envie o link do repositório Docker para que a equipe de verificação possa acessar a imagem e avaliar o seu trabalho.