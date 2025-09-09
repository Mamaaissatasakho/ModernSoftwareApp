# ModernSoftwareApp
[![Build](https://github.com/MamaAissataSakho/ModernSoftwareApp/actions/workflows/dotnet.yml/badge.svg)](https://github.com/MamaAissataSakho/ModernSoftwareApp/actions)


Petit projet .NET 8 pour le cours **Modern Enterprise Software Engineering** (ESTIAM).
- Application console C# + classe `Calculator`
- Tests unitaires **xUnit**
- CI **GitHub Actions** (build, test, contrôle de formatage non bloquant)
- Image **Docker**

![Build](https://github.com/<ton-user>/ModernSoftwareApp/actions/workflows/dotnet.yml/badge.svg)

## Prérequis
- .NET SDK 8
- Git
- Docker Desktop

## Lancer en local
```bash
dotnet build
dotnet test
dotnet run --project ModernSoftwareApp
