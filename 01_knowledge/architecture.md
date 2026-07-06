# Architecture

## Sprint 1 Architecture

TKP v0.1.0 usa una arquitectura deliberadamente simple:

```txt
Markdown files + Git history + explicit conventions
```

## Capas

### 1. Knowledge

Conocimiento relativamente estable: glosario, arquitectura, principios y agentes.

### 2. Source of Truth

Estado vigente: estado actual, reglas operativas, proyectos activos y fuentes válidas.

### 3. Decisions

Decisiones aprobadas, propuestas, reemplazadas o archivadas.

### 4. Sessions

Historial operativo de conversaciones y jornadas de trabajo.

### 5. Projects

Contexto vivo por proyecto.

### 6. Handoffs

Transferencia de contexto accionable.

### 7. Templates

Formatos reutilizables para mantener consistencia.

### 8. Meta

Roadmap, sprint plan, changelog y backlog.

## Evolución futura

La arquitectura debe crecer por sprints: CLI, indexador, búsqueda, context builder, handoff engine, dashboard y memory bus.
