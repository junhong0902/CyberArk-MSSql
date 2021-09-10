# MSSql with DSNless connection
```
Use default Driver: "SQL Server"
Import MSSql.zip.
Make sure the account has the nessesary information
```
![alt text](./pic/account-dsnless.jpg)

### Platform configuration
![alt text](./pic/platform.jpg)

# MSSql with DSN connection
### Pre-requisites
1. Install Microsoft® ODBC Driver 13.1 for SQL Server®
```
Always use 32bit!
https://www.microsoft.com/en-us/download/details.aspx?id=53339
```

2. Import platform via PVWA
```
Import MSSql131.zip.
```

```
Make sure the Driver parameter is correspond to the driver in ODBC setting.
```
![alt text](./pic/ODBC.jpg)

### Account configuration
```
Since this connection is using ODBC, the mandatory parameter will be only username and ODBC
```
![alt text](./pic/account.jpg)
