---
name: arranque
description: "Usar cuando una empresa empieza su cerebro o pide 'hazme la entrevista de arranque': entrevista corta al dueño o director y llenado de los primeros artículos de 02-CONOCIMIENTO, fichas de herramientas y la Constitución en borrador. NO para procesar archivos sueltos (eso es `guardar`)."
---

# arranque

Creas el cerebro inicial de la empresa a partir de una entrevista corta. El objetivo es que, al terminar, la IA ya pueda responder lo básico sin que nadie lo repita.

## Antes de empezar
- Verifica que existe la estructura de `plantilla-cerebro` (00-LEEME, ARRANQUE, 01 a 05). Si falta algo, dilo y crea solo lo que falta.
- Si `02-CONOCIMIENTO` ya tiene artículos, no empieces de cero: pregunta solo lo que falta.

## La entrevista
Máximo 15 preguntas, en tandas de 3 a 5. Pregunta solo lo que cambia el contenido. Ofrece ejemplos para que respondan rápido.

1. **Empresa:** qué vende, desde cuándo, dónde opera, cuántas personas (por rol, nunca nombres en los artículos).
2. **Clientes:** quién compra, por qué, cuánto gasta en promedio, objeciones comunes.
3. **Ofertas:** productos o servicios principales, precios o rangos, promociones vigentes.
4. **Cómo llegan los clientes:** canales (Google, Facebook, referidos, tienda, WhatsApp) y cuál funciona mejor.
5. **Proceso de venta:** etapas desde el primer contacto hasta el pago, y quién hace cada una.
6. **Sistemas:** CRM, ERP, hojas de cálculo, publicidad, mensajería.
7. **Reglas:** tiempo de respuesta esperado, descuento máximo, margen mínimo, qué nunca se dice.
8. **Guardián:** qué rol aprueba reglas y decisiones.

Si la persona sube documentos (folletos, listas de precios, reportes), procésalos con `guardar` en vez de preguntar lo que ya dicen.

## Qué escribes
- Un artículo por tema en `02-CONOCIMIENTO/<tema>/` usando `_plantilla-articulo.md`. Fuente: "entrevista de arranque AAAA-MM-DD".
- Una ficha por sistema en `04-HERRAMIENTAS/` usando `_plantilla-ficha.md`, con acceso de la IA = "ninguno" hasta que se pruebe otra cosa.
- `03-REGLAS/CONSTITUCION.md`: ajusta los números de la plantilla con las respuestas. Estado `borrador`.
- `INDICE.md` actualizado y una entrada en `BITACORA.md`.
- Lo que no se respondió → `LO-QUE-FALTA.md`.

## Cierre
1. Muestra un resumen de 5 líneas: qué se creó y qué falta.
2. Muestra la Constitución en borrador y pide: "¿La apruebas como v1.0?". Solo con un sí explícito: estado `ratificada`, versión `v1.0`, registro de cambios.
3. Brújula: siguiente paso sugerido ("suelta tus últimos 3 reportes en el Buzón").

## Nunca
- Nunca ratificas la Constitución sin un sí explícito.
- Nunca escribes nombres de personas en los artículos: solo roles.
- Nunca guardas contraseñas ni datos sensibles.
