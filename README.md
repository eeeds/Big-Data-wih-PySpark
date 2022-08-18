## Build the image
```
docker build -t spark .
```
## Run the image
```
docker run -d -v "C:\Users\User\Desktop\Github\Datacamp\Big Data wih PySpark\code":/work  --name empanada spark 
```
## Exec the image
```
docker exec -it  empanada bash
```
## Finally, I'm going to use docker-compose
## Build the compose
```
docker-compose build
```
## Run the compose
```
docker-compose up -d
```
This final docker-compose is working well

