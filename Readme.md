# Projeto ASP.NET 5.0 - Controle de Contatos

## Descrição
Este projeto é uma aplicação web desenvolvida em ASP.NET 5.0 para gerenciamento de contatos.

## Pré-requisitos
- [.NET SDK 5.0](https://dotnet.microsoft.com/download/dotnet/5.0)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) (ou equivalente)

cd SistemaDeContatos

dotnet ef migrations add InitialCreate
dotnet ef database update

dotnet run