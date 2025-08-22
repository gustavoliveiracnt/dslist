# DSList Backend – Java Spring

Projeto desenvolvido durante o curso intensivo de Java e Spring Boot, que implementa uma API REST para gerenciar jogos e listas de jogos.

## Modelo Conceitual do Projeto
<img width="824" height="290" alt="image" src="https://github.com/user-attachments/assets/c7c9d3ee-037d-4110-9c45-9b50ef4c0492" />

## Tecnologias Utilizadas
- Java 21, Spring Boot, Spring Data JPA, Hibernate, Maven
- Banco: H2

## Estrutura
- DTOs, Repositories, Services, Controllers bem organizados
- Coleção Postman incluída para facilitar testes

## Endpoints

| Método | Endpoint                                | Descrição                                   |
|--------|-----------------------------------------|---------------------------------------------|
| GET    | `/lists`                                | Retorna todas as listas de jogos            |
| GET    | `/lists/{listId}/games`                 | Retorna os jogos de uma lista específica    |
| GET    | `/games/{id}`                           | Retorna os detalhes de um jogo              |
| PUT    | `/lists/{listId}/replacement`           | Atualiza a posição de um jogo na lista      |

## Execução
```bash
git clone ...
cd dslist-backend
./mvnw spring-boot:run
```

