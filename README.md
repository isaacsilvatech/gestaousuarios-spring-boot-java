# 👥 Sistema de Gestão de Usuários

API para gerenciamento de usuários, permitindo cadastro, consulta, atualização e remoção de registros, com autenticação e controle de acesso.

Projeto desenvolvido para fins de **estudo e prática com Spring**, aplicando boas práticas de backend.

---

## 🚀 Tecnologias Utilizadas

![Java](https://img.shields.io/badge/Java-17+-orange?style=for-the-badge&logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen?style=for-the-badge&logo=springboot)
![Spring Web](https://img.shields.io/badge/Spring%20Web-REST-green?style=for-the-badge&logo=spring)
![Spring Security](https://img.shields.io/badge/Spring%20Security-Auth-success?style=for-the-badge&logo=springsecurity)
![JWT](https://img.shields.io/badge/JWT-Security-black?style=for-the-badge&logo=jsonwebtokens)
![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-ORM-blue?style=for-the-badge&logo=spring)
![Flyway](https://img.shields.io/badge/Flyway-Migrations-red?style=for-the-badge&logo=flyway)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue?style=for-the-badge&logo=mysql)
![Lombok](https://img.shields.io/badge/Lombok-Productivity-pink?style=for-the-badge&logo=java)

---

## 📌 Funcionalidades

- Cadastro de usuários
- Consulta de usuários
- Atualização de dados cadastrais
- Ativação e inativação de usuários
- Exclusão lógica e/ou definitiva
- Autenticação com JWT
- Controle de acesso por perfil
- Validação de dados
- Versionamento de banco de dados

---

## 👤 Perfis de Usuário

- **Administrador**
  - Gerencia todos os usuários
  - Pode excluir registros definitivamente
- **Usuário Comum**
  - Pode consultar e atualizar seus próprios dados
