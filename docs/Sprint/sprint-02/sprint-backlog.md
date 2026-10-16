# Sprint 02 Backlog - Salud360

Proyecto: Salud360  
Sprint: Sprint 2  
Objetivo: Ampliar la historia clínica, incorporar diagnósticos y tratamientos, y comenzar la gestión de medicamentos y prescripciones.  
Duración: Por definir  
Versión objetivo: v0.2.0

## Historias de usuario (con estimaciones en puntos)
- HU13 — Registrar diagnóstico
    - Criterios de aceptación:
        - Asociar diagnóstico a una consulta y paciente.
        - Registrar código/nombre y descripción.
        - Fecha y hora automáticas.
- HU14 — Registrar tratamiento
    - Criterios de aceptación:
        - Vincular tratamiento al paciente y al diagnóstico.
        - Descripción, inicio y fin estimados.
- HU15 — Registrar medicamento (catálogo)
    - Criterios de aceptación:
        - Nombre, presentación, concentración.
        - Identificador único.
- HU16 — Registrar prescripción
    - Criterios de aceptación:
        - Selección de paciente y medicamento.
        - Dosis, frecuencia, duración.
        - Vinculación con profesional emisor.
- HU17 — Consulta de diagnósticos y tratamientos
    - Criterios de aceptación:
        - Ver historial de diagnósticos y tratamientos por paciente.
- HU18 — Consulta de medicamentos y prescripciones
    - Criterios de aceptación:
        - Ver catálogo de medicamentos y prescripciones del paciente.
- HU19 — Evolución clínica (seguimiento)
    - Criterios de aceptación:
        - Registrar notas de evolución asociadas a consultas.
- HU20 — Seguridad y control de acceso (opcional para versión 0.2)
    - Criterios de aceptación:
        - Roles y permisos básicos (admin, profesional, admin clínico).

## Dependencias
- HU13 requiere HU04 (citas) o al menos acceso a consultas.
- HU16 y HU17 dependen de pacientes e historiales creados (HU05/HU07).
- HU15 debe existir el catálogo de medicamentos (HU15 o HU03 de farmacología en backlog).