# 1.3 Marco teórico y tecnológico — ORIÓN

El prototipo se construye como aplicación web con Python y Django. Django aporta rutas, formularios, autenticación, validación y acceso a base de datos. Se usa SQLite como base inicial, adecuada para desarrollo local. La interfaz se construye con plantillas HTML y CSS adaptable.

## Arquitectura
- Frontend: plantillas HTML y CSS.
- Backend: vistas y reglas de negocio en Django.
- Persistencia: modelos relacionales de Django.
- Archivos: almacenamiento local durante desarrollo.
- Identidad: identificador UUID para cada persona y acreditación.

La presentación menciona QR e integración tecnológica. En esta primera versión se crea un identificador único de acreditación, pero aún no se implementa el escaneo QR ni las integraciones externas.
