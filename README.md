## C# Console Application Template
Bootstrapper for C# Console Apps utilizing Net 7.0 or later.

### Top-level Statements
[MSFT Learn - Top-level Statements](https://learn.microsoft.com/en-us/dotnet/core/tutorials/top-level-templates) provides high level overview
 - what statements are added by this
 - using directives
 - how to use the old program style

 More directives, args, await, namespaces in [Top-level statements - programs without Main methods](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/program-structure/top-level-statements), 2022-01


### Nullable
[MSFT Learn - Update a codebase with nullable reference types to improve null diagnostic warnings](https://learn.microsoft.com/en-us/dotnet/csharp/nullable-migration-strategies) mentions some benefits why we should use new nullable references features,
- Improved diagnostics

### How this template is generated
Create dir, create new `ConsoleApp` type project and open it in VS Code,

```Powershell
New-Item -Type Directory D:\Code\CS\CS-ConsoleApp-Template
dotnet new console --name ConsoleApp --language "C#" --output .
pushd D:\Code\CS\CS-ConsoleApp-Template
Start Code .
```
