TÍTULO: Maquetación Web
¿Por qué validar formularios?
EL PROBLEMA E INSUMOS:
Los formularios son Interfaces (capa de comunicación entre el usuario y la
computadora) que permiten enviar información del usuario al sistema. Pudiéndose
enviar, por ejemplo, un nombre, un apellido, una fecha de nacimiento, un número de
cuenta, etc.
Cuando se envían los datos, el sistema que los recibe espera los formatos
correspondientes por cada tipo de dato. Si enviamos un nombre esperará un string, si
enviamos una fecha esperará un formato de fecha, si enviamos un número esperará un
número. El error se genera cuando enviemos información incorrecta en los campos, o
sea, si en un campo que tienes que enviar un dato tipo string envías un número. También
evitaremos las inyecciones SQL (SQL Injection es una falla en la codificación de una
aplicación cualquiera (web o local) que posibilita por medio de un input cualquiera, la
manipulación de una consulta SQL.).
PREGUNTAS:
• ¿Para qué sirve la validación de formularios?
    La validación de un formulario consiste en llamar a una propiedad y/o una función de validación cuando el usuario pulsa sobre el botón de envío del formulario. En esta función, se comprueban si los valores que ha introducido el usuario cumplen las restricciones impuestas por la aplicación.
• ¿Cuáles son los problemas al no validar un formulario?
    - Algunos usuarios pueden tener el JS deshabilitado
    - Hay que programar cada verificación (y eso es un engorro)
    - Queremos obtener los datos correctos en el formato correcto. Nuestras aplicaciones no funcionarán correctamente si los datos de nuestros usuarios se almacenan en el formato incorrecto, son incorrectos o se omiten por completo.
    - Queremos proteger los datos de nuestros usuarios. Obligar a nuestros usuarios a introducir contraseñas seguras facilita proteger la información de su cuenta.
    - Queremos protegernos a nosotros mismo. Hay muchas formas en que los usuarios maliciosos puedan usar mal los formularios desprotegidos y dañar la aplicación 
• ¿Cuáles son los beneficios?
    - Personalizable, En casuística (que para eso la programas), En diseño (para poner colorines y mensajes de alerta)
    - Mayor compatibilidad con navegadores (casi todos los modernos y no tan modernos)
    - Queremos obtener los datos correctos en el formato correcto. Nuestras aplicaciones no funcionarán correctamente si los datos de nuestros usuarios se almacenan en el formato incorrecto, son incorrectos o se omiten por completo.
    - Queremos proteger los datos de nuestros usuarios. Obligar a nuestros usuarios a introducir contraseñas seguras facilita proteger la información de su cuenta.
    - Queremos protegernos a nosotros mismo. Hay muchas formas en que los usuarios maliciosos puedan usar mal los formularios desprotegidos y dañar la aplicación 