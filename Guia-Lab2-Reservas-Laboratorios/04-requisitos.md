# Requisitos del sistema

## Requisitos funcionales

| Código | Requisito | Prioridad |
|---|---|---|
| RF-01 | El sistema permitirá iniciar sesión con una cuenta autorizada. | Alta |
| RF-02 | El sistema permitirá consultar laboratorios, capacidad y equipamiento disponible. | Alta |
| RF-03 | El sistema permitirá consultar disponibilidad por fecha y rango horario. | Alta |
| RF-04 | El sistema permitirá enviar una solicitud indicando laboratorio, fecha, hora de inicio, hora de fin y motivo académico. | Alta |
| RF-05 | El sistema validará que la solicitud no se superponga con una reserva confirmada ni con un periodo de mantenimiento. | Alta |
| RF-06 | El coordinador podrá aprobar o rechazar solicitudes y registrar el motivo de la decisión. | Alta |
| RF-07 | El sistema notificará al solicitante cuando cambie el estado de su solicitud. | Media |
| RF-08 | El usuario podrá consultar el estado y el historial de sus solicitudes. | Media |
| RF-09 | El usuario podrá cancelar una reserva de acuerdo con las reglas institucionales. | Media |
| RF-10 | El administrador podrá gestionar usuarios, roles y datos de los laboratorios. | Alta |

## Requisitos no funcionales

| Código | Requisito | Criterio verificable |
|---|---|---|
| RNF-01 | Usabilidad | Las funciones principales deben estar identificadas con etiquetas claras y navegación consistente. |
| RNF-02 | Rendimiento | Las consultas de disponibilidad deberán responder en un máximo de 3 segundos bajo carga normal. |
| RNF-03 | Seguridad | El sistema deberá autenticar usuarios y restringir funciones según su rol. |
| RNF-04 | Privacidad | Los datos personales y detalles de las solicitudes solo serán visibles para usuarios autorizados. |
| RNF-05 | Integridad | El sistema no deberá permitir dos reservas confirmadas para el mismo laboratorio en intervalos superpuestos. |
| RNF-06 | Disponibilidad | El sistema deberá estar disponible durante los periodos de planificación y uso académico, salvo mantenimiento programado. |
| RNF-07 | Compatibilidad | La interfaz deberá funcionar en versiones actuales de navegadores de escritorio y móviles. |
