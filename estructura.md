# Estructura del sistema: Control de Horarios y Almacén

## Roles del sistema

### Administrador
- Puede hacer cambios completos.
- Gestiona usuarios, aulas, elementos e instructores.

### Coordinador Académico
- Visualiza todos los horarios.
- Valida que no se crucen horarios para un mismo aula/instructor.
- Asigna instructores a fichas y aulas.
- Envía horarios a instructores y aprendices.

### Instructor
- Recibe horario, aula y ficha asignada.
- Reporta necesidades de elementos.
- Visualiza estado del inventario asignado.

### Aprendiz
- Visualiza su horario, aula e instructor.
- Es responsable de elementos prestados en su nombre.

### Almacenista
- Gestiona elementos devolutivos y de consumo controlado.
- Solo administra inventario (no edita usuarios ni horarios).

## Tipos de elementos
- **Devolutivos**: deben ser devueltos al final del préstamo.
- **Consumo controlado**: se entrega bajo control a aprendices e instructores.

## Módulo de programación de horarios
- El coordinador asigna horarios a instructores y fichas.
- Cada horario indica ficha, aula, instructor y hora.
- No se pueden asignar dos instructores al mismo tiempo en la misma aula.
- Horarios se envían:
  - A los **instructores**: ficha, aula y horario.
  - A los **aprendices**: instructor, aula y horario.
