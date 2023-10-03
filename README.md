# tiendacampus2023netcore
El proyecto visto en el repositorio es elaborado por: Elba Garcia y Giovanni Balza Muñoz.
Este proyecto esta basado en la arquitectura de una aplicacion, a traves de (Appplication Programming Interface) el cual permite a diferentes aplicaciones o sistemas interactuar con el protocolo HTTP.
Durante la creacion de este proyecto se crearon migraciones de datos, haciendo uso de entity framework.
Tambien podemos observar el uso de entidades, por ello la carpeta entities.
Paquetes que usamos: Microsoft.EntityFrameworkCore, PomeloEntityFrameworkCoreMysql.
Realizamos diferentes clases y la mas importante clase de contexto, la cual se usa para la conexion a la base de datos.(TiendaContext)Esta carpeta se
encuentra en Infraestructura en una carpeta interna(Data), TiendaContext heredara de otra clase DbContext, la cual permanece al Entity Framework Core.
Para la conexion de base de datos, debemos crear depencias las cuales se haran en Programs.cs de la carpeta API, para finalizar la configuracion de base de datos, se crea una variable de conexion
en el archivo appsettings.Development.json.
En este proyecto tambien agregamos metodos y repositorios para poder manipular, acceder, almacenar datos.

pdta: Este proyecto se ejecuta en consola MySql.
