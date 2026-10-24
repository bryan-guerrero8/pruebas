# Especificación breve de requisitos de software (SRS)

## 1. Propósito

Definir los requisitos principales del Sistema de Reservas de Laboratorios Universitarios para facilitar la planificación y el control de uso de los espacios académicos.

## 2. Alcance del producto

El sistema centraliza la consulta de disponibilidad y la solicitud, aprobación, cancelación y seguimiento de reservas. Los usuarios accederán a las funciones correspondientes a su perfil.

## 3. Clases de usuario

- **Solicitante:** docente o usuario institucional autorizado que consulta disponibilidad y solicita reservas.
- **Coordinador:** revisa solicitudes, administra la programación y resuelve conflictos.
- **Administrador:** gestiona cuentas, roles, laboratorios y parámetros del sistema.

## 4. Entorno operativo

Aplicación web accesible desde navegadores modernos en computadoras, tabletas y teléfonos. Requiere conexión a la red institucional o a internet según la implementación.

## 5. Reglas del negocio

1. Una reserva debe indicar laboratorio, fecha, hora de inicio, hora de fin y motivo.
2. La hora de fin debe ser posterior a la hora de inicio.
3. No se confirma una reserva si existe una reserva confirmada superpuesta o un bloqueo de mantenimiento.
4. Una solicitud permanece pendiente hasta que el coordinador la apruebe o la rechace.
5. Solo usuarios autorizados pueden consultar datos privados o administrar reservas.
6. Las cancelaciones respetan el plazo definido por la institución.

## 6. Restricciones

- Las reglas de prioridad y cancelación deben ser aprobadas por la institución.
- El acceso a funciones administrativas requiere autenticación.
- Los datos personales no deben exponerse en la consulta pública de disponibilidad.

## 7. Criterios de aceptación

- Un usuario autorizado puede consultar la disponibilidad por fecha y horario.
- El sistema rechaza una solicitud con horario inválido o superpuesto.
- El coordinador puede aprobar o rechazar una solicitud pendiente.
- El solicitante puede consultar el estado actualizado de su solicitud.
- Un usuario sin permisos administrativos no puede modificar laboratorios ni roles.
