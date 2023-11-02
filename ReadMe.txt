SQl config add the below code in appsettings
 "ConnectionStrings": {
    "BrandCS": "server=CKJ\\MSSQL;database=brandDB;Integrated Security=True;MultipleActiveResultSets = true;TrustServerCertificate=True"
  }

Make Migration-----  command  
Goto tools Nuget -> Package manager console ->
In Package managere console Just type  command --- Add-migration Initial


after that in  Pm console use command --- Update-database
