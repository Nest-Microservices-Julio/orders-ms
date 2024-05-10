# Orders Microservice

## Dev

1. Clonar el repositorio
2. Instalar dependencias
3. Crear un archivo `.env` basado en `.env.template`
4. Ejecutar migracion de prisma `npx prisma migrate dev`
5. Ejecutar el docker-compose `docker-compose up -d`
6. Ejecutar el servidor Nats
```bash	
docker run -d --name nats-main -p 4222:4222 -p 8222:8222 nats
```
6. Ejecutar el servidor `npm run start:dev`