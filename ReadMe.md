### A sample docker - compose project
## combination of Angular, Java and Postgres

### Steps:
1. run " docker-compose up -d "
2. run " docker-compose ps "
3. get current ip by "ipconfig getifaddr en0"
4. to access pgAdmin navigate http://192.168.1.33:8080/login?next=%2F
5. login then add server (link: https://linuxhint.com/postgresql_docker/)

    5.1. Now, to add the PostgreSQL server running as a Docker container, right click on Servers, and then go to Create > Server…
    
    5.2. In the General tab, type in your server Name.
    
    5.3. go to the Connection tab and type in pgsql-server as Host name/address, 5432 as Port, postgres as Maintenance database, admin as Username, secret as Password and check Save password? checkbox. Then, click on Save.
    
    5.4. 
    
    5.5.   
      
5. to remove all images "docker image prune -a"



Javad Talebi

cevat.talebi@gmail.com