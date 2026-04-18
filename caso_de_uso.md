# Caso de Uso General del Sistema

## Actores del sistema

### Estudiante
Usuario que necesita reservar salas o recursos para exposiciones o actividades académicas.

### Docente
Usuario que solicita salas, laboratorios o equipos para impartir clases o realizar actividades académicas.

### Personal Administrativo
Encargado de revisar, aprobar o rechazar solicitudes de reserva.

### Administrador del Sistema
Responsable de gestionar usuarios, recursos y funcionamiento general del sistema.

## Caso de uso principal: Solicitar reserva

### Actor principal
Estudiante o Docente

### Propósito
Permitir al usuario solicitar la reserva de una sala o recurso en una fecha y horario determinado.

### Precondiciones
- El usuario debe estar registrado.
- El usuario debe haber iniciado sesión.
- La sala o recurso debe estar disponible.

## Flujo básico
1. El usuario inicia sesión en el sistema.
2. El sistema muestra el menú principal.
3. El usuario consulta la disponibilidad.
4. El sistema muestra las salas y recursos disponibles.
5. El usuario selecciona una sala o recurso.
6. El usuario completa los datos de la reserva.
7. El sistema valida disponibilidad y horario.
8. El sistema registra la solicitud.
9. El sistema muestra mensaje de confirmación.

## Flujo alterno 1. Recurso no disponible
1. El usuario selecciona una sala o recurso.
2. El sistema detecta conflicto de horario.
3. El sistema muestra un mensaje indicando que no está disponible.
4. El usuario selecciona otro recurso o cambia de horario.

## Flujo alterno 2. Datos incompletos
1. El usuario intenta enviar la solicitud.
2. El sistema detecta campos vacíos.
3. El sistema solicita completar la información.
4. El usuario corrige y vuelve a intentar.