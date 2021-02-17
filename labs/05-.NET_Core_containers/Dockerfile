FROM mcr.microsoft.com/dotnet/core/runtime:3.1

COPY app/bin/Release/netcoreapp5.0/publish/ app/

ENTRYPOINT ["dotnet", "app/myapp.dll"]