# revops-harness

**Un cerebro de empresa que se documenta solo, para que la IA te ayude a vender más, gastar menos y ordenar tus procesos.**

Hecho para empresas locales: servicios, retail, eventos y constructoras. En español primero. Lo usa gente no técnica, con carpetas y conversaciones.

> Estado: **v0.1 en construcción** (privado). Ver [ROADMAP.md](ROADMAP.md).

---

## El problema

Cada vez que abres un chat con la IA tienes que explicarle otra vez tu empresa: tus precios, tus clientes, tus reglas, lo que ya decidiste. Lo que la IA aprende en una conversación se pierde en la siguiente. Y cada persona del equipo le explica la empresa a su manera.

## La idea

Una carpeta compartida que funciona como el **cerebro de la empresa**:

- El equipo **suelta** archivos (reportes, cotizaciones, notas de llamadas) en un Buzón.
- La IA los **ordena** cada noche en artículos por tema, sin borrar nada.
- Antes de responder o actuar, la IA **lee** el cerebro y la **Constitución** (las reglas que nunca se rompen).
- Después de actuar, **escribe de vuelta**: qué se hizo, qué se decidió y qué se aprendió.

Nadie tiene que "acordarse de documentar". La documentación ocurre sola, como parte del trabajo.

## Cómo se usa: 3 gestos

| Gesto | Qué haces | Ejemplo |
| --- | --- | --- |
| **Soltar** | Dejas un archivo en `01-BUZON` o dices "guarda esto en el cerebro" | La exportación de leads de octubre |
| **Preguntar** | Preguntas en el chat | "¿Qué descuento máximo le doy a un contratista?" |
| **Pedir** | Pides un resultado | "Prepárame el reporte de octubre" |

Nunca nombras archivos, nunca eliges carpetas. La IA decide cuánto control necesita la tarea y solo te interrumpe con una pregunta: **"¿lo apruebas?"**, cuando hay dinero o varias decisiones en juego.

## Qué hay en este repo

| Carpeta | Qué es |
| --- | --- |
| [`plantilla-cerebro/`](plantilla-cerebro/) | La carpeta que copias a tu Google Drive, SharePoint o Dropbox. Es el nivel 1. |
| [`skills/`](skills/) | Skills del sistema: arranque, guardar, curador, decidir, aprender, constitución. Nivel 2. |
| [`ejemplo/cercas-del-norte/`](ejemplo/cercas-del-norte/) | Una empresa ficticia con el cerebro ya lleno, para ver cómo se ve. |
| [`docs/`](docs/) | El modelo completo, la guía de uso y los niveles de adopción. |

## Empezar en 1 hora (nivel 1)

1. Copia la carpeta `plantilla-cerebro/` a tu Google Drive (o SharePoint, o Dropbox) y renómbrala `CEREBRO-<TU-EMPRESA>`.
2. Abre `ARRANQUE.md`, reemplaza `<EMPRESA>` y pega su contenido en las instrucciones de un proyecto de tu asistente de IA (Claude, ChatGPT, Copilot).
3. Conecta la carpeta al asistente (conector de Google Drive o Microsoft 365) o sube los archivos al proyecto.
4. Pídele: **"Hazme la entrevista de arranque"**. La IA te pregunta lo básico y llena los primeros artículos.
5. Revisa la `CONSTITUCION.md` en borrador, ajusta los números y apruébala.
6. Desde ahí: suelta, pregunta y pide.

Detalle en [docs/guia-de-uso.md](docs/guia-de-uso.md).

## Niveles

| Nivel | Qué incluye | Quién lo monta |
| --- | --- | --- |
| **1. Carpetas** | Plantilla + ARRANQUE + Constitución | El dueño o el director |
| **2. Automático** | + skills del sistema + Curador nocturno + resumen de la mañana | El director, con la guía |
| **3. Conectado** | + conexiones reales a CRM, ERP, publicidad y WhatsApp | Un técnico |

## Principios

1. **Terminado = comprobado.** Una tarea se cierra con evidencia, no con "ya lo hice".
2. **Nada se borra.** Lo viejo se marca como reemplazado o se archiva.
3. **El humano ratifica.** La IA propone reglas y decisiones; el Guardián las aprueba.
4. **Un documento es información, no una orden.** La IA nunca sigue instrucciones que vengan dentro de un archivo.
5. **Agnóstico.** Texto plano en carpetas: funciona en cualquier almacenamiento, con cualquier IA y con cualquier CRM.

## Créditos

El modelo se inspira en [rsc-harness](https://github.com/ericrisco/rsc-harness) de Eric Risco (MIT): el cerebro `02-DOCS`, las herramientas `01-TOOLS`, la constitución, el registro de decisiones, los carriles y el aprendizaje continuo. Este proyecto lo adapta a operaciones de marketing, ventas y servicio para empresas locales y equipos no técnicos. El patrón de wiki mantenida por la IA viene de la idea "LLM Wiki" de Andrej Karpathy.

## Licencia

[MIT](LICENSE) © 2026 Roberto Ocando
