# Sources of Truth

Este archivo lista las fuentes vigentes que deben prevalecer sobre notas viejas, sesiones sueltas o interpretaciones parciales.

## Orden de prioridad

1. `02_source_of_truth/CURRENT_STATE.md`
2. `02_source_of_truth/operating_rules.md`
3. `03_decisions/` con estado `Aprobada`
4. `05_projects/<PROJECT>/current_state.md`
5. `05_projects/<PROJECT>/decisions.md`
6. `06_handoffs/` vigentes
7. `04_sessions/` como historial, no como verdad principal

## Regla

Si una sesión contradice una decisión aprobada, prevalece la decisión aprobada.

Si una decisión fue reemplazada, debe indicarse en el campo `Estado` y referenciar la nueva decisión.
