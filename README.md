

Este repositorio aloja una aplicación simple de PHP CRUD (Create, Read, Update, Delete). Es una demostración básica de cómo integrar PHP con una base de datos MySQL para administrar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario.

## Tecnologías Empleadas

- **PHP:** Lenguaje de secuencias de comandos del lado del servidor utilizado en el desarrollo web.
- **MySQL:** Sistema de gestión de bases de datos empleado para almacenar los datos de usuario.
- **HTML & CSS:** Utilizados para estructurar y estilizar las páginas web.
- **Tailwind CSS:** Un framework de CSS utilitario para el desarrollo rápido de interfaces de usuario.

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

- **Funcionalidad:** Presenta todos los usuarios de la base de datos en una tabla.
- **Características:** 
  - Visualización de todos los usuarios.
  - Enlaces para añadir, editar o eliminar información de usuario.

### 2. Añadir Usuario (`user.php`)

![Añadir Usuario](images/add.png)

- **Funcionalidad:** Permite agregar un nuevo usuario a la base de datos.
- **Características:** 
  - Formulario para ingresar los detalles del usuario (nombre, correo electrónico, teléfono móvil, contraseña).
  - Validación de datos y envío a la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

- **Funcionalidad:** Permite modificar los detalles de los usuarios existentes.
- **Características:** 
  - Formulario con los detalles actuales del usuario.
  - Actualización de los detalles del usuario en la base de datos.

### 4. Eliminar Usuario (`delete.php`)

- **Funcionalidad:** Facilita la eliminación de un usuario de la base de datos.
- **Características:** 
  - Eliminación de la información del usuario basada en su ID.

## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece la conexión con la base de datos MySQL.
- **Credenciales:** Emplea el nombre del host, usuario, contraseña y nombre de la base de datos para la conexión.

## Ejecución

1. Clona el repositorio en tu dispositivo local.
2. Configura un entorno PHP y MySQL (como XAMPP).
3. Crea la base de datos utilizando phpmyadmin.
4. Ejecuta la aplicación en un servidor local.

## Nota de Seguridad

Esta aplicación es una demostración básica y no incluye medidas avanzadas de seguridad. Se recomienda utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos, con el fin de prevenir ataques de inyección SQL.

---

Siéntete libre de contribuir a este proyecto o sugerir mejoras. Para cualquier consulta o problema, por favor abre un issue en este repositorio.

