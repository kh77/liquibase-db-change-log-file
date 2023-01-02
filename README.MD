## Generate changelog for exisiting database using Liquibase

- Install liquibase cli

- Go to liquibase.properties file

- change databasename, username, password for the specific database

- provide jar file eg: sqlserver jar is exist in this example

- 'changeLogFile' specify any name of dbchangelog, change extension to generate specific format like json,xml,yaml etc eg: dbchangelog.xml 

- Run this command -> liquibase generateChangeLog

- It will generate change log file.

