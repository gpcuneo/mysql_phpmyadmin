# mysql_phpmyadmin

### Ejecucion de MySQL 5.7 y PhpMyAdmin sobre Docker:

Crear un archivo .env en la raiz del proyecto y configurar las siguientes variables:
- MYSQL_ROOT_PASSWORD=password
- MYSQL_DATABASE=database
- MYSQL_USER=appuser
- MYSQL_PASSWORD=apppass
- PMA_HOST=db
- PMA_PORT=3306
- PMA_ARBITRARY=1

Lanzar los contenedores:
- docker compose up -d
