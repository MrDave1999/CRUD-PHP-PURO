# CRUD-PHP-PURO
Esta aplicación web solo es para fines de aprendizaje.

## Instalación

Para poder ejecutar la app se necesita tener:

- Apache HTTP
- MySQL Server 8.0
- Intérprete PHP
  - Hay que habilitar la extensión `mysqli`
  
Para **importar** `dbsector.sql` necesita primero crear la base de datos:
```sql
CREATE DATABASE dbsector;
```
Luego ejecute este comando (reemplace en `username` por el nombre de usuario que use, por ejemplo: `root`):
```bash
mysql -u username -p dbsector < dbsector.sql 
```

**Nota:** También debe de modificar la [cadena de conexión](https://github.com/MrDave1999/CRUD-PHP-PURO/blob/main/models/conexion.php#L6) (agregue el nombre de usuario y la contraseña correspondiente).
  
  
