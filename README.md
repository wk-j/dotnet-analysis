## Code Analysis

- https://carlos.mendible.com/2017/08/24/net-core-code-analysis-and-stylecop

```
dotnet new console --language C# --output src/Hello
dotnet add src/Hello/Hello.csproj package Microsoft.CodeAnalysis.FxCopAnalyzers
dotnet add src/Hello/Hello.csproj package StyleCop.Analyzers
dotnet restore src/Hello/Hello.csproj
dotnet build src/Hello/Hello.csproj
```