### Rent A Car Project with [NArchitecture](https://github.com/kodlamaio-projects/nArchitecture) Tool

```
dotnet tool install --global NArchitecture.Gen --version 1.1.1
dotnet tool update --global NArchitecture.Gen

narchgen
narchgen new RentACarProject
narchgen generate crud
```

### Migrations
Use this commands for the `Migration Operations`:
- Create Migration
```
    PM> Add-Migration [MigrationName]
```
- Update Data   (Add Configurations)
```
    PM> Update-Database
```
- Remove Last Migration
```
    PM> Remove-Migration
```
- Drop the Database
```
    PM> Drop-Database 
```
