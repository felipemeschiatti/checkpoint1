# Checkpoint 1 - Spring Boot API

Este é um projeto desenvolvido como parte de um checkpoint para a disciplina de Backend com Java e Spring Boot. A aplicação consiste em uma API REST simples para gerenciamento de uma clínica odontológica, permitindo o cadastro e consulta de dentistas, pacientes e consultas.

## Tecnologias Utilizadas

- Java 17
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 Database (banco de dados em memória)
- Lombok

##  Estrutura do Projeto

A aplicação está organizada nos seguintes pacotes:

- `model`: Contém as classes de entidade (`Paciente`).
- `service`: Camada de regra de negócio.
- `controller`: Responsável por expor os endpoints da API.
- `dto`: Objetos de transferência de dados para as requisições e respostas.


##  Funcionalidades Implementadas

### Paciente

- **POST `/pacientes`**: Cadastra um novo paciente.
- **GET `/pacientes`**: Retorna todos os pacientes cadastrados.
- **GET `/pacientes/{id}`**: Retorna um paciente por ID.
- **PUT `/pacientes/{id}`**: Atualiza os dados de um paciente.
- **DELETE `/pacientes/{id}`**: Remove um paciente do sistema.

## Documentação da API

A documentação Swagger pode ser acessada em: 
http://localhost:8080/swagger-ui/index.html


##  Como Rodar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/felipemeschiatti/checkpoint1.git

