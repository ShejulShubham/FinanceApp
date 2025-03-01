# Finance App
The Finance app is build using DotNET MVC.

### Steps to run the app
first open the project in Visual Studio code 

Step 1: setup the database query in appsettings.json file.
```json
    "ConnectionStrings": {
        "defaultConnectionString": "your_connection_string"
    }
```

Step 2: go to Tools->NuGet package manager->Package manager console and enter following command

```console
    Add-Migration InitialCreate
```

```console
    Update-Database
```

Step 3: go to FinanceApp folder and open terminal then run following command
```terminal
    dotnet run
    dotnet watch run
```

### Still from the website

![One](/FinanceApp/Public/FinanceApp%20(1).png)
![Two](/FinanceApp/Public/FinanceApp%20(2).png)