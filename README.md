# 💸 PulsePay Gateway

Um projeto de **Gateway de Pagamento** simulado, construído com foco em **Clean Architecture + CQRS**, utilizando **.NET 8**, **Entity Framework Core InMemory**, **Swagger**, **MediatR** e boas práticas de arquitetura de software.

---

## 📚 Objetivo

Este projeto foi criado com fins educacionais e demonstra como construir um **Gateway de Pagamento desacoplado**, escalável e testável. O comportamento do provedor de pagamento é **simulado com mocks**, permitindo o estudo de padrões como:

- Clean Architecture
- CQRS (Command & Query Responsibility Segregation)
- Strategy + Factory
- Dependency Injection
- Manipulação assíncrona com `async/await`
- Tratamento de erros e responses padronizados

---

## 🧠 Tecnologias Utilizadas

| Tecnologia          | Finalidade                                |
|---------------------|--------------------------------------------|
| ASP.NET Core 8      | Web API REST                              |
| EF Core InMemory    | Persistência simulada                     |
| MediatR             | Gerenciamento de comandos e queries (CQRS)|
| Swagger / Swashbuckle | Documentação e testes de API            |
| AutoMapper          | Mapeamento entre DTOs e Entidades         |

---

## 🧪 Funcionalidades Simuladas

- [x] Criar pagamento
- [x] Selecionar forma de pagamento (Pix, Cartão)
- [x] Estratégias de pagamento com retorno fake
- [x] Retorno padronizado (`Result<T>`)
- [x] Persistência em memória
- [x] Swagger para testes
- [x] Handler para comandos e queries com MediatR

