# Usamos una imagen existente como imagen base
FROM alpine

# Descargamos e instalamos la dependecia
RUN apk add --update redis

# Le decimos a la imagen qué ahcer cuando arranque como un container.
CMD ["redis-server"]