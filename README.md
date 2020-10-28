# ZLARA

setting pertama kali :  
1. update composer  
`docker-compose run --rm -w /app web composer update`  
2. kopi file .env.example ke .env  
3. generate key  
`docker-compose run --rm -w /app web php artisan key:generate`  

run container  
`docker-compose up -d`  

coba buka http://localhost:1187  

stop container  
`docker-compose down`  

cara masuk ke shell container (new container auto destroy)  
`docker-compose run --rm web /bin/bash`  

cara masuk ke shell container  
`docker exec -it zlara /bin/bash`  


