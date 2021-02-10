# Scaffolding MS SQL Database in Dotnet Core 

![Framework](https://img.shields.io/badge/framework-.net%20core%20v3.1-green)
![Database](https://img.shields.io/badge/Database-MS%20SQL-brightgreen)

# About This
This is a project for Scaffolding DBContext in Entity Framework Core from existing MS SQL database.

# NuGet Packages
  
| NuGet Packages | Version |
| ------ | ------ |
| Microsoft.EntityFrameworkCore | 5.0.2 |
| Microsoft.EntityFrameworkCore.SqlServer | 5.0.2 |
| Microsoft.EntityFrameworkCore.Tools | 5.0.2 |

# Dependencies
  - Visual Studio 2019 | [Download](https://visualstudio.microsoft.com/downloads/)
  - Dotnet Core 3.1 | [Download](https://dotnet.microsoft.com/download/dotnet-core/3.1) |

# How to use it?
It's very simple. It's a C# class library targeting ***.net core 3.1.*** So makesure you have ***.net core 3.1 selected as target framework***.

**Step # 1 :** 
    
    Clone the repository
**Step # 2 :** 

    Select Windows Authentication from SSMS (SQL Server Management Studio)
**Step # 3 :** 
    
    Open the solution file with Visual Studio 2019
**Step # 4 :** 

    Go to ***Tools > NuGet package manger > Package Manager Console***
**Step # 5 :** 

    Run the following Command

***N.B: In case yout are not using windows authentication, use the following command***

```sh
Scaffold-DbContext "User Id=[Your User Id];Password=[Your Password];Database=[Database Name];Trusted_Connection=False;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models
```

License
----

MIT


**Free Software, Hell Yeah!**

***Tools I used to create this read me. Might also help you!***

[Shields IO](https://shields.io)
[JBT](https://jbt.github.io/markdown-editor/)
