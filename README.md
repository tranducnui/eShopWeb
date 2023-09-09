# eShopWeb
# Use .Net for create website
# Hướng dẫn chạy sản phẩm : 
=>	Mở project trên Visual Studio 2019/2022
=>	Set startup project là eShopSolution.Data 
=>	Đổi connection string trên file Appsetting.json tại eShopSolution.Data project
=>	Open Tools --> Nuget Package Manager --> Package Manager Console in Visual Studio
=>	Chạy lệnh: Update-database và Enter.
=>	Sau khi migrate database successful, set Startup Project là eShopSolution.WebApp
=>	Thay đổi database connection trong file appsettings.Development.json ở eShopSolution.BackendApi project.
=>	Thay đổi 3 projects chạy self-host profile.
=>	Set multiple run project: Chuột phải vào Solution và chọn Properties và set Multiple Project, chọn Start lần lượt 3 Projects: BackendApi, WebApp and AdminApp.
=>	Choose profile to run hoặc ấn F5
