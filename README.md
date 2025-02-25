# Configurar un compose para correr un cluster Consul conformado por un servidor y un cliente que registran una aplicación. 

docker compose up -d --build

docker ps

ve a la direccion: 192.168.80.3:8500 para ver la interfaz de Consul y a la direccion: 192.168.80.3:5000 para verificar la aplicacion

Una vez funcionando, deberias ver el servicio y el cluster:

app-compose junto con los healthchecks.
