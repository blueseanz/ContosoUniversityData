# ContosoUniversityData
Getting Started with Entity Framework 6 Database First Using MVC 5

1 Create SQL Server Database Project. Open the Properties for the project and select Microsoft Azure SQL Database for the target platform. Create table and add post deployment script. 

2 Create ASP.NET Web Application and install latest EF.

3 Add ADO.NET Entity Data Model/EF Designer from database, local server=(localdb)\ProjectsV13

4 Right-click the Controllers folder, and select Add – New Scaffolded Item.

5 Change DB, Update Model from Database

6 Add Metadata Class contain all of the validation attributes to the model classes

7 Create PartialClasses that contain metadata attributes, so that it will not be lost when regenerating the model classes because the metadata attribute is applied in partial class that are not regenerated.
