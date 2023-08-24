FROM microsoft/aspnetcore:2.0 AS base
WORKDIR /app
EXPOSE 5000
COPY . .
ENTRYPOINT ["dotnet", "netcoretest.dll"]