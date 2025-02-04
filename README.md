# Inventario-BAP

## Descripción
Inventario-BAP es un proyecto de gestión de inventarios desarrollado en PHP. Este proyecto permite a los usuarios gestionar y rastrear inventarios de productos de manera eficiente, proporcionando herramientas para agregar, editar, eliminar y visualizar productos dentro del sistema.

## Tecnologías utilizadas
- PHP
- MySQL (para la gestión de la base de datos)
- Apache/Nginx (servidor web)
- HTML, CSS y JavaScript (para la interfaz de usuario)
- Bootstrap (para un diseño responsivo y atractivo)

## Instrucciones de instalación
Sigue estos pasos para instalar y configurar el proyecto en tu entorno local:

1. Clona el repositorio:
    ```bash
    git clone https://github.com/AndresUni7/Inventario-BAP.git
    ```

2. Navega al directorio del proyecto:
    ```bash
    cd Inventario-BAP
    ```

3. Instala las dependencias necesarias utilizando Composer (si aplica):
    ```bash
    composer install
    ```

4. Configura tu servidor web para apuntar al directorio del proyecto. Si usas XAMPP o WAMP:
   - Copia la carpeta del proyecto en `htdocs` (para XAMPP) o `www` (para WAMP).
   - Asegúrate de que el servidor Apache y MySQL estén en ejecución.

5. Crea la base de datos en MySQL:
   - Accede a phpMyAdmin o usa la línea de comandos de MySQL:
     ```sql
     CREATE DATABASE inventario_bap;
     ```
   - Importa el archivo SQL del proyecto (si está disponible) en la base de datos.

6. Configura el archivo de conexión a la base de datos (`config.php` o similar), actualizando las credenciales según tu entorno:
    ```php
    define('DB_HOST', 'localhost');
    define('DB_USER', 'root');  // Cambiar si tienes otro usuario
    define('DB_PASS', '');      // Cambiar si tienes contraseña
    define('DB_NAME', 'inventario_bap');
    ```

7. Inicia el servidor local si no lo has hecho:
    ```bash
    php -S localhost:8000
    ```
    O accede a `http://localhost/Inventario-BAP` en tu navegador.

## Instrucciones de uso
1. Abre tu navegador web y navega a `http://localhost/Inventario-BAP` o la URL configurada.
2. Inicia sesión utilizando tus credenciales (usuario y contraseña por defecto si aplica).
3. Utiliza el menú de navegación para acceder a las diferentes funcionalidades del sistema de inventario:
   - **Agregar productos**: Registra nuevos productos con nombre, cantidad, precio y categoría.
   - **Editar productos**: Modifica la información de los productos existentes.
   - **Eliminar productos**: Remueve productos del inventario.
   - **Visualizar inventario**: Consulta la lista de productos disponibles.
   - **Generar reportes**: Exporta datos en formatos como PDF o Excel (si está implementado).
## Autor
- **AndresUni7** - [GitHub](https://github.com/AndresUni7)
