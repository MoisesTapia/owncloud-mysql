![Texto alternativo](https://github.com/MoisesTapia/owncloud-mysql/blob/master/owncloud.png)

[![Channel](https://img.shields.io/badge/channel-YouTube-red)](https://www.youtube.com/channel/UCiuZK5geN3OCGeBxuXMfHEQ)
[![Docker](https://img.shields.io/badge/Docker-19.03.8-blue)](https://www.docker.com/)
[![Owncloud](https://img.shields.io/badge/Owncloud-10.0.3-orange)](https://hub.docker.com/_/owncloud)
[![Mysql](https://img.shields.io/badge/Mysql-5.7-green)](https://hub.docker.com/_/mysql)

# Language
[Español](https://github.com/MoisesTapia/owncloud-mysql/blob/master/README.md#Uso)<br>
[English](https://github.com/MoisesTapia/owncloud-mysql/blob/master/README.md#usage)

## Uso

```bash
git clone https://github.com/MoisesTapia/owncloud-mysql
cd owncloud-mysql
```
dentro de nuestra carpeta estara el docker compose el cual solo le daremos
```bash
docker-compose up -d
```
con esto iniciaremos la descarga de los servicios de Owncloud y MySQL
### Datos y volumenes
Nos creara 2 carpetas "index" y "mysql_data" donde se almacenara toda la informacion

### Env
Para las variables de entorno estaran en el archivo ".env"
```bash
MYSQL_DATABASE=owncloud
MYSQL_USER=owncloud
MYSQL_PASSWORD=owncloud
MYSQL_ROOT_PASSWORD=owncloud
```
estas estan marcadas por defecto pero las puedes cambiar a tu concideracion.

### Usage

```bash
git clone https://github.com/MoisesTapia/owncloud-mysql
cd owncloud-mysql
```
Once inside our folder we need just to run:
```bash
docker-compose up -d
```
### files and volumes
This will creates two folders one with the name "index" and other with with name "mysql_data" in each folder will be stored all information about the containers

### Env
The .env file contain the environment vars
```bash
MYSQL_DATABASE=owncloud
MYSQL_USER=owncloud
MYSQL_PASSWORD=owncloud
MYSQL_ROOT_PASSWORD=owncloud
```
You can change it for your advisability
