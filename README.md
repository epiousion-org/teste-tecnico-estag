# Teste técnico Epiousion IT - Estagiário Backend

## Objetivo
Desenvolver uma api para gerenciamento de uma TO DO list (gerenciamento de tarefas)

### Obrigatório

- Instruções para execução da aplicação
- Funcionamento da api (mesmo que parcial)

### Recomendações

- Códigos de Resposta/Verbos HTTP corretos
- Código preferencialmente em inglês

### Diferenciais

- Logs
- Docker
- Documentação
- Conexão com banco de dados (MySQL, Postgres)

## Tecnologias

### Linguagem de programação

O sistema preferencialmente pode ser desenvolvido em:

- NodeJS (express)
- Java Spring Boot
- Python (FastAPI)
- Php

## Especificações do Teste

#### 1) Criação de Tarefas

O sistema deve permitir criação de tarefas com as seguintes propriedades: Nome, Descrição.
A tarefa deve ter um status que a defina como 'finalizada' ou 'a fazer'.
Não se esqueça de criar um identificador para cada tarefa (id)

#### 2) Lista de Tarefas

O sistema deve permitir resgatar a lista de tarefas

#### 3) Finalização de Tarefas

O sistema deve permitir alterar o status das tarefas através de seu id.
As edições devem ser: de 'a fazer' para 'finalizado', e de 'finalizado' para 'a fazer'

#### 4) Deleção de Tarefas

O sistema deve permitir deleção de tarefas através de seu id.
