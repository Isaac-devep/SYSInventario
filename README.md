Proyecto Farmacia

Este proyecto es un sistema de gestión para una farmacia, que incluye funcionalidades para manejar la base de datos de productos, ventas y clientes.

Contenido del Repositorio
farmaciaDB.sql: Script para la creación de la base de datos.
farmaciaDBdata.sql: Script para la inserción de datos en la base de datos.
nbproject: Carpeta del proyecto NetBeans.
src: Carpeta que contiene el código fuente del proyecto.

Requisitos
Para ejecutar este proyecto, necesitarás:

MySQL o cualquier otro sistema de gestión de bases de datos compatible.
Un servidor web como Apache.
PHP 7.4 o superior.
NetBeans o cualquier otro IDE compatible con proyectos Java.

Instalación
Clonar el repositorio
git clone https://github.com/tu_usuario/farmacia.git
cd farmacia

Crear la base de datos
Importa los archivos farmaciaDB.sql y farmaciaDBdata.sql en tu sistema de gestión de bases de datos:

mysql -u tu_usuario -p tu_contraseña farmacia < farmaciaDB.sql
mysql -u tu_usuario -p tu_contraseña farmacia < farmaciaDBdata.sql
Configurar el servidor web

Asegúrate de que tu servidor web esté configurado para servir el proyecto. Si estás usando Apache, configura el archivo de host virtual para apuntar al directorio src.

Abrir el proyecto en NetBeans

Abre NetBeans, selecciona File > Open Project, y navega hasta la carpeta farmacia-master para abrir el proyecto.

Uso
Una vez que hayas configurado todo, puedes acceder al sistema de gestión de la farmacia a través de tu navegador web apuntando a http://localhost/farmacia.

Contribuir
Si deseas contribuir a este proyecto, por favor realiza un fork del repositorio y envía un pull request con tus mejoras.
