# IntegrityGuard
IntegrityGuardProject

change the name of the computer in program.cs  , for example : DESKTOP-ABCD change it to you desktop name

Download SSMS and SQL developer server

download dotnet
and inside the visual studio enter the command prompt
and write the following codes :

cd WebApp-IntegrityGuard
dotnet tool install --global dotnet-ef

then we have to migrate it to the SQL database

write the following code :

dotnet ef migrations add *ADD any name * 

then update the database in visual basic command prompt 

dotnet ef update database 
