# php-backend-challenge

Hola,

Antes de nada, agradecerte dedicar parte de tu tiempo a la realización de este pequeña prueba técnica.

# Enunciado

Imaginemos que un cliente solicita que le contactemos en relación con una Hipoteca. Mediante una llamada a la API REST persistirlo en la base de datos.

La solicitud de hipoteca debe contener:

- Nombre y apellidos del cliente
- Email (Único por cliente)
- Teléfono (Único por cliente)
- Ahorros aportados
- Precio de Compra
- Fecha de solicitud

Una vez tenemos guardada la información de la solicitud de la hipoteca, debe asignarse a un experto hipotecario de forma aleatoria.

Por otro lado, nuestros **expertos hipotecarios** mediante su aplicación, necesitan obtener el listado de solicitudes a gestionar. Es necesario contar con un endpoint que reciba como parámetro el ID del experto y la fecha de las solicitudes que queremos obtener y nos devuelva un JSON con el listado. indicando el porcentaje de **Ahorros aportados** sobre el **Precio de Compra**

# TODO

- Arquitectura de aplicación en Laravel/symfony
- Construir el modelo de datos en MYSQL con todas las entidades y relaciones (Solicitudes de hipoteca, expertos, clientes...)
- Endpoint para persistir la solicitud en BD
- Endpoint de recuperación aleatoria de experto hipotecario 
- Endpoint para mostrar las solicitudes a gestionar por el experto

# Evaluable

- Diseño modelado de datos
- API REST con sus endpoints
- Arquitectura de aplicación en Laravel/symfony
- Utilización del ORM
- Uso de buenas prácticas
- Patrones de diseño utilizados
- Optimización del performance
