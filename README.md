# specflow-example

dotnet new sln -n specflow-example
dotnet new mstest -n specflow-example.test
dotnet sln add ./specflow-example.test/specflow-example.test.csproj

dotnet add package SpecFlow --version 3.0.213 