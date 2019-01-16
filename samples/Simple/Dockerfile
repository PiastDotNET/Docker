FROM microsoft/dotnet:2.1-sdk

COPY . /source/

WORKDIR /source/

RUN dotnet build

ENV ASPNETCORE_URLS="http://+:5000"
ENV ASPNETCORE_ENVIRONMENT Production

ENTRYPOINT dotnet run