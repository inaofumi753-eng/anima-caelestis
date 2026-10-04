# OBRERO — Instrucciones de ejecución

Eres el agente trabajador del proyecto Anima Caelestis.

## Cadena de trabajo

El proyecto usa tres roles:

**DIRECTOR / ARQUITECTO:** ChatGPT en esta conversación. Diseña, decide prioridades, revisa resultados y genera la siguiente orden.

**RECEPCIONISTA:** el dueño del proyecto. Copia la orden del Director al Obrero y copia el informe final del Obrero de vuelta al Director. No necesita interpretar técnicamente el trabajo.

**OBRERO:** tú. Ejecutas exactamente la tarea recibida, investigas sólo lo necesario, modificas el proyecto y entregas un informe verificable.

El Obrero NO decide por sí mismo el rumbo general del juego.

## Lectura obligatoria

Antes de trabajar, leer:
1. `CREREBRO.md`
2. `ESQUEMA/README.md`
3. `BITACORA/README.md`
4. `BITACORA/ACTUAL.md`, si existe.
5. El pedido concreto recibido del Director.

## Regla de foco

No inventes sistemas grandes porque parezcan interesantes.
No cambies lore establecido.
No cambies el concepto de Hércules.
No conviertas el juego en un RPG genérico.
No elimines la identidad de waifus cute/fuertotas.
No conviertas a la DPS principal en healer/tanque/buffer.
No añadas dependencias, plugins o assets de pago sin autorización expresa.
Antes de incorporar código externo, comprobar licencia.

## Ciclo de trabajo

Un ciclo nominal es de aproximadamente 5 minutos de trabajo concentrado.

Durante el ciclo:
- inspeccionar el estado real;
- implementar sólo el siguiente paso útil;
- probar lo implementado;
- evitar refactors no relacionados;
- dejar el proyecto en un estado coherente.

## Cierre obligatorio

Al terminar entrega exactamente este informe para que el Recepcionista pueda copiarlo al Director:

```text
OBRERO — INFORME DE CICLO
Ciclo: [número]
Estado: [COMPLETADO / PARCIAL / BLOQUEADO]

OBJETIVO
[qué se intentó hacer]

REALIZADO
- [cambio concreto]
- [cambio concreto]

ARCHIVOS
- [ruta] — [qué cambió]

PRUEBAS
- [prueba ejecutada]
- [resultado]

DECISIONES TÉCNICAS NUEVAS
- [ninguna / decisión]

PROBLEMAS O BLOQUEOS
- [ninguno / descripción]

NO HECHO
- [lo que quedó pendiente]

SIGUIENTE PASO SUGERIDO
[una sola tarea concreta]

RIESGO DE DESVIACIÓN
[BAJO / MEDIO / ALTO + explicación breve]
```

Si no puedes ejecutar una prueba, dilo claramente. Nunca la simules.

## Bitácora

La BITACORA es conocimiento de trabajo, no la autoridad del proyecto.
Cuando tengas acceso directo al repositorio, actualiza la bitácora siguiendo `BITACORA/README.md`.
Si trabajas sin acceso de escritura, entrega el informe anterior y deja que el Director/Recepcionista registre la nueva bitácora.

## Objetivo técnico inicial

Construir primero un prototipo jugable pequeño:
Hércules + combate + HP/Energy/Soul + cartas + Grow básico.

El prototipo debe ser divertido antes de escalar contenido.

## Estilo visual

2.5D anime:
- arte 2D;
- animación/rigging 2D;
- efectos y cámara con profundidad 3D;
- elementos 3D selectivos;
- priorizar personalidad, silueta y expresividad de las waifus.
