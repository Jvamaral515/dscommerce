# DSCommerce
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://github.com/Jvamaral515/dscommerce/blob/main/LICENSE) 
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)
## Sobre o Projeto
O DSCommerce é uma API RESTful desenvolvida em Java com o framework Spring, voltada para o gerenciamento de um sistema de comércio eletrônico. A aplicação foi projetada para atender tanto administradores quanto clientes, oferecendo funcionalidades como cadastro e controle de produtos, organização por categorias, gerenciamento de pedidos e autenticação de usuários.

A arquitetura do projeto utiliza Spring Web para o gerenciamento das requisições HTTP, Spring Data JPA para persistência e manipulação de dados em MySQL e H2 Database. A segurança é implementada com Spring Security, integrando OAuth2 Resource Server, JWT (JSON Web Token) e BCrypt para garantir autenticação segura e proteção dos dados.

O projeto foi desenvolvido utilizando as seguintes tecnologias:
- [x]  **Java**
- [x]  **Spring**
- [x]  **Spring Web**
- [x]  **Spring Boot DevTools**
- [x]  **Spring Data JPA**
- [x]  **OAuth2 Resource Server**
- [x]  **RSA**
- [x]  **JWT**
- [x]  **BCrypt**
- [x]  **MySQL**
- [x]  **H2 Database**


# Funcionalidades
- [x]  Autenticação de usuários com controle de acesso por perfis.<br>
- [x]  Perfis de cliente e administrador, com permissões específicas.<br>
- [x]  Cadastro e edição de produtos e categorias, restrito a administradores autenticados.<br>
- [x]  Listagem completa de produtos e busca por ID.
- [x]  Atualização e exclusão de produtos, disponíveis apenas para administradores logados.
- [x]  Consulta e listagem de categorias.<br>
- [x]  Criação de novos pedidos, disponíveis para usuários clientes autenticados.<br>
- [x]  Acesso aos pedidos conforme o perfil e a propriedade do usuário.<br>



# Instalação
```bash
  $ git clone https://github.com/Jvamaral515/dscommerce.git
  $ cd ./dscommerce-api

  $ mvn clean install

  $ mvn spring-boot:run
```

# Autor
João Victor Amaral Diniz de Souza

LinkedIn: https://www.linkedin.com/in/joao-victor-amaral-diniz-de-souza/
