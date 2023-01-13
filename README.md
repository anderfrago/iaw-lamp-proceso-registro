# Proceso de registro _inseguro_

En esta primera versión se van a trabajar aspectos relacionados con la comunicación entre PHP y MySQL, además de la gestión de sesiones. Además, en el proceso de registro se puede comprobar en que consiste una inyección de SQL. _¿Cómo la corregirías?_

### Lista de tareas a completar

> El alumnado debe completar los comentacios marcados con TODO (_pendiente de hacer_) en el código

- Comienza obteniendo el proyecto desde el repositorio inicial.
- A continuación, crea tu propio proyecto en GitHub y subé ahí el código

#### 1 Registro

> **signup.php**

- Realiza la lectura de los campos del formulario en $user y $pass
- Establecer el almacenamiento de usuario en la sesión para que al pulsar sobre el menú de Acceder no se le vuelva a preguntar por usuario/contraseña.
- Muestra mensaje de error x2

#### 2 Acceso

> **login.php**

- Establecer la consulta de base de datos correspondiente para verificar si el usuario existe.
  $result = queryMySQL("")
- Realiza la gestión de la sesión de usuario. Almacena en la variables de sesión user el valor de $user
- Corrige el BUG.
- Muestra el mensaje de error x2
