FROM mcr.microsoft.com/dotnet/framework/samples:aspnetapp
ARG source
WORKDIR /inetpub/wwwroot/myApp
COPY ${source:-obj/Docker/Publish} .