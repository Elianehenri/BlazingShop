# BlazingShop


## Descrição

O BlazingShop é um projeto desenvolvido em Blazor Server que oferece funcionalidades para o cadastro de produtos e categorias utilizando um banco de dados SQL Server.

##Requisitos do Ambiente

- [Visual Studio](https://visualstudio.microsoft.com/) (Versão 2022 ou posterior)
- [.NET SDK](https://dotnet.microsoft.com/download/dotnet) (Versão 7.0 ou posterior)
- [SQL Server](https://www.microsoft.com/sql-server/)

## Configuração do Projeto

1. Clone este repositório para o seu ambiente local.
   ``` git clone https://github.com/Elianehenri/BlazingShop.git ```
2. Execute `dotnet restore` para restaurar as dependências.
3. Execute as migrações do Entity Framework Core com `dotnet ef database update`.
4. Execute o projeto com `dotnet run`.
## Configuração do Banco de Dados

O banco de dados é configurado no arquivo `appsettings.json`. Substitua os valores apropriados para a conexão com o seu servidor SQL.

```json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=seu-servidor-sql;Database=NomeDoBancoDeDados;User Id=seu-usuario;Password=sua-senha;"
  },
  
}
````
 #
### Autor
* **Eliane Henriqueta**
