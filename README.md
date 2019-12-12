# mysql-mssql-php7-docker
Entorno dockerizado con MySQL, MS-SQL y PHP7



## VirtualHosts

En **/etc/hosts**, para cada proyecto se recomienda tener

127.0.0.1 proyecto-01.st


### Uso


#### Clonar éste proyecto y el o los subproyectos

``` sh
$ git clone --recursive git@github.com:jeastman-labs/mysql-mssql-php7-docker.git
```

#### Levantar el entorno
``` sh
$ docker-compose up -d
```

#### Detener el entorno
``` sh
$ docer-compose stop
```

### Detener el entorno y eliminar los contenedores
``` sh
$ docker-compose down
```

### Eliminar las imágenes
``` sh
$ docker rmi -f `docker images -q`
```
