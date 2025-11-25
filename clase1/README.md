Aplicacion httpd
//nos permite arrancar un contenedor ver la aplicacion httpd respondiendo por el puerto 8081 de nuestro host está mapeado al puerto 80 del contenedor y docker se encargará de redirigir las peticiones al contenedor
docker run -d -p 8081:80 --name mi_Apache httpd
//listar los containers activos
docker ps
//detenido del container mi_Apache por Id
docker stop fff68ee5a753
//borrado del container mi_Apache por Id
docker rm fff68ee5a753
