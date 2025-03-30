## 🛒 Sistema PDV - Ponto de Venda

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)

## 📌 Sobre o Projeto

O **Sistema PDV** é uma solução robusta e eficiente para gerenciamento de vendas em estabelecimentos comerciais. Desenvolvido com **Java e Spring Boot** no back-end e utilizando **HTML e CSS** no front-end, este sistema oferece um conjunto completo de funcionalidades para otimizar o controle de vendas, estoque e pagamentos.

## 🚀 Funcionalidades

✅ Registro e gerenciamento de vendas em tempo real  
✅ Emissão de comprovantes e integração com sistemas fiscais  
✅ Controle de estoque automático e alertas de reposição  
✅ Suporte a múltiplas formas de pagamento (PIX, Cartão, Dinheiro)  
✅ Cadastro de clientes e programa de fidelidade  
✅ Relatórios detalhados de faturamento e movimentação financeira  
✅ Segurança avançada com autenticação de usuários e controle de permissões  

## 🛠️ Tecnologias Utilizadas

- **Back-End:** Java, Spring Boot, JPA/Hibernate
- **Front-End:** HTML5, CSS3
- **Banco de Dados:** MySQL
- **Segurança:** Spring Security, JWT
- **Outras Integrações:** API REST, Swagger para documentação

## 📂 Estrutura do Projeto

```
📦 sistema-pdv
 ┣ 📂 backend
 ┃ ┣ 📂 src/main/java/com/seuprojeto
 ┃ ┃ ┣ 📂 controllers
 ┃ ┃ ┣ 📂 models
 ┃ ┃ ┣ 📂 repositories
 ┃ ┃ ┣ 📂 services
 ┃ ┃ ┗ Application.java
 ┃ ┣ 📂 resources
 ┃ ┃ ┣ application.properties
 ┃ ┃ ┗ data.sql
 ┣ 📂 frontend
 ┃ ┣ 📂 assets
 ┃ ┣ 📂 css
 ┃ ┣ 📂 js
 ┃ ┗ index.html
 ┗ README.md
```

## 📥 Instalação e Execução

### 🔹 Pré-requisitos
- JDK 17+
- MySQL instalado e configurado
- Maven para gerenciamento de dependências

### 🔹 Clonando o repositório
```bash
git clone https://github.com/seuusuario/sistema-pdv.git
cd sistema-pdv
```

### 🔹 Configurando o Banco de Dados
1. Criar um banco de dados no MySQL:
```sql
CREATE DATABASE pdv_db;
```
2. Configurar o `application.properties` com suas credenciais do MySQL.

### 🔹 Executando a Aplicação
```bash
cd backend
mvn spring-boot:run
```
A API estará disponível em `http://localhost:8080`.
