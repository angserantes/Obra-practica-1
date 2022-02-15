# Obra piloto do Servicio de Orientación Laboral

Realización de un modelo operativo simple de la aplicación destinada al Servicio de Orientación Laboral del Ayuntamiento de Vigo. El trabajo realizado se ha desarrollado en 3 grupos: diseño, documentación y programación.

## Grupo de programación:

1. tecnología empleada: PhpMyAdmin -> Creación de la BBDD llamada "obra" y sus respectivas tablas: usuarios, empresas e persoas.
2. Se decide adapatar los campos de las tablas, con una aproximación a los campos que se corresponden con los formularios actuales.
3. En la tabla "usuarios" se crean 3 usuarios: admin, funcionario1 y funcionario2.
4. Se instala Bootsrap.
5. Organizamos la estructura del proyecto:
   1. php de conexión a la base de datos
   2. formulario de login
   3. index.php donde hacemos una llamada al archivo conexion.php, un formulario de búsqueda por DNI  y una parte con html para la salida de los datos de la la tabla personas.
   4. Creación de los archivos de gardar, modificar, eliminar y actualizar de los apartados de empresas y personas.
