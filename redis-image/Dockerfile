# Usamos una imagen existente como imagen base
FROM alpine

# Descargamos e instalamos todas las dependecias
RUN apk add --update redis
RUN apk add --update gcc
# Le decimos a la imagen qué ahcer cuando arranque como un container.
CMD ["redis-server"]