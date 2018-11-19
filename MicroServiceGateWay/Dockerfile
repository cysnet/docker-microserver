FROM microsoft/dotnet:2.1-aspnetcore-runtime
MAINTAINER yishi.chen

LABEL description="GateWay"
LABEL version="1.0"

ARG gatewayport

WORKDIR /app
COPY bin/Release/netcoreapp2.0/publish/ .
EXPOSE $gatewayport
ENTRYPOINT ["dotnet","MicroServiceGateWay.dll"]
