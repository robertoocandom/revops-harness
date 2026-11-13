---
version: v0.1-borrador
estado: borrador          # borrador | ratificada
ratificada: —
guardian: <rol>
---
# Constitución comercial de <EMPRESA>

Reglas que nunca se rompen. Cada una tiene que poder verificarse. La IA las lee antes de cada tarea. Solo el Guardián aprueba cambios.

## Reglas

| # | Regla | Cómo se verifica |
| --- | --- | --- |
| 1 | Todo lead nuevo recibe respuesta en menos de **5 minutos** en horario laboral | Tiempo de primera respuesta en el CRM |
| 2 | Ningún descuento mayor al **X%** sin aprobación del Guardián | Descuentos en cotizaciones vs. lista de precios |
| 3 | Toda campaña tiene objetivo, KPI y presupuesto tope antes de lanzarse | Brief aprobado en `02-CONOCIMIENTO/marketing` |
| 4 | Ninguna oferta se publica por debajo del margen mínimo de **X%** | Cálculo de margen en el brief |
| 5 | Todo texto público sigue la voz de marca y no promete lo que no se entrega | Revisión contra `marca/voz.md` |
| 6 | Toda cifra de un reporte cita su fuente; las ventas salen del CRM o ERP, nunca de la plataforma de anuncios | Fuente al lado de cada número |
| 7 | Ningún dato de clientes sale de los sistemas de la empresa sin aprobación | Revisión antes de exportar o compartir |

## Definición de "terminado"

Una tarea está terminada cuando:
- [ ] Cumple todas las reglas de arriba.
- [ ] Tiene evidencia (link, captura o número con fuente).
- [ ] Quedó registrada en `BITACORA.md` (y en `DECISIONES.md` si se decidió algo).

## Registro de cambios

Nunca se edita una regla aprobada: se marca como reemplazada y se agrega la nueva.

| Versión | Fecha | Cambio | Por qué | Aprobó |
| --- | --- | --- | --- | --- |
| v0.1-borrador | AAAA-MM-DD | Borrador inicial desde la plantilla | — | — |
