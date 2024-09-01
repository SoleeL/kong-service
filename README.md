# Ejecucion de kong

Ejecutar comando para la creacion de los contenedores:

$ docker compose up -d

Si 'kong-1' no esta iniciado correctamente:

1. Volver a iniciar 'kong-migrations-1'.
2. Cuando 'kong-migrations-1' termine, iniciar 'kong-1'.