# ✈️ ReserVou

Aplicação web voltada para gerenciamento de reservas e experiências de viagem, com foco em organização de estabelecimentos e evolução para um sistema completo de planejamento.

---

## 🚀 Sobre o projeto

O **ReserVou** é um projeto em desenvolvimento que simula um sistema de reservas, permitindo o cadastro e listagem de estabelecimentos.

O objetivo do projeto é evoluir para uma plataforma completa de gestão de experiências de viagem, incluindo reservas, pagamentos e organização de itinerários.

Atualmente, o sistema já possui integração completa entre frontend e backend através de APIs REST.

---

## 🧠 Arquitetura

O projeto está dividido em duas camadas principais:

### 🔹 Backend
- .NET (C#)
- ASP.NET Web API
- Estrutura em camadas (Controller, Service, Repository)
- CRUD completo de estabelecimentos
- Uso de DbContext (simulado em memória)

### 🔹 Frontend
- Angular
- Angular Material
- Consumo de API REST
- Interface para cadastro e listagem de estabelecimentos

---

## ⚙️ Funcionalidades atuais

- ✅ Cadastro de estabelecimentos  
- ✅ Listagem de estabelecimentos  
- ✅ Integração completa Frontend ↔ Backend  
- ✅ API REST com operações CRUD  
- ⚠️ Persistência temporária (dados armazenados apenas em memória)  

---

## 🧪 Status do projeto

🚧 Em desenvolvimento

Atualmente o sistema utiliza armazenamento em memória, ou seja, os dados são perdidos ao reiniciar a aplicação.

---

## 🔮 Próximos passos

- 🔹 Implementação de banco de dados (SQL Server ou PostgreSQL)
- 🔹 Autenticação de usuários
- 🔹 Sistema de reservas
- 🔹 Integração com APIs externas
- 🔹 Melhorias de arquitetura e organização do código
- 🔹 Deploy em ambiente cloud

---

## 🛠️ Tecnologias utilizadas

### Backend
- C#
- .NET
- ASP.NET Web API

### Frontend
- Angular
- Angular Material
- TypeScript

### Outros
- Git & GitHub
- API REST

---

## ▶️ Como executar o projeto

### Backend

```bash
cd Reservou.Api
dotnet run
