# Cadastro de Pessoas - JSF + PrimeFaces + Hibernate + JPA + Wildfly

Este projeto é uma aplicação web desenvolvida em Java utilizando as tecnologias **JSF**, **PrimeFaces**, **Hibernate**, **JPA** e **Wildfly**. Ele permite realizar o **cadastro de pessoas** com **lista de documentos**, **endereços** e **contatos**, além de funcionalidades para **visualização**, **edição**, **remoção** e **pesquisa por nome**.

## 🛠 Tecnologias Utilizadas

- Java 8
- JSF 2.3
- PrimeFaces 8.0
- Hibernate 5
- JPA
- Wildfly 26
- MySQL
- Maven
- Eclipse IDE for Enterprise Java Developers

## 📋 Funcionalidades

- ✅ Cadastro de pessoas com nome, tipo, e-mail e telefone
- ✅ Inclusão de múltiplos documentos, contatos e endereços por pessoa
- ✅ Tela de **pesquisa por nome** com listagem e ações de editar, excluir e visualizar
- ✅ Tela de **visualização completa** dos dados de uma pessoa
- ✅ Validação básica nos campos obrigatórios
- ✅ Layout responsivo com PrimeFaces

## 🖼 Estrutura de Telas

1. `form.xhtml` — Tela principal de cadastro, edição e pesquisa
![image](https://github.com/user-attachments/assets/d90929a2-f62f-4c69-b8c8-1df77aabdae4)

2. `view.xhtml` — Tela de visualização dos dados completos da pessoa
![image](https://github.com/user-attachments/assets/3df94b21-6b9e-4026-a988-dd425cb6cc2f)

3. `search.xhtml` - Tela de busca
![image](https://github.com/user-attachments/assets/cb6ae23a-5427-4167-8bea-4a9eb6cd4daf)


Crie o banco de dados MySQL com o nome `crudJava`:
#MySQL
Utilize as querys do db.txt !!!


🚀 Executando o Projeto
1. Clone este repositório: git clone https://github.com/LuandxAguiar/crudJava.git
2. Importe no Eclipse como um projeto Maven existente
3. Configure o Wildfly no Eclipse e adicione o projeto ao servidor
4. Acesse: http://localhost:8080/crud/





   
