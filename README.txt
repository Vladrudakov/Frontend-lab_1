запускаем билд
1) docker build -t lab1 .  
lab1 - название образа

2) docker run -d -p 8080:8080 lab1
после чего заходим на localhost:8080