# Desafío de Oracle

## Contexto:

Imagina que estás trabajando en un proyecto de gestión de empleados. Se requiere un conjunto de procedimientos almacenados en Oracle para realizar operaciones específicas en la base de datos.

## 1. Creación de un Paquete:

Crea un paquete llamado `GestionEmpleados` que incluya los siguientes elementos:

### Procedimiento: PrcCrearEmpleado

- **Parámetros:** Nombre, Apellido, Salario, Departamento.
- **Descripción:** Debe insertar un nuevo empleado en una tabla llamada `Empleados`.

### Procedimiento: ActualizarSalarioPrc

- **Parámetros:** ID del empleado, Nuevo Salario.
- **Descripción:** Debe actualizar el salario de un empleado existente.

## 2. Prueba de los Componentes:

Escribe un script PL/SQL que demuestre el uso de cada procedimiento del paquete (`GestionEmpleados`). Esto debería incluir la creación de empleados y la actualización de salarios.

# Entrega:

1. Debes crear un repositorio publico en github o gitlab (el que mejor te acomode), dejar tu solución en el repo y enviarme el link al correo.
2. Ganas puntos si utilizaste branches diferentes al momento de desarrollar el desafío
3. Ganas puntos si hiciste una o mas Pull Request para dejar tus desarrollos en el branch "main"
4. Ganas puntos si los commits fueron realizados en un formato de "Conventional Commits"
6. Ganas puntos si el repositorio tiene readme con la explicación de como correr cada uno de los ejercicios o explicación
7. Proporciona todos los scripts SQL necesarios para la creación de objetos en la base de datos y el script de prueba que demuestre el funcionamiento correcto de cada componente.
   7.1 El paquete debe estar en dos archivos, uno para el header y otro para el body
   7.2 Los script para probar los procedimientos del paquete deben estar en un archivo llamado ScriptsGestionEmpleados.sql con sus debidos comentarios de ser necesarios
