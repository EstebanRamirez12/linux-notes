=========|| Docker ||==========
docker images: Lista imágenes descargadas
docker inspect <contenedor>: Muestra configuración detallada
docker compose ps: Estado de servicios Compose


INICIAR BASE DE DATOS
cd ~/dev/postgresql
docker compose up -d

CERRARAR BASE DE DATOS
docker stop postgres-dev

VERIFICAR 
docker ps

docker exec -it postgres-dev psql -U postgres -d DB_HomeFlow: Entrar a PostreSQL



correo: personal
pass: Test1234
