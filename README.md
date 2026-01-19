# 🍲 API de Receitas

![Status](https://img.shields.io/badge/Status-Concluído-green)
![Language](https://img.shields.io/badge/Language-C%23-purple)
![Framework](https://img.shields.io/badge/.NET-6.0-blue)

Este repositório contém a solução do **projeto de backend da Trybe**, implementado como uma **API RESTful** em **C# (.NET 6 / ASP.NET Core 6)**.

O objetivo do projeto é fornecer endpoints para **gerenciar receitas, usuários e comentários**, seguindo boas práticas de **arquitetura em camadas**, **SOLID**, **Clean Code** e **RESTful API design**.

---

## 🚀 Funcionalidades

A API oferece os seguintes módulos:

### 🥘 Receitas (`Recipe`)
- Listar todas as receitas.
- Consultar uma receita pelo `name`.
- Criar novas receitas.
- Atualizar receitas existentes.
- Deletar receitas pelo `name`.

### 👤 Usuários (`User`)
- Consultar usuário pelo `email`.
- Criar novos usuários.
- Atualizar usuários existentes.
- Deletar usuários pelo `email`.

### 💬 Comentários (`Comment`)
- Criar comentários para receitas.
- Consultar comentários por `recipeName`.

---

## 🛠 Tecnologias e Boas Práticas

- **Linguagem:** C#  
- **Framework:** .NET 6 / ASP.NET Core 6  
- **Persistência:** Em memória (estrutura de objetos), facilmente adaptável para banco de dados  
- **Princípios e boas práticas aplicados:**
  - ✅ **Arquitetura em camadas:** Controllers → Services → Models
  - ✅ **RESTful API:** Endpoints padronizados com status HTTP corretos
  - ✅ **SOLID & Clean Code:** Métodos pequenos, nomes descritivos, responsabilidade única
  - ✅ **JSON:** Para comunicação cliente-servidor
  - ✅ **Validação de entradas** e tratamento de erros

---

## ⚙️ Como Rodar o Projeto

### Pré-requisitos
- [.NET 6 SDK](https://dotnet.microsoft.com/download/dotnet/6.0)
- Visual Studio 2022 ou VS Code

### Passo a Passo

1. Clone o repositório:

```bash
git clone git@github.com:guhpissai/api-de-receitas.git
cd api-de-receitas
```

2. Restaure as dependencias
```bash
dotnet restore
```

3. Executar a aplicação
```bash
dotnet run
```
