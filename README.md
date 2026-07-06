# TKP — TORO Knowledge Protocol

TKP es la fuente de verdad operativa del ecosistema TORO.

No intenta crear una memoria mágica compartida entre agentes. Define un protocolo simple, versionado y mantenible para que cualquier persona, IA o coder pueda entender el estado actual, las decisiones vigentes y el próximo paso de cada proyecto.

## Regla principal

Antes de trabajar sobre cualquier proyecto TORO, un agente debe leer primero:

```txt
02_source_of_truth/CURRENT_STATE.md
```

Luego debe revisar, según corresponda:

- `02_source_of_truth/sources-of-truth.md`
- `02_source_of_truth/operating_rules.md`
- `05_projects/<PROJECT>/current_state.md`
- `03_decisions/`
- `04_sessions/`
- `06_handoffs/`

## Para qué sirve

TKP sirve para:

- registrar decisiones importantes;
- evitar discusiones repetidas;
- coordinar handoffs entre agentes;
- mantener contexto vivo por proyecto;
- permitir que un coder entre rápido sin reconstruir toda la historia;
- separar estado vigente de historial operativo.

## Cómo usarlo

### 1. Ver estado actual

Leer:

```txt
02_source_of_truth/CURRENT_STATE.md
```

### 2. Registrar una decisión

Copiar el template:

```txt
03_decisions/DEC-000_TEMPLATE.md
```

Crear un nuevo archivo siguiendo el patrón:

```txt
03_decisions/DEC-001-nombre-breve.md
```

Luego actualizar:

- `02_source_of_truth/sources-of-truth.md`
- `05_projects/<PROJECT>/decisions.md`
- `09_meta/changelog.md` si corresponde

### 3. Registrar una sesión

Copiar:

```txt
07_templates/SESSION_TEMPLATE.md
```

Guardar en:

```txt
04_sessions/YYYY/MM/SESSION-XXX-nombre-breve.md
```

### 4. Crear un handoff

Copiar:

```txt
06_handoffs/HANDOFF_TEMPLATE.md
```

Usar cuando un agente, coder o persona entrega contexto a otro.

## Qué NO hacer

- No convertir `04_sessions/` en la fuente principal de verdad.
- No mezclar decisiones vigentes con notas sueltas.
- No modificar decisiones aprobadas sin crear una nueva decisión que la reemplace.
- No introducir backend, dashboard, embeddings ni automatizaciones antes de Sprint 2+.
- No trabajar sin leer `CURRENT_STATE.md`.

## Estado del producto

Versión actual: `v0.1.0 — Sprint 1 Foundation MVP`.

Ver roadmap en:

```txt
09_meta/sprint_plan.md
```
