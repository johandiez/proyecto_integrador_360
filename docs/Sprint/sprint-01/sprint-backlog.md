# Sprint 1 — Sprint Backlog

## Información general

- *Proyecto:* Salud360
- *Sprint:* Sprint 1
- *Objetivo:* Construir el núcleo administrativo y la estructura clínica inicial del sistema.
- *Duración:* Por definir por el equipo.
- *Versión objetivo:* v0.1.0

## Objetivo del Sprint

Desplegar el núcleo administrativo y la estructura clínica base para permitir el registro de pacientes, la asignación de profesionales, la gestión de especialidades, el agendamiento de citas y la creación de historias clínicas.

## Historias seleccionadas

| ID | Historia de usuario | Prioridad | Estimación | Estado |
|---|---|---|---:|---|
| HU01 | Registrar paciente | Alta | 5 | To Do |
| HU02 | Registrar profesional | Alta | 5 | To Do |
| HU03 | Registrar especialidad | Alta | 3 | To Do |
| HU04 | Agendar cita médica | Alta | 5 | To Do |
| HU05 | Crear historia clínica | Alta | 5 | To Do |

*Total estimado:* 23 puntos.

## Tareas del Sprint

### HU01 — Registrar paciente

- Diseñar la estructura de datos del paciente.
- Crear el formulario de registro.
- Validar campos obligatorios.
- Validar identificación única.
- Probar el registro de pacientes.

### HU02 — Registrar profesional

- Diseñar la estructura de datos del profesional.
- Crear el formulario de registro.
- Registrar licencia profesional.
- Relacionar el profesional con una especialidad.
- Probar el registro de profesionales.

### HU03 — Registrar especialidad

- Diseñar la estructura de datos de especialidades.
- Crear el formulario de registro.
- Validar nombres duplicados.
- Permitir asociar profesionales.
- Probar el registro de especialidades.

### HU04 — Agendar cita médica

- Diseñar la estructura de datos de citas.
- Relacionar paciente y profesional.
- Registrar fecha, hora y motivo.
- Definir estados de la cita.
- Probar el agendamiento.

### HU05 — Crear historia clínica

- Diseñar la estructura de la historia clínica.
- Relacionar la historia con el paciente.
- Validar que exista una sola historia por paciente.
- Registrar antecedentes y alergias iniciales.
- Probar la creación de historias clínicas.

## Criterios generales de terminado

Una historia se considera terminada cuando:

- Cumple sus criterios de aceptación.
- La información queda almacenada correctamente.
- Se validan los campos obligatorios.
- Se realizan pruebas funcionales.
- El código se encuentra versionado en GitHub.
- La documentación correspondiente está actualizada.
- El equipo revisa y acepta el resultado.

## Dependencias

1. Para registrar un profesional debe existir al menos una especialidad.
2. Para agendar una cita deben existir un paciente y un profesional.
3. Para crear una historia clínica debe existir un paciente.
4. Las historias clínicas deben relacionarse con un único paciente.

## Resultado esperado

Al finalizar el Sprint 1, el sistema debe permitir:

- Registrar pacientes.
- Registrar especialidades.
- Registrar profesionales.
- Asociar profesionales con especialidades.
- Agendar citas médicas.
- Crear una historia clínica por paciente.