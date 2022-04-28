# MONGODB Docker compose
Please check and change the required version of mongodb from env file.

# Starting the DB
````bash
docker-compose up -d
````

# Connecting to mongodb container
````bash
docker exec -it mongodb bash
````

# Connecting to mongodb server as admin
````bash
mongo admin -u root -p root
````

# Connecting to mongodb testdb 
````bash
mongo -u mongodb -p mongodb --authenticationDatabase testdb
````
