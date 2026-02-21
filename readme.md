# Wallet API — High-Concurrency P2P Payments

API REST backend para gerenciamento de carteiras digitais e transferências P2P com foco em consistência, concorrência e boas práticas de engenharia.

## 🔧 Tecnologias

**Backend:** Java 17, Spring Boot 3  
**DB:** PostgreSQL  
**Mensageria:** Apache Kafka  
**Testes:** JUnit 5, Mockito  
**Containerização:** Docker / Docker Compose  
**Documentação:** Swagger / OpenAPI  

---

## 🚀 Funcionalidades

- Transferências P2P com lock pessimista  
- Estratégia anti-deadlock  
- Tratamento de erros semanticamente correto  
- Endpoints seguros e validados  
- Documentação interativa via Swagger

---

## 🧠 Destaques de Engenharia

✔ Consistência de dados com `PESSIMISTIC_WRITE`  
✔ Deadlock evitado por ordenação de locks  
✔ Arquitetura orientada a eventos (Kafka)  
✔ Tratamento de exceções com ProblemDetails (RFC 7807)

---

## 📦 Executando o Projeto

🔹 Clone o repositório  
```bash
git clone https://github.com/eduardosimass/wallet-api.git
