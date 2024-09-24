# Sistema de Gestión de Tareas

Este proyecto es un Sistema de Gestión de Tareas desarrollado en PHP puro. Permite a los usuarios registrarse, iniciar sesión, y gestionar sus tareas de manera eficiente. Los usuarios pueden crear, editar, eliminar y marcar tareas como completadas, así como clasificar las tareas mediante etiquetas.

## Funcionalidades

- **Registro de Usuarios**: Los usuarios pueden crear una cuenta y gestionar sus perfiles.
- **Gestión de Tareas**: Crear, editar, eliminar y marcar tareas como completadas.
- **Etiquetas**: Clasificar tareas para una mejor organización.
- **Sistema de Comentarios**: Comentar en tareas para colaborar.
- **Notificaciones**: Recibir notificaciones por correo electrónico.

## Requisitos

- PHP 7.0 o superior
- Servidor web (Apache/Nginx)
- MySQL
- Composer (opcional, para la gestión de dependencias)

## Instalación

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/tu_usuario/sistema-gestion-tareas.git
   ```

# Crea la base de datos:

Abre tu cliente MySQL y ejecuta el siguiente comando sql:

    ```sql
    CREATE DATABASE task_management;
    ```

# Importa la estructura de la base de datos:

Crea las tablas necesarias utilizando los scripts SQL proporcionados en database_scripts/

# Configura la conexión a la base de datos:

Edita el archivo .db.env y proporciona tus credenciales de la base de datos.

# Configura el servidor:

Asegúrate de que tu servidor web apunte al directorio del proyecto.

# Accede a la aplicación:

Abre tu navegador y ve a http://localhost/task_management/index.php
