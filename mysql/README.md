## Build
```sh
docker build -t mysql-server:latest .
```

## Run
```sh
 docker run --name=mysql-server -p 3306:3306/tcp -d mysql-server
```

## Stop
```sh
docker kill mysql-server
docker rm mysql-server
```