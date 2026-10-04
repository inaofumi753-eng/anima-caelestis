# BITACORA

La BITACORA es un registro rotativo de trabajo.

## Función

Registra únicamente el estado operativo reciente para que el siguiente ciclo pueda continuar sin perder tiempo.

La autoridad permanente está en:
- `CREREBRO.md`
- `ESQUEMA/README.md`

## Flujo Director → Recepcionista → Obrero → Recepcionista → Director

1. El Director crea una orden concreta.
2. El Recepcionista la copia al Obrero.
3. El Obrero trabaja durante un ciclo nominal de 5 minutos.
4. El Obrero entrega el informe estandarizado.
5. El Recepcionista copia ese informe al Director.
6. El Director revisa el resultado contra CREREBRO y ESQUEMA.
7. El Director genera la siguiente orden.
8. Se repite el ciclo.

El Recepcionista no necesita resumir ni reinterpretar el informe técnico: debe copiarlo lo más fielmente posible.

## Rotación

Cuando se genere una nueva bitácora:
- conservar sólo el estado más reciente en `BITACORA/ACTUAL.md`;
- la anterior puede sustituirse;
- nunca borrar CREREBRO.md;
- nunca borrar ESQUEMA/.

## Información mínima que debe sobrevivir

- ciclo;
- objetivo;
- estado;
- trabajo realizado;
- archivos modificados;
- pruebas;
- decisiones nuevas;
- bloqueos;
- siguiente paso.

## Regla

Una bitácora NO puede introducir una decisión maestra contradictoria. Si aparece un conflicto, se registra como conflicto y el Director decide.
