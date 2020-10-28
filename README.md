# ZLARA

setting pertama kali :  
1. update composer  
`docker-compose run --rm -w /app web composer update`  
2. belum ada info...  
3. apalagi 3 tambah belum ada...  

run container  
`docker-compose up -d`  

coba buka http://localhost:1187  

stop container  
`docker-compose down`  

cara masuk ke shell container (new container auto destroy)  
`docker-compose run --rm web /bin/bash`  

cara masuk ke shell container  
`docker exec -it zlara /bin/bash`  


