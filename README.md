# eShopWeb
# Use .Net for create website
# Hướng dẫn chạy sản phẩm : 
•	Open solution eShopSolution.sln in Visual Studio 2019
•	Set startup project is eShopSolution.Data
•	Change connection string in Appsetting.json in eShopSolution.Data project
•	Open Tools --> Nuget Package Manager --> Package Manager Console in Visual Studio
•	Run Update-database and Enter.
•	After migrate database successful, set Startup Project is eShopSolution.WebApp
•	Change database connection in appsettings.Development.json in eShopSolution.WebApp project.
•	You need to change 3 projects to self-host profile.
•	Set multiple run project: Right click to Solution and choose Properties and set Multiple Project, choose Start for 3 Projects: BackendApi, WebApp and AdminApp.
•	Choose profile to run or press F5
