# issue: wpf consumes huge memory vs winform

```pwsh
dotnet new wpf -o testwpf
dotnet new winforms -o testwinform

dotnet new sln
dotnet new gitignore

dotnet sln add --in-root testwpf
dotnet sln add --in-root testwinform

dotnet build
```

then run these two apps and abserve the memory consumption from task manager

![image](https://github.com/ali50m/TestApp/assets/9393831/afa57539-8bff-45a4-b46a-e78dcabbb45c)

![image](https://github.com/ali50m/TestApp/assets/9393831/79d40c9d-da52-4505-ba54-f7ee21906c31)
