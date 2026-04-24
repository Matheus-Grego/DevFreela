# 🚀 DevFreela

DevFreela é uma aplicação backend desenvolvida para consolidar, na prática, conceitos modernos de arquitetura e desenvolvimento utilizando o ecossistema .NET.

O projeto foi construído com foco em boas práticas amplamente utilizadas no mercado, como separação de responsabilidades, baixo acoplamento e escalabilidade.

---

## 🧠 Arquitetura e Conceitos

A aplicação segue os princípios de **Clean Architecture**, garantindo uma estrutura organizada e de fácil manutenção.

Principais abordagens aplicadas:

* **Clean Architecture**
* **CQRS (Command Query Responsibility Segregation)**
* **Injeção de Dependência (Dependency Injection)**
* **Repository Pattern**
* **Validações desacopladas com FluentValidation**

Essa estrutura permite que cada camada da aplicação tenha responsabilidades bem definidas, facilitando testes, manutenção e evolução do sistema.

---

## ⚙️ Tecnologias Utilizadas

* 🚀 ASP.NET Core
* 🗄️ Entity Framework Core
* 🐘 PostgreSQL
* 🔐 JWT (JSON Web Token)
* 📩 SendGrid (envio de e-mails)
* 🧠 MediatR
* 📦 Repository Pattern
* 🧪 xUnit (testes unitários)
* 🎭 Moq (mocking)
* 🎲 Bogus (geração de dados fictícios)
* ✅ FluentValidation

---

## 🔐 Autenticação e Segurança

O sistema utiliza autenticação baseada em **JWT**, garantindo segurança no acesso aos endpoints.

Funcionalidades implementadas:

* Login e geração de token
* Autorização baseada em roles
* Recuperação de senha via e-mail

---

## 📩 Funcionalidades Extras

* Envio de e-mails para recuperação de senha utilizando SendGrid
* Cache em memória para otimização de performance
* Geração de dados fictícios para testes

---

## 🧪 Testes

O projeto conta com testes unitários utilizando:

* xUnit
* Moq
* Bogus

Garantindo maior confiabilidade e facilitando a evolução do código.

---

## 📈 Objetivo do Projeto

Este projeto foi desenvolvido com o objetivo de:

* Aplicar na prática conceitos modernos de backend
* Reforçar conhecimentos em arquitetura limpa
* Simular um ambiente próximo ao utilizado no mercado

---

## ▶️ Como Executar o Projeto

### Pré-requisitos

* .NET SDK instalado
* PostgreSQL em execução

### Passos

```bash
# Clonar o repositório
git clone https://github.com/matheus-grego/devfreela.git

# Acessar a pasta do projeto
cd devfreela

# Restaurar dependências
dotnet restore

# Executar migrations (se aplicável)
dotnet ef database update

# Rodar a aplicação
dotnet run
```

---

## 📌 Considerações Finais

O DevFreela representa a aplicação prática de diversas tecnologias e padrões utilizados no mercado, servindo como base sólida para construção de APIs robustas, escaláveis e de fácil manutenção.

---

## 👨‍💻 Autor

Desenvolvido por Matheus Amaral
