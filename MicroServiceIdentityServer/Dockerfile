FROM microsoft/dotnet:2.1-aspnetcore-runtime
MAINTAINER yishi.chen

LABEL description="IdentityServer4"
LABEL version="1.0"

ARG identityserverport

WORKDIR /app
COPY bin/Release/netcoreapp2.0/publish/ .
EXPOSE $identityserverport
ENTRYPOINT ["dotnet","MicroServiceIdentityServer.dll"]
