# Projeto Razor Pages com AdminLTE 4.0 e ASP.NET Identity

Este repositório contém um projeto desenvolvido em **Razor Pages** que utiliza o template **AdminLTE 4.0** para o layout da aplicação. Além disso, o projeto já está configurado com o **ASP.NET Identity** para gerenciamento de autenticação e autorização de usuários.

## Descrição do Projeto

O projeto foi criado com o objetivo de fornecer uma base sólida para o desenvolvimento de aplicações web utilizando o framework **Razor Pages** da Microsoft. O layout da aplicação foi configurado com o **AdminLTE 4.0**, um popular template de dashboard baseado em Bootstrap 4, que oferece uma interface moderna e responsiva.

O **ASP.NET Identity** foi integrado ao projeto para fornecer funcionalidades de autenticação e autorização, como registro de usuários, login, recuperação de senha e gerenciamento de perfis. Isso permite que a aplicação tenha um sistema de segurança robusto e personalizável.

## Funcionalidades

- **Layout AdminLTE 4.0**: Interface de usuário moderna e responsiva, com componentes pré-estilizados e prontos para uso.
- **ASP.NET Identity**: Sistema de autenticação e autorização configurado, incluindo:
  - Registro de usuários
  - Login e logout
  - Recuperação de senha
  - Gerenciamento de perfis
- **Razor Pages**: Desenvolvimento de páginas dinâmicas com a facilidade do Razor Pages.

## Pré-requisitos

Antes de executar o projeto, certifique-se de que você possui os seguintes requisitos instalados:

- [.NET SDK](https://dotnet.microsoft.com/download) (versão 6.0 ou superior)
- [Visual Studio](https://visualstudio.microsoft.com/) (recomendado) ou [Visual Studio Code](https://code.visualstudio.com/)
- [SQL Server](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads) (ou outro banco de dados compatível com Entity Framework)

## Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/joaopedro-monteiro/AdminLTE.RazorPages.git

2. **Navegue até a pasta do projeto:**
   ```bash
   cd nome-do-repositorio
   
3. **Restauração de pacotes:**
   Certifique-se de restaurar os pacotes NuGet necessários:
   ```bash
   dotnet restore
   
4. **Configuração do Banco de Dados:**
   Atualize a string de conexão no arquivo appsettings.json para apontar para o seu banco de dados.
   Execute as migrações para criar o banco de dados:
   ```bash
   dotnet ef database update
   
5. **Execute o projeto:**
   ```bash
   dotnet run
   









   
