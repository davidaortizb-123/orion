# 6 y 7. Requisitos funcionales y no funcionales — ORIÓN

## Funcionales
- RF-01: crear producciones.
- RF-02: registrar empresas.
- RF-03: registrar personal por producción, empresa, sector y función.
- RF-04: cargar documentos con fecha de vencimiento y estado.
- RF-05: impedir la aprobación si existen documentos que no estén en estado válido.
- RF-06: emitir una acreditación única al aprobar personal.
- RF-07: registrar costos y asociarlos a una producción.
- RF-08: consultar cifras generales en el dashboard.

## No funcionales
- RNF-01: el sistema debe exigir inicio de sesión para sus módulos internos.
- RNF-02: los campos se validan en el servidor.
- RNF-03: la interfaz debe funcionar en pantallas pequeñas y grandes.
- RNF-04: la base de datos debe mantener relaciones entre entidades.
- RNF-05: los archivos de documentos no deben exponerse públicamente en un despliegue real.

## Pendientes
No se especificaron objetivos de rendimiento, disponibilidad, recuperación ante fallos, niveles de servicio ni política de retención de datos.
