FROM microsoft/aspnetcore:2.0
ARG source
WORKDIR /app
EXPOSE 50001
COPY ${source:-obj/Docker/publish} .
ENTRYPOINT ["dotnet", "MainWeb.dll"]
