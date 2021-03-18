1. create Models
2. create class PaymentDetail + Context in Models
3. write model
4. install manage nuget package 
	EntityFrameworkCore
	EntityFrameworkTools
	EntityFrameworkCore.Sqlserver
5. write Payment context
	short letter -> ctor
6. write Startup
	add service -> useSqlServer
7. write appsetting.json -> connectionString 
8. add connectionString -> useSqlServer -> Startup.cs
9. open tools -> Nuget package -> console
10. write in nuget console -> create migration
	Add-migration "Name Migration" -> create migration
	Update-Database -> build db
11. install CodeGeneration.Design + CodeGeneration.Utils
12. create Controller
13. add cors in Startup.cs
	services.AddCors() in ConfigureServices
	app.UseCors in Configure
	
