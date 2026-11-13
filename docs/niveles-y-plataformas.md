# Niveles y plataformas

## Niveles de adopción

| Nivel | Qué incluye | Quién lo monta | Tiempo | Se pasa al siguiente cuando… |
| --- | --- | --- | --- | --- |
| **1. Carpetas** | Plantilla, 00-LEEME, ARRANQUE en un proyecto de la IA, Constitución inicial. Procesar el Buzón se pide a mano. | Dueño o director | 1 a 2 horas | El equipo usa el Buzón cada semana durante un mes |
| **2. Automático** | + skills del sistema + Curador nocturno + resumen de la mañana | Director, con la guía | 1 día | Hay al menos 10 decisiones y lecciones registradas |
| **3. Conectado** | + conexiones reales a CRM, ERP, publicidad y WhatsApp (solo lectura primero) | Técnico | 1 a 4 semanas | — |

El nivel 1 tiene que funcionar sin ninguna skill. Si no funciona sin skills, no es sencillo.

## Almacenamiento

El cerebro es texto plano (`.md`) en carpetas. No depende de ninguna función propia de la plataforma.

| Plataforma | Lectura por la IA | Escritura automática | Notas |
| --- | --- | --- | --- |
| **Google Drive** | Sí, con el conector de Drive | Viable con el conector (crear y actualizar archivos) | Recomendado para el piloto. Probar en cada cuenta. |
| **SharePoint / OneDrive** | Sí, con el conector de Microsoft 365 | Por probar | Si el conector no escribe, el Curador corre desde una app de escritorio con la carpeta sincronizada. |
| **Dropbox / carpeta local** | Con conector o carpeta sincronizada | Con app de escritorio | Útil para empresas pequeñas. |

> Verifica siempre qué permite tu plan y tu conector antes de prometer automatización al equipo.

## Formato de archivos

- Lo que escribe la IA: `.md` (Markdown, texto plano). Portable, legible por cualquier IA y por personas.
- Drive y SharePoint muestran `.md` sin formato. La forma normal de leer el cerebro es **preguntarle a la IA**. Para verlo bonito, abre la carpeta en [Obsidian](https://obsidian.md) (gratis).
- Los originales del Buzón se guardan en su formato en `05-ARCHIVO`.

## IA

`ARRANQUE.md` está en lenguaje normal: funciona como instrucciones de proyecto en Claude, ChatGPT, Copilot o Gemini. Las skills de `skills/` usan el formato de Agent Skills (Claude). En asistentes sin skills, el contenido de una skill se pega como instrucción.

## Curador nocturno (nivel 2)

El Curador es una tarea programada que corre la skill `curador` cada noche. Opciones:
- Una tarea programada de tu asistente de IA (por ejemplo, tareas programadas de Claude).
- Un flujo en Make, n8n o Zapier que dispare al asistente.
- Manual: el Guardián escribe *"corre el curador"* al empezar el día.
