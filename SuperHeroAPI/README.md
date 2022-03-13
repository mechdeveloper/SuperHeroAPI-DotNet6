# CRUD with a .NET 6 Web API & Entity Framework Core 🚀 Full Course

## DBContext

- Install package 'Microsoft.EntityFrameworkCore'
- Install package 'Microsoft.EntityFrameworkCore.Design'
- Install package 'Microsoft.EntityFrameworkCore.sqlserver'

## Instal Entity Framework Core .NET Command-line Tools 6.0.3

`dotnet tool install --global dotnet-ef`

## Code-First Migration

```
cd .\SuperHeroAPI
dotnet ef migrations add CreateInitial
dotnet ef database update
```