# 🍕 ContosoPizza Razor Pages

Uma aplicação web completa desenvolvida com **ASP.NET Core Razor Pages**, projetada para gerenciar o catálogo e pedidos de uma pizzaria. Este projeto foi realizado através da documentação do **Microsoft Learn** para aprofundamento em Server-Side Rendering (SSR) e persistência de dados.

---

<div align="center">
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/Razor%20Pages-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="Razor Pages">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
</div>

---

## 📌 Funcionalidades
- [x] **Gestão de Inventário:** CRUD completo (Criar, Ler, Atualizar e Deletar) de pizzas.
- [x] **Interface Dinâmica:** Renderização de componentes via Razor Pages.
- [x] **Persistência:** Integração com banco de dados para salvar informações entre sessões.

## 🛠️ Tecnologias e Conceitos
* **ASP.NET Core Razor Pages:** Arquitetura focada em páginas para facilitar o desenvolvimento web.
* **Entity Framework Core:** Utilizado para a abstração da camada de banco de dados.
* **SQLite:** Banco de dados leve e autocontido para desenvolvimento local.
* **Bootstrap:** Para estilização e responsividade da interface.

## 📂 Estrutura Principal
* `Pages/Pizzas/`: Contém a lógica de negócio e as views para o gerenciamento das pizzas.
* `Models/`: Definição das entidades (Pizza, etc).
* `Services/`: Camada de serviço para isolar a lógica de acesso a dados.

## 🚀 Como Começar

### Pré-requisitos
* [.NET SDK](https://dotnet.microsoft.com/download) instalado (Versão 7.0 ou superior).

### Instalação e Execução
1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/jamerson-mt/ContosoPizzaRazorPages.git](https://github.com/jamerson-mt/ContosoPizzaRazorPages.git)
   cd ContosoPizzaRazorPages
