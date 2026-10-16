# Historias de usuario — Salud360
## HU01 — Registrar paciente
**Como** personal administrativo,  
**quiero** registrar la información personal de un paciente,  
**para** mantener sus datos organizados y disponibles en Salud360.
### Criterios de aceptación
- Registrar identificación única, nombre completo y fecha de nacimiento.
- Registrar teléfono, correo electrónico y contacto de emergencia.
- Validar los campos obligatorios.
- Evitar registros duplicados por número de identificación.
## HU02 — Registrar profesional
**Como** administrador,  
**quiero** registrar los profesionales de salud,  
**para** gestionar las personas encargadas de atender a los pacientes.
### Criterios de aceptación
- Registrar identificación, nombre completo y licencia profesional.
- Registrar teléfono y correo electrónico.
- Asociar el profesional con al menos una especialidad médica.
- Validar los campos obligatorios.
## HU03 — Registrar especialidad
**Como** administrador,  
**quiero** registrar especialidades médicas,  
**para** clasificar correctamente a los profesionales de salud.
### Criterios de aceptación
- Registrar el nombre de la especialidad.
- Registrar una descripción operativa.
- Permitir vincular varios profesionales a una especialidad.
- Evitar especialidades con nombres duplicados.
## HU04 — Agendar cita médica
**Como** personal administrativo,  
**quiero** registrar una cita entre un paciente y un profesional,  
**para** organizar la atención médica.
### Criterios de aceptación
- Seleccionar un paciente previamente registrado.
- Seleccionar un profesional previamente registrado.
- Definir fecha, hora y motivo de la consulta.
- Establecer el estado inicial de la cita como `pendiente`.
- Permitir los estados `pendiente`, `atendida` y `cancelada`.
## HU05 — Crear historia clínica
**Como** profesional de salud,  
**quiero** disponer de una historia clínica para cada paciente,  
**para** almacenar la información relevante de sus atenciones.
### Criterios de aceptación
- Vincular una única historia clínica con cada paciente.
- Registrar antecedentes médicos y alergias conocidas.
- Conservar el historial de consultas.
- Evitar la creación de historias clínicas duplicadas para un paciente.
## HU06 — Consultar historia clínica
**Como** profesional de salud,  
**quiero** consultar la historia clínica de un paciente,  
**para** conocer sus antecedentes antes de la consulta.
### Criterios de aceptación
- Buscar pacientes por identificación o nombre.
- Mostrar datos personales, antecedentes y alergias.
- Mostrar cronológicamente las consultas.
- Mostrar diagnósticos y tratamientos previos.
## HU07 — Registrar diagnóstico
**Como** profesional de salud,  
**quiero** registrar el diagnóstico de un paciente,  
**para** mantener actualizada su historia clínica.
### Criterios de aceptación
- Asociar el diagnóstico con una consulta y un paciente.
- Registrar el código o nombre del diagnóstico.
- Registrar una descripción detallada.
- Registrar automáticamente la fecha y hora.
## HU08 — Registrar tratamiento
**Como** profesional de salud,  
**quiero** registrar el tratamiento indicado a un paciente,  
**para** mantener la trazabilidad de su atención.
### Criterios de aceptación
- Asociar el tratamiento con el paciente.
- Asociar el tratamiento con el diagnóstico correspondiente.
- Registrar la descripción del tratamiento.
- Registrar fecha de inicio y fecha estimada de terminación.
## HU09 — Registrar medicamento
**Como** administrador,  
**quiero** registrar los medicamentos disponibles,  
**para** utilizarlos posteriormente en las prescripciones médicas.
### Criterios de aceptación
- Registrar el nombre comercial o genérico.
- Registrar la presentación.
- Registrar la concentración.
- Asignar un identificador único.
- Evitar medicamentos duplicados.
## HU10 — Registrar prescripción
**Como** profesional de salud,  
**quiero** registrar los medicamentos formulados a un paciente,  
**para** mantener el registro del tratamiento farmacológico.
### Criterios de aceptación
- Seleccionar un paciente registrado.
- Seleccionar un medicamento del catálogo.
- Registrar dosis, frecuencia y duración.
- Vincular la prescripción con el profesional que la emite.
## HU11 — Registrar signos vitales
**Como** profesional de salud,  
**quiero** registrar los signos vitales durante la consulta,  
**para** monitorear el estado físico del paciente.
### Criterios de aceptación
- Registrar peso en kilogramos.
- Registrar talla en centímetros.
- Registrar temperatura en grados Celsius.
- Registrar presión arterial.
- Registrar frecuencia cardíaca.
- Registrar saturación de oxígeno.
- Relacionar los signos vitales con una consulta activa.
## HU12 — Registrar alergias y antecedentes
**Como** profesional de salud,  
**quiero** registrar alergias y antecedentes médicos,  
**para** prevenir riesgos en futuras atenciones.
### Criterios de aceptación
- Registrar alergias a medicamentos o agentes externos.
- Registrar antecedentes patológicos.
- Registrar antecedentes quirúrgicos.
- Registrar antecedentes familiares.
- Vincular permanentemente la información con la ficha del paciente.