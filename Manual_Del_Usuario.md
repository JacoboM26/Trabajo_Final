## Manual de Usuario del Sistema de Gestión EPS.
** Introducción.
El sistema de gestión EPS permite administrar citas médicas y registrar eventos asociados a los pacientes. Este software tiene dos modos principales:

- Usuario: Para consultar citas.
- Administrador: Para gestionar usuarios, citas y eventos.

## Requisitos:
- Python instalado en el sistema.
- Conexión a internet no es necesaria, ya que el programa funciona de manera local.

## Guía de Uso
- Menú Principal:
- Consultar Cita: Permite ingresar una cédula para revisar si existe una cita registrada.
- Ingresar cédula: El sistema mostrará la información de la cita, si existe.

- Menú Administrador:
- Requiere una contraseña (admin123). Una vez autenticado, se accede a las funciones administrativas.

- Salir:
- Finaliza el programa.

## Funciones del Administrador
- Agregar Usuario y Cita:
Permite registrar un nuevo paciente y asignar una cita.
- Ingresar cédula.
- Especificar fecha (YYYY-MM-DD) y hora (HH:MM).
- Confirmar o Cancelar Cita:
Permite actualizar el estado de una cita existente.
- Ingresar cédula.
- Seleccionar una acción: confirmar o cancelar.
- Generar Reporte:
Muestra un listado de todas las citas registradas y los eventos asociados a cada paciente.
- Añadir Evento:
Permite registrar un evento relacionado con un paciente.
- Ingresar cédula y descripción del evento.
## Ejemplo de Uso
1. Consultar Cita:
Usuario ingresa su cédula: 12345678.
- El sistema responde:
Cédula: 12345678
Fecha: 2024-12-15
Hora: 10:00
Estado: pendiente
2. Confirmar una Cita:
- Administrador ingresa al menú, selecciona la opción 2, e introduce la cédula del paciente:
Cita confirmada.
- Adicionalmente: 
- Los datos se gestionan en memoria, por lo que no persisten después de cerrar el programa.
- La contraseña del administrador predeterminada es admin123.
