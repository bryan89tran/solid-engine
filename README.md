# solid-engine


### Initialize the default migration
```
PM > update-database
```

Note: Databse will be created but with a hashed time stamp
Option: Go to MS SQL Server and change the name to match the string in the appsetting.json
```json
// Example
{
    ConnectionStrings: {
        "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=aspnet-GraniteHouse-F9473BAB-38D1-489D-92AE-0F24B4E00F12"
        "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=GraniteHouse"
    }
}

```
