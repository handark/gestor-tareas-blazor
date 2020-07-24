# Gestor de Tareas
## Aplicación creada con Blazer para uso didactico

## Crear una nueva app enm Blazer

dotnet new blazorserver -o GestorTareasBlazor --no-https

## Ejecutar

dotnet watch run

## Crear componente

dotnet new razorcomponent -n NombreComponente -o Pages

## Generar release

dotnet publish -c Release

## Deploy en Vercel

npm i -g vercel
vercel login
cd bin/Release/netcoreapp3.1/publish/wwwroot