# Introduction 
API to register or login with Net Core 5, jwt.  
This API is set to be consumed by repo login-register-react-redux-ui  

# Details
Net Core 5 API  
Entity Framework Core  
SQL Server  

# Setup
Run scripts on project "Database" in SQL Management.  
Replace "nameofyourdb" with your own db name.  
Update connection strin in API/appsettings.json

# Projects in solution
API - Main Project. It contains the api controllers.    
Database - Scripts to be run in SQL Management  
Domain - It contains the entities  
Models - It contains view models  
Repository - It contains the Data context neccesary for Entity Framework. If you apply the repository and the Unit of work patterns, the correspondent interfaces and classes should be here.  

