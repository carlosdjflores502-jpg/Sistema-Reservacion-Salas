# Requerimientos del Sistema

## Requerimientos Funcionales

### RF01. Registro de usuarios
El sistema deberá permitir el registro de usuarios mediante un formulario con nombre, correo institucional, contraseña y tipo de usuario.

### RF02. Inicio de sesión
El sistema deberá permitir que los usuarios registrados inicien sesión con su correo y contraseña.

### RF03. Recuperación de acceso
El sistema deberá permitir restablecer la contraseña en caso de olvido.

### RF04. Consulta de disponibilidad
El sistema deberá mostrar la disponibilidad de salas y recursos en tiempo real.

### RF05. Búsqueda de salas y recursos
El sistema deberá permitir buscar salas y recursos por fecha, hora, capacidad y tipo.

### RF06. Solicitud de reserva
El sistema deberá permitir registrar solicitudes de reserva indicando fecha, hora y propósito.

### RF07. Validación de conflictos
El sistema deberá validar que no exista una reserva previa en el mismo horario.

### RF08. Aprobación o rechazo de reservas
El sistema deberá permitir al personal administrativo aprobar o rechazar solicitudes.

### RF09. Notificación del estado de la reserva
El sistema deberá informar al usuario si su solicitud fue aprobada o rechazada.

### RF10. Historial de reservas
El sistema deberá permitir consultar el historial de reservas realizadas.

### RF11. Cancelación de reservas
El sistema deberá permitir cancelar reservas antes de la fecha programada.

### RF12. Gestión de salas y recursos
El sistema deberá permitir al administrador registrar, modificar o eliminar salas y recursos.

## Requerimientos No Funcionales

### RNF01. Usabilidad
El sistema debe contar con una interfaz intuitiva y fácil de usar.

### RNF02. Disponibilidad
El sistema debe estar disponible durante el horario institucional.

### RNF03. Seguridad
El sistema debe proteger el acceso mediante autenticación.

### RNF04. Tiempo de respuesta
El sistema debe responder en un tiempo no mayor a 3 segundos en condiciones normales.

### RNF05. Integridad de datos
El sistema debe garantizar que la información se almacene correctamente.

### RNF06. Compatibilidad
El sistema debe funcionar en navegadores modernos.

### RNF07. Escalabilidad
El sistema debe permitir futuras mejoras e integraciones.

### RNF08. Mantenibilidad
El sistema debe facilitar correcciones y actualizaciones futuras.

## DERCAS

### DERCAS 1. Validación de solapamiento de reservas
El sistema no debe permitir que una sala o recurso sea reservado por más de un usuario en el mismo horario.

### DERCAS 2. Control de acceso por roles
El sistema debe restringir funciones según el tipo de usuario.

### DERCAS 3. Registro y conservación de historial
El sistema debe almacenar un historial de todas las reservas realizadas.