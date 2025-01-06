# Blog Pessoal

Este é um projeto desenvolvido como parte do programa da Generation Brasil, que tem como objetivo criar um sistema de blog pessoal. O projeto utiliza diversas tecnologias modernas para implementar funcionalidades de CRUD e está disponível para uso com deploy realizado pelo Render.

## 📜 Sobre o Projeto
O Blog Pessoal é uma aplicação web onde usuários podem:

- Criar, visualizar, editar e excluir postagens.
- Gerenciar temas para categorizar as postagens.
- Realizar cadastro e autenticação de usuários.

## 📂 Estrutura do Projeto
- src/main/java -> Controller: Gerencia as requisições HTTP.
- src/main/java -> Model: Define as entidades e seus atributos.
- src/main/java -> Repository: Manipula os dados no banco de dados.
- src/main/resources -> application.properties: Configurações do banco de dados e da aplicação.

## 🚀 Tecnologias Utilizadas

Linguagem: Java 17

Framework: Spring Boot

Banco de Dados: SQL

Arquitetura: RESTful API 

## 🛠️ Funcionalidades
= CRUD de Postagens: Permite Criar, Listar, Editar e Excluir Postagens;
- Gerenciamento de Temas: Relacionar postagens a temas específicos;
- Autenticação de Usuários: Controle de Acesso com segurança;
- Testes Unitários utilizando o Junit;
- Arquitetura em Camadas: Organização em Controller, Model e Repository.

## 🔧 Instalação e Configuração

1. Clone este repositório:
  ```
   git clone https://github.com/seu-repositorio/algoritmo-do-sabor.git
  ```
2. Configure o banco de dados no arquivo `application.properties` em `src/main/resources`:
  ```
  spring.datasource.url=jdbc:mysql://localhost:3306/algoritmo_do_sabor
  spring.datasource.username=seu_usuario
  spring.datasource.password=sua_senha
  ```
3. Execute o projeto:
  ```
  ./mvnw spring-boot:run
  ```

## 🛠️ Melhorias Futuras

 - Criar interface de usuário para melhorar a experiência do cliente.
 - Adicionar interações com outros usuários.

### Desenvolvido por:

- [Lucas Matheus](https://www.linkedin.com/in/lucas-matheus-lima/)
