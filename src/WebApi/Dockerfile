FROM microsoft/aspnetcore:1.0.1
ENTRYPOINT ["dotnet", "WebApi.dll"]
ARG source=.
WORKDIR /app
EXPOSE 5000
COPY $source .
