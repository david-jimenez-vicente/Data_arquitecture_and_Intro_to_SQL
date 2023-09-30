## Repositorio para "Modelado de Base de Datos e Introducción a SQL"
## Repository for "Database Model Design and Intro to SQL" subject
---
### *Contenido del repositorio*  
· 'Flota_DJ.drawio': Diagrama Entidad-Relación en formato nativo para el software Draw.IO  
· 'Flota_DJ.pdf' *y* 'Flota_DJ.html': El diagrama E-R en formatos de amplia compatibilidad, para ver sin
software específico.  
· 'Flota_DJ.sql': Script SQL para creación, población y consulta automáticos de la base de datos.  
### *Repository content*  
· 'Flota_DJ.drawio': Entity-Relationship using Draw.IO native file format.  
· 'Flota_DJ.pdf' *and* 'Flota_DJ.html': The E-R diagram in wide compatibility formats, to be used as standalone.  
· 'Flota_DJ.sql': SQL script to auto create, populate and query the database.

---  

### *Descripción del proyecto*
· Este es el proyecto final de la asignatura de "Modelado de Datos e Introducción a SQL".
En él he creado una nueva base de datos con código manualmente para gestionar una flota de vehículos
de una empresa. La base usada ha sido PostgreSQL.  
· El responsable necesita hacer un seguimiento de los datos técnicos de los vehículos con sus registros
de mantenimiento regular y con los datos de su seguro obligatorio.  
· Esta necesidad crea tres bloques de información semánticamente diferenciados.  
· Para realizar el diseño del esquema de Entidad-Relación se ha usado el software y WebApp gratuíto Draw.IO:
https://app.diagrams.net , que puedes usar gratuíta e inmediatamente para abrir el archivo .drawio.
Además de la agrupación por semántica, se ha realizado una Normalización exhaustiva en el diseño.  
· Tras el diseño del esquema, se ha usado el software de gestión de bases de datos DBeaver CE para crear
un servidor PostgreSQL y crear y ejecutar el script SQL. Puedes usar tu cliente SQL favorito para ejecutarla.


### *Project description*  
· This is the final poject for the "Data arquitecture and Intro to SQL" subject. I modeled a new database
manually coding to manage a business vehicle fleet. Done using PostgreSQL.  
· The corresponding manager needs to track the technical data of the vehicles, their periodical maintenance
data and their mandatory assurance info.  
· This needs create three blocks of information semantically differentiated.  
· To design the Entity-Relationship scheme, the Draw.IO free desktop app and WebApp has been used: https://app.diagrams.net,
that you can free and instantly use it to open the .drawio file.
In addition to grouping by semantics, exhaustive Normalization has been carried out in the design.  
· After designing the schema, DBMS DBeaver CE has been used to implement and to create the SQL server and create and run the script.
You can use your favorite SQL client.
