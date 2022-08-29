# docker_pmn
* This project is for running php on nginx with mysql database on docker images.

## Run
```
cd docker_pmn
docker-compose up
```

## Browser url
```
localhost:8000
````

## Connect to DB
```
docker exec -it {container ID} /bin/bash
> mysql -uroot -p
> root_password
```
