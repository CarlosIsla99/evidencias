**Índice**   
1. [AWS SERVER DOCUMENTATION](#id1)
2. [AGREGAR IP ELÁSTICA](#id2)
3. [GESTIÓN DE DNS](#id3)
4. [VIRTUAL HOSTS](#id4)
5. [SERVIDOR FTP](#id5)
6. [COPIAS DE SEGURIDAD](#id6)
7. [AUTOMATIZAR COPIAS DE SEGURIDAD](#id7)
8. [INSOMNIA](#id8)

# <u>AWS SERVER DOCUMENTATION</u><a name="id1"></a>

* **Conexión al servidor**
![conection](img/conection-to-server.PNG)

* **Actualizar Ubuntu**
![update](img/update-ubuntu-1.PNG)
![update](img/update-ubuntu-2.PNG)

* **Instalación de Apache2**
![apache2 installation](img/apache2-installation.PNG)

* **Instalación de MYSQL**
![mysql installation](img/mysql-installation.PNG)
![mysql installation](img/mysql-secure.PNG)
![mysql installation](img/mysql-secure-ajustes.PNG)
*contraseña: carlos20*

* **Instalación de PHP**
![php installation](img/php-installation.PNG)
![php installation](img/mysql-restart-apache2.PNG)
![phpmyadmin installation](img/phpmyadmin-instalation.PNG)


# <u>AGREGAR IP ELÁSTICA</u><a name="id2"></a>

* **Clickr en el menú "Elastic IPs"**
![ip elastica](img/menu.PNG)

* **Añadir direccion**
![ip elastica](img/allocate-ip.PNG)
![ip elastica](img/allocated-ip.PNG)

* **Asociar IP elástica**
![ip elastica](img/asociar-ip.PNG)
![ip elastica](img/ip-asociada.PNG)

# <u>GESTIÓN DE DNS</u><a name="id3"></a>

* **En la página de www.gestionservicios.online**
![gestion DNS](img/regsitros.PNG)
* **Rellenamos datos**
    * Nombre de la página
    * Tiempo de vida
    * Tipo de registro DNS
    * Dirección IPv4.
![gestion DNS](img/form-dns.PNG)

* **Resultado**
![gestion DNS](img/dns-funciona.PNG)

# <u>VIRTUAL HOSTS</u><a name="id4"></a>

* **Crea carpetas ('servidor' y 'cliente') en /var/www con index.html diferentes**
![servidor-cliente](img/servidor-cliente.PNG)
![servidor-cliente](img/servidor-cliente-servidorhtml.PNG)
![servidor-cliente](img/servidor-cliente-clientehtml.PNG)

* **Crae dos subdominios:**
    * cliente-tunombre.dominios.fpz1920.<i></i>com
    * servidor-tunombre.dominios.fpz1920.<i></i>com
![servidor-cliente](img/servidor-cliente-dns.PNG)

* **Dar permisos para su uso**
![servidor-cliente](img/servidor-cliente-permisos.PNG)

* **Añadir carpetas a sitesaviable**
    * Añadir carpetas cliente y servidor
![servidor-cliente](img/servidor-cliente-sites.PNG)
    * Editar la dirección y el nombre
![servidor-cliente](img/servidor-cliente-host.PNG)
    * Aplicar a2ensite
![servidor-cliente](img/servidor-cliente-a2ensite.PNG)

* **Reinicar apache para comprobar los resultados**
![servidor-ciente](img/servidor-cliente-restart.PNG)
![servidor-ciente](img/servidor-cliente-resultado1.PNG)

# <u>SERVIDOR FTP</u><a name="id5"></a>
![servidor-FTP](img/t5.PNG)
![servidor-FTP](img/t5-edit.PNG)
![servidor-FTP](img/t5-añadir.PNG)
![servidor-FTP](img/t5-add-users.PNG)
![servidor-FTP](img/t5-vsftpd.PNG)
![servidor-FTP](img/t5-vsftpd-edit.PNG)
![servidor-FTP](img/t5-nano.PNG)
![servidor-FTP](img/t5-restart.PNG)
![servidor-FTP](img/t5-users.PNG)
![servidor-FTP](img/t5-end.PNG)

# <u>Copias de seguridad</u><a name="id6"></a>
* **Crear copias tipo tar**
![copia de seguridad](img/cs.PNG)
![copia de seguridad](img/cs-1.PNG)
![copia de seguridad](img/cs-tar-resul.PNG)
* **Crear una BBDD y copia**
![copia de seguridad](img/cs-bbdd.PNG)
![copia de seguridad](img/cs-bbdd-copia.PNG)
* **Comprobación**
![copia de seguridad](img/cs-resul-final.PNG)

# <u>Automatización de copias de seguridad</u><a name="id7"></a>
* **Creamos una carpeta 'backup'**
![automatizacion](img/auto-carp.PNG)
* **Creamos un PHP que ejecute el .sh**
![automatizacion](img/auto-sh.PNG)
![automatizacion](img/auto-php.PNG)
* **Creamos el .sh**
![automatizacion](img/auto-script.PNG)
* **Dar permisos a la carpeta que contiene el .php**
![automatizacion](img/auto-perm.PNG)
* **Dar permisos a la carpeta de backups**
![automatizacion](img/backup-perm.PNG)
* **Cambiar usuarios**
![automatizacion](img/camb-usu.PNG)
* **Creamos con crontab para hacer el backup**
![automatizacion](img/cron.PNG)

# <u>INSOMNIA</u><a name="id8"></a>
## Tarea1
* **configurar el .htcacces para recibir el path y redireccionar al .php**

![insomnia](img/htcacces.PNG)

* **configurar el .htcacces para recibir el path y redireccionar al .php**

![insomnia](img/php.PNG)

## Tarea2
* **El php procesa los datos y recibe lo siguiente**

![insomnia](img/php_file.PNG)

* **GET**

![insomnia](img/get_2.PNG)

* **POST**

![insomnia](img/post_2.PNG)

* **DELETE**

![insomnia](img/delete_2.PNG)

* **PUT**

![insomnia](img/put_2.PNG)

## Tarea3
* **Crear la conexión con la BBDD**
![insomnia](img/connect.PNG)

* **Crear un CASE para abarcar todas las posibilidades**
    * **GET**
    ![insomnia](img/get.PNG)
    * **POST**
    ![insomnia](img/post.PNG)
    * **PUT**
    ![insomnia](img/put.PNG)
    * **DELETE**
    ![insomnia](img/delete.PNG)
