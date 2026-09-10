======= COMANDOS POSTGRESQL =======
\dt: Lista tablas dentro de psql
\dn: Lista schemas
\l: Lista bases de datos

psql: iniciar bd
\q: salir de psql

cerrar consulta con q

ejemplos

SELECT * FROM tbl_gasto LIMIT 10;

UPDATE tbl_gasto
SET monto = 1500
WHERE id = 10;


