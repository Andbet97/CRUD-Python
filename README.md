# Módulo de gestión de usuarios CRUD

Realizar un módulo de gestión de usuarios CRUD (create, read, update, delete) en el lenguaje
de programación python 3 utilizando programación orientada a objetos, se deberá guardar la
información en una base de datos Mysql.

De cada usuario se deberá capturar la siguientes información: primer nombre, segundo
nombres, primer apellido, segundo apellido, número de documento, dirección, número de
celular, nombre de usuario, contraseña y estado del usuario (activo o inactivo).

## Condiciones generales del programa:

1. Se debe validar que no se pueda ingresar campos vacios en la base de datos.

2. Al adicionar un usuario al sistema este queda activo inicialmente.

3. Un usuario se podrá eliminar o suspender (inactivo).

4. Se debe validar que el número de celular contenga solo dígitos y que contenga 10
dígitos.

5. Se debe validar que el nombre de usuario no exista en la base de datos.

6. Se debe validar que la contraseña tengo mínimo 10 caracteres, que contenga dígitos y
letras, mayúsculas y minúsculas, debe contener algunos de los siguientes caracteres
especiales (l,+.*,|).

7. La contraseña se debe almacenar en la base de dato con un digest de SAH1 ó MD5.

8. Los mensajes de error se deberán mostrar en pantalla en color rojo.

9. Los mensajes de información como “Usuario adicionado satisfactoriamente” o “usuarios
eliminado satisfactoriamente” se debe mostrar en pantalla en color verde.

10. Los usuarios se podrán almacenar en el sistema manualmente o desde un archivo de
Excel que contenga los datos requeridos.

11. El programa deberá correr en modo texto (Sin interfaz gráfica) en una consola de
sistema operativo (Windows, linux o Mac OS)