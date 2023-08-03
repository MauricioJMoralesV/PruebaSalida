Proyecto de Gestión de Restaurant

Este proyecto es una aplicación web desarrollada en Java para la gestión de un restaurante, incluyendo la administración de mesas, pedidos y camareros.
Tabla de contenidos

    Requisitos
    Instalación
    Uso
    Contribución
    Licencia

Requisitos

Antes de comenzar, asegúrate de tener instalados los siguientes componentes:

    Java Development Kit (JDK) 11 o superior
    Maven
    MySQL Server

Instalación

    Clona este repositorio en tu máquina local utilizando Git:

bash

git clone https://github.com/tu-usuario/restaurant-gestion.git

    Configura la base de datos MySQL:
        Crea una base de datos con el nombre "Restaurant".
        Abre el archivo "application.properties" en la carpeta "src/main/resources" y ajusta la configuración de la base de datos (nombre de usuario, contraseña, etc.):

properties

spring.datasource.url=jdbc:mysql://localhost:8081/Restaurant
spring.datasource.username=root
spring.datasource.password=


Uso

Una vez que la aplicación esté en funcionamiento, puedes acceder a la interfaz web en http://localhost:8081. Aquí podrás realizar las siguientes acciones:

    Administrar mesas: Agregar, editar y eliminar mesas.
    Realizar pedidos: Seleccionar una mesa, camarero y platos para generar un pedido.
    Ver historial de pedidos: Buscar y visualizar los detalles de los pedidos realizados.


Licencia

Este proyecto está bajo la Licencia Awakelab. Consulta el archivo LICENSE para más detalles.
