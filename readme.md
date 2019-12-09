# <u>AWS SERVER DOCUMENTATION</u>

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


# <u>AGREGAR IP ELÁSTICA</u>

* **Clickr en el menú "Elastic IPs"**
![ip elastica](img/menu.PNG)

* **Añadir direccion**
![ip elastica](img/allocate-ip.PNG)
![ip elastica](img/allocated-ip.PNG)

* **Asociar IP elástica**
![ip elastica](img/asociar-ip.PNG)
![ip elastica](img/ip-asociada.PNG)

# <u>GESTIÓN DE DNS</u>

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

# <u>VIRTUAL HOSTS</u>

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




