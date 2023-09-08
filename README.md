# eShopWeb
# Use .Net for create website
# Hướng dẫn chạy sản phẩm : 
•	Open solution eShopSolution.sln in Visual Studio 2019 /n
•	Set startup project is eShopSolution.Data /n
•	Change connection string in Appsetting.json in eShopSolution.Data project/n
•	Open Tools --> Nuget Package Manager --> Package Manager Console in Visual Studio/n
•	Run Update-database and Enter./n
•	After migrate database successful, set Startup Project is eShopSolution.WebApp/n
•	Change database connection in appsettings.Development.json in eShopSolution.WebApp project./n
•	You need to change 3 projects to self-host profile./n
•	Set multiple run project: Right click to Solution and choose Properties and set Multiple Project, choose Start for 3 Projects: BackendApi, WebApp and AdminApp./n
•	Choose profile to run or press F5/n
