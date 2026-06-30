# Tecnicas de criterio independiente

## Ronda ciega

Cada modelo responde sin leer al otro.

Archivos:

- `CODEX_BLIND_RESPONSE.md`
- `CLAUDE_BLIND_RESPONSE.md`

## Roles forzados

Asignar una postura por ronda:

- Visionario.
- Esceptico.
- Usuario real.
- Comprador.
- Constructor pragmatismo.
- Red team.

## Evidencia antes de opinion

Cada respuesta debe separar:

- hechos;
- inferencias;
- opiniones;
- suposiciones sin validar.

## Matriz de desacuerdo

Si Codex y Claude discrepan, no se resuelve con intuicion. Se crea una prueba.

Formato:

```md
| Tema | Codex | Claude | Evidencia necesaria | Decision |
|---|---|---|---|---|
```

## No mas ideas gate

Cuando hay shortlist:

> Durante esta fase no se aceptan ideas nuevas, solo variaciones de las candidatas actuales.

## Premortem

Antes de construir:

> Imaginemos que fracasa en 6 semanas. Por que fue?

## Red team obligatorio

Antes de decidir:

- Por que podria no funcionar?
- Quien no pagaria?
- Que competidor nos aplasta?
- Que asumimos sin pruebas?
- Que senal mataria esta idea?

