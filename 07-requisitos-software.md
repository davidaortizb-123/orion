# 5. Requisitos de software — ORIÓN

## Funciones
1. Registrar y consultar empresas.
2. Registrar y consultar producciones.
3. Registrar y buscar personal.
4. Cargar y revisar documentos.
5. Aprobar personal cuando sus documentos estén marcados como válidos.
6. Emitir una acreditación al aprobar personal.
7. Registrar costos operativos.
8. Consultar indicadores agregados.

## Requisitos no funcionales iniciales
- Acceso autenticado a los módulos internos.
- Validación de datos en formularios.
- Interfaz adaptable a móviles y escritorio.
- Uso de relaciones en base de datos para reducir duplicidad.
- Protección básica de formularios mediante CSRF de Django.

La seguridad para producción requiere más medidas que las incluidas en este prototipo.
