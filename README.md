# FCC_build-a-celestial-bodies-database

Command to connect to universe datase withe the user freecodecamp 
```
>> psql -U freecodecamp -d universe   
```

Command to export a database dump into a file
```
>> pg_dump -cC --inserts -U freecodecamp universe > universe.sql 
```


Commande to import a database
```
>> psql -U postgres < universe.sql 
```

psql command to log in and interact with the database. You can use it to just run a single command and exit. 
```
PSQL="psql -X --username=freecodecamp --dbname=students --no-align --tuples-only -c"
```



Command to list all object in my Pgsql
```
>> \l
```

Command to create a database
```
>> CREATE DATABASE universe;
```

Command to connect to an existing DB
```
>> \c universe
```
