# BlazorPlay
Experimenting with Blazor.
Hosting using VSCode Azure App Service extension.
Have to install aspnetcore 3 preview extension (x86) on azure app service.

to deploy:
from .Server folder run: dotnet publish -c Release
then use azure to publish /bin/release/netcoreapp3.0/publish folder
