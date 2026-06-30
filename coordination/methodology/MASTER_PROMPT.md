# Prompt maestro reutilizable

Copia este prompt en un nuevo chat con Codex cuando quieras iniciar esta metodologia.

```md
Quiero trabajar con una metodologia cooperativa entre Codex, Claude y yo usando el repositorio como fuente de comunicacion compartida.

Tu seras Codex. Tu trabajo no es solo responderme, sino organizar el proyecto, crear una carpeta de coordinacion y preparar todo para que otro modelo pueda leer el contexto, responder y colaborar contigo sin depender de mi memoria.

## Objetivo inicial

[ESCRIBIR AQUI LA IDEA, PROBLEMA O INTENCION DEL PROYECTO. Si no tengo idea concreta, ayudame a descubrir una.]

## Filosofia

- No asumir que la primera idea es la buena.
- Pensar antes de construir.
- Comparar potencial, viabilidad, motivacion y riesgo.
- Mantener un flujo limpio, sin repetir pasos ni dispersarnos.
- Dejar siempre contexto escrito para que otro modelo pueda continuar.
- Convertir decisiones en tareas concretas.
- Priorizar terminar algo pequeno, util y validable.

## Carpeta de coordinacion

Crea `coordination/` con:

- `README.md`
- `PROJECT_BRIEF.md`
- `USER_ORIGINAL_MESSAGE.md`
- `COLLABORATION_PROTOCOL.md`
- `TASK_BOARD.md`
- `DECISIONS.md`
- `PROJECT_TRUTHS.md`
- `DISAGREEMENTS.md`
- `IDEA_GRAVEYARD.md`
- `SCOPE_GUARDRAILS.md`
- `QUESTIONS_FOR_USER.md`
- `QUESTIONS_FOR_CLAUDE.md`
- `QUESTIONS_FOR_CODEX.md`
- `HANDOFF.md`

## Regla de independencia

Si Claude u otro modelo debe dar criterio independiente, prepara `PROMPT_FOR_CLAUDE_BLIND.md`.

Ese archivo debe indicar que Claude responda primero sin leer la respuesta de Codex.

## Flujo

1. Entender el objetivo.
2. Crear la carpeta de coordinacion.
3. Escribir brief y protocolo.
4. Hacer ronda ciega si buscamos criterio independiente.
5. Comparar respuestas.
6. Registrar desacuerdos.
7. Hacer red team de la idea finalista.
8. Decidir.
9. Crear roadmap y tareas.
10. Ejecutar y verificar.
```

