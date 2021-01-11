# Dev Oops

Yeah, I'm not having a typo mistake, it should be a dev oops rather than DevOps.
I've initalized this repo for storing everything I want to take notes while studying about DevOps.

## Docker Compose Usage

You should update the env file correspond to your configuration
Then run

```bash
docker-compose up
```

The input db host for TeamCity will be: SQLServer:1433
Instance: please keep it blank, by default the SQL Server container has been up using Developer Edition
Using SSMS or sqlcommand if you would to create a new database name TeamCity or what ever you like. Then input to Database name field
Use authenticate mode by login & password
