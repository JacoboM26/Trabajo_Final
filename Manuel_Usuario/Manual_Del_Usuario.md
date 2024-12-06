## Manual de Usuario: Sistema de Gestión AgendApp
## Descripción del Sistema
El sistema de gestión AgendApp es un programa de consola diseñado para administrar y gestionar las citas médicas de los pacientes. Los usuarios pueden consultar, confirmar o cancelar sus citas, mientras que los administradores tienen acceso a funciones avanzadas como la creación de citas y generación de reportes.
## Instrucciones Generales
1. Ejecución del Programa:
   Abre el programa desde tu entorno de desarrollo o consola de Python y sigue las instrucciones en pantalla.

2. Menú Principal:
   Cuando inicie el programa, verás un menú con las siguientes opciones:
   - 1. Consultar cita: Permite consultar los detalles de tu cita usando tu cédula.
   - 2. Confirmar o cancelar cita: Permite confirmar o cancelar tu cita.
   - 3. Menú Administrador: Requiere una contraseña para acceder a funciones avanzadas.
   - 4. Salir: Finaliza el programa.
## Funciones para Usuarios
1. Consultar cita
- Ingresa tu cédula cuando el sistema lo solicite.
- El sistema mostrará la información de tu cita:
  - Fecha
  - Hora
  - Estado (pendiente, confirmada o cancelada)
2. Confirmar o cancelar cita
- Ingresa tu cédula cuando el sistema lo solicite.
- Selecciona la opción deseada:
  - 1. Confirmar cita: Cambia el estado de la cita a 'confirmada'.
  - 2. Cancelar cita: Cambia el estado de la cita a 'cancelada'.

Nota: Si no tienes una cita registrada, el sistema te notificará.
## Funciones para Administradores
Acceso al Menú Administrador
1. Selecciona la opción '3. Menú Administrador' en el menú principal.
2. Ingresa la contraseña de administrador (admin123 por defecto).

Opciones en el Menú Administrador
1. Agregar usuario y cita:
   - Ingresa la cédula, fecha y hora de la cita.
   - El sistema registrará los datos y la cita quedará en estado 'pendiente'.

2. Confirmar o cancelar cita:
   - Similar a la opción para usuarios, pero permite administrar citas de cualquier cédula.

3. Generar reporte:
   - Muestra un listado con todas las citas registradas:
     - Cédula, fecha, hora y estado.
   - También muestra un historial de eventos por cédula.

4. Salir al menú principal:
   - Regresa al menú principal.

## Ejemplo de Uso
Caso: Usuario
1. Un paciente con cédula 12345678 abre el programa.
2. Selecciona la opción 1. Consultar cita.
   - El sistema muestra:
     - Fecha: 2024-12-15
     - Hora: 10:30
     - Estado: pendiente
3. El paciente decide confirmar su cita:
   - Selecciona la opción 2. Confirmar o cancelar cita.
   - Ingresa su cédula y selecciona '1. Confirmar cita'.
   - El sistema confirma la cita y muestra un mensaje de éxito.
Caso: Administrador
1. El administrador accede al menú con la contraseña.
2. Selecciona la opción 1. Agregar usuario y cita.
   - Ingresa:
     - Cédula: 87654321
     - Fecha: 2024-12-20
     - Hora: 14:00
   - El sistema registra la cita en estado 'pendiente'.
3. El administrador genera un reporte seleccionando la opción 3. Generar reporte.
   - Se muestra un listado con todas las citas y eventos registrados.
## Errores Comunes
1. Cédula no encontrada:
   - Si ingresas una cédula no registrada, el sistema te notificará.
   - Asegúrate de que la cédula es correcta o consulta al administrador.

2. Contraseña incorrecta:
   - Si fallas al ingresar la contraseña en el menú de administrador, no podrás acceder.
   - Verifica que usas la contraseña correcta: admin123.
## Sugerencias de uso
- Confirmar tu cita con anticipación: Esto ayuda a mantener el orden en el sistema.
- Los administradores deben generar reportes periódicos: Así podrán supervisar el estado de las citas.

