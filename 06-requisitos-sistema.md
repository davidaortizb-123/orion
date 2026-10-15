# 4. Requisitos del sistema — ORIÓN

## Entidades
- Empresa.
- Evento o producción.
- Sector.
- Función.
- Personal.
- Documento.
- Acreditación.
- Costo operativo.

## Reglas implementadas
- El número de documento de cada persona debe ser único.
- Cada persona se asocia a una empresa y una producción, sector y función.
- Cada acreditación se identifica con un UUID.
- No se puede crear más de una acreditación para la misma persona en la misma producción.
- El costo debe ser igual o mayor que cero.
- La fecha final de un evento debe ser posterior a la inicial.
