# Anteproyecto

Para el desarrollo del proyecto intermodular, requiere montar una arquitectura física de máquinas, las cuales deben incluir servidores de microsoft o de linux, además de incluir clientes de ambas distribuciones.

![alt text](image.png)

La imagen adjuntada, especifica que máquinas y arquitectura debe incluir como mínimo, a partir de estos requisitos, nosotros hemos planteado, seguir la siguiente distribución de servidores y clientes.

## NUESTRO ANTEPROYECTO

Hemos considerado hacer la siguiente distribución:

Servidores Linux:

- SO: Debian 12
- Funciones: Utilizaremos 2 servidores Debian, el primero para WEB y BBDD, el segundo para DNS y CORREO

Servidor Windows:

- SO: Windows Server 2019
- Función: Utilizaremos windows server para el DHCP

Clientes:

- SO: Windows 10 (en duda)
- SO: Linux (2)

Máquinas pfsense

- Función: Proxy (Cortafuegos dmz-Red local)
- Función: Cortafuegos (DMZ - exterior)


![alt text](image-1.png)

### Objetivo del Proyecto: 

Nuestro proyecto intermodular tiene como objetivo el diseño, desarrollo, creación e implementación de una página web de pujas. La página web será desplegada sobre la infraestructura de servidores y clientes previamente comentada (configurada), servirá como punto de encuentro entre compradores y vendedores, que quieran poner a la venta piezas de componetentes o equipos.

### Roles de Usuario: 

La plataforma distinguirá entre dos tipos de usuarios:

- Comprador: Podrá participar en número ilimitado de subastas disponibles, sin límite de dinero y gestionar su cuenta.
- Vendedor: Tendrá la capacidad de crear pujas ( el número de pujas creadas será ilimitado), desde el precio mínimo que el vendedor quiera.

### Funcionalidades Principales:

- Gestión de Cuentas y Autenticación: Sistema de registro seguro que requerirá confirmación mediante correo electrónico.

- Perfiles Dinámicos: Los usuarios podrán participar en subastas y poner sus productos a la venta en subastas, cuando ellos quieran.

- Publicación y Postulación: Flujo completo para poder participar en subastas y vender.

- Arquitectura y Base de Datos: Debido a la variedad y constante cambio de los datos de las subastas , el proyecto utilizará una base de datos NoSQL (mongoDB). Esto proporcionará la flexibilidad y escalabilidad necesarias para gestionar las actualizaciones constantes de los precios sin las restricciones de una base de datos SQL.



