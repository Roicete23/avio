# Flujo optimo recomendado

## Fase 1: Captura

Guardar el mensaje original del usuario en:

- `USER_ORIGINAL_MESSAGE.md`

Crear:

- `PROJECT_BRIEF.md`
- `PROJECT_TRUTHS.md`

## Fase 2: Pensamiento independiente

Si necesitamos criterio creativo o estrategico:

1. Codex prepara `PROMPT_FOR_CLAUDE_BLIND.md`.
2. Claude responde sin leer a Codex.
3. Codex responde por separado.
4. Se comparan respuestas.

Salida:

- `CODEX_FIRST_RESPONSE.md`
- `CLAUDE_FIRST_RESPONSE.md`
- `SYNTHESIS.md`

## Fase 3: Desacuerdo util

Registrar diferencias en:

- `DISAGREEMENTS.md`

Cada desacuerdo debe tener:

- posicion de Codex;
- posicion de Claude;
- evidencia necesaria;
- decision o experimento.

## Fase 4: Red team

Antes de decidir:

- crear `RED_TEAM_REVIEW.md`;
- listar razones de fracaso;
- definir senales de invalidacion.

## Fase 5: Decision

Guardar decisiones en:

- `DECISIONS.md`

Mover ideas descartadas a:

- `IDEA_GRAVEYARD.md`

## Fase 6: Accion

Crear:

- `ROADMAP.md`
- `WEEK_1_TASKS.md`
- `TASK_BOARD.md`

Regla:

> Una fase no esta completa hasta que tiene una salida visible: archivo, landing, prototipo, tracker, decision o prueba.

