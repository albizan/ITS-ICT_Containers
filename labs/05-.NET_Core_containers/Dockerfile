FROM  mcr.microsoft.com/dotnet/runtime

COPY app/bin/Release/netcoreapp5.0/publish/ app/

ENTRYPOINT ["dotnet", "app/myapp.dll"]