# ✅ SistemaDeTarefas - API REST em C# com .NET

## 📌 Sobre o Projeto

Este projeto é uma API REST desenvolvida em **C#** utilizando o **.NET Core**, com o objetivo de gerenciar tarefas e usuários de forma prática e escalável.  

Faz parte do estudo e prática de conceitos como criação de endpoints, manipulação de dados com **Entity Framework**, e persistência com **SQL Server**.

---

## ⚙️ Tecnologias Utilizadas

- 💻 **C#**
- 🚀 **.NET Core 6**
- 🌐 **ASP.NET Core Web API**
- 🗂 **Entity Framework Core**
- 🛢 **Microsoft SQL Server**

---

## 🛠️ Estrutura da Aplicação

A API segue os princípios REST e possui as seguintes entidades principais:

### 📋 Tarefa

| Campo     | Tipo          | Descrição                |
|-----------|---------------|--------------------------|
| Id        | int           | Identificador único      |
| Nome      | string        | Nome da tarefa           |
| Descricao | string        | Descrição detalhada      |
| Status    | StatusTarefa  | Status atual da tarefa   |

### 👤 Usuário

| Campo | Tipo   | Descrição            |
|-------|--------|----------------------|
| Id    | int    | Identificador único  |
| Nome  | string | Nome do usuário      |
| Email | string | E-mail do usuário    |

---

## 🔗 Endpoints da API

- `GET /api/Usuario` → Listar todos os usuários  
- `GET /api/Usuario/{id}` → Buscar usuário por ID  
- `POST /api/Usuario` → Cadastrar novo usuário  
- `PUT /api/Usuario/{id}` → Atualizar usuário existente  
- `DELETE /api/Usuario/{id}` → Remover usuário  

---

## 🧩 Repositórios e Contexto

- O projeto utiliza **EF Core** para mapear as entidades e acessar o banco de dados.
- O mapeamento é feito nas classes `UsuarioMap` e `TarefaMap`.
- O contexto principal é definido em `SistemaDeTarefasDbContext`.

---

## 🔧 Configuração Inicial

Antes de rodar o projeto, verifique:

- ✅ **.NET SDK 6 ou superior** instalado  
- ✅ Configuração da **string de conexão** no arquivo `appsettings.json`  
- ✅ Banco de dados SQL Server disponível

---

## 🚀 Executando o Projeto

1. Abra o projeto no **Visual Studio 2022** (ou superior).
2. Restaure os pacotes NuGet, se necessário.
3. Certifique-se de que o projeto da API está como **Startup Project**.
4. Pressione `F5` ou clique em **Iniciar** para executar.

---

## 🧪 Testes com Swagger

Assim que o projeto for iniciado, a interface do **Swagger** será aberta automaticamente no navegador.

- Use o Swagger para testar todos os endpoints de forma prática e interativa.

---

## ✅ Pronto!

A API estará disponível localmente e pronta para uso.  
Sinta-se à vontade para explorar, testar e evoluir este projeto conforme seus aprendizados! 🚀

📸 Screenshot

![swagger](https://github.com/user-attachments/assets/3967182c-cb57-4a04-bae8-f374584e38b2)

