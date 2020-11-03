# PeliculasApi

1) Crear el proyecto
2) Instalar  nuget sqlserver,tools,automapper
3)Crea una carpeta entidades con el archivo genero.cs dentro de entidad
4)En appstettings.develpoment agregar  el ConnectionStrings:""..
5)Se crea en la raiz el archivo ApplicationDbContext
6)Configura en startup.cs el services.addbContext
7)En herramientas  consola nuget el Add-Migration Initial
8)Ejectuar el Update-Database
9)Crea en controller GenerosController
10)Agregar una carpeta Helpers y crear el AutoMapperProfiles
11)Crea una carpeta con el nombre de DTOs y crear el GeneroDTO
12)Se configura el GenerosController
13)Borra el valuesController
