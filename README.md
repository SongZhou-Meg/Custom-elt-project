# Custom-elt-project
Manually built elt with docker and postgres

Mainly contain the following two parts which transfer the data from source db to destination db.
1. ELT
   1) Dockerfile
   2) elt_script.py
2. Source_db_init
    1) init.sql 

docker-compose.yaml is the key file which define the process of data moving by defination of 4 parts under services: 
    1) source-postgres 
    2) destination_psotgres; 
    3) elt_script  
    4) network 
