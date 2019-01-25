# Project Template
These are key files needed in each project

1. docker-compose.yml
Creates three services Jupyter, PostgresDB, and PGLOADER to get postgres loaded. 
2. .dockerignore
ensures that large files aren't loaded into the docker context. 
3. sqlite3.load is a sample file that loads data into the postgres via pgloader. note that the database needs to be found at /src in the dockercontainer and . in host. 

make sure the PGPASSWORD environment variable is set. 

