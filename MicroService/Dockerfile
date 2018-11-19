FROM microsoft/dotnet:2.1-aspnetcore-runtime
MAINTAINER yishi.chen

LABEL description="microservice"
LABEL version="1.0"

ARG microport

WORKDIR /app
COPY bin/Release/netcoreapp2.0/publish/ .
EXPOSE $microport
ENTRYPOINT ["dotnet","MicroService.dll"]
