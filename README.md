# Sistema Académico Riwi CodeUp – Introducción (Spring Framework)

Bienvenido al repositorio del **Sistema Académico Riwi CodeUp**, una aplicación profesional para la gestión de estudiantes, cursos y calificaciones, desarrollada con **Spring Framework** siguiendo principios de **arquitectura limpia**, **SOLID** y **DDD (Domain-Driven Design)**.

-----

## Diagramas

### Entidad-Relación
<img width="671" height="541" alt="Entidad-Relacion" src="https://github.com/user-attachments/assets/11dee80a-9ee9-4777-9c29-ddb3ca4288f5" />

### Clases
<img width="671" height="534" alt="Diagrama de clases drawio" src="https://github.com/user-attachments/assets/b1605c66-22d7-4e33-b4ac-ed4344766219" />

### Casos de Usos
| Actor        | Caso de uso                      | Descripción                                           |
| ------------ | -------------------------------- | ----------------------------------------------------- |
| **Users**    | **Login**                        | Autenticarse con correo y contraseña.                 |
|              | **Logout**                       | Cerrar sesión (borrar datos del usuario de la sesión).|
| **Students** | **Registrarse**                  | Crear cuenta de estudiante.                           |
|              | **Ver calificaciones**           | Consultar las notas de los cursos inscritos.          |
|              | **Ver cursos**                   | Listar los cursos donde está matriculado.             |
| **Teachers** | **Agregar notas**                | Asignar calificaciones a los estudiantes de un curso. |
|              | **Ver estudiantes del curso**    | Listar los estudiantes de un curso específico.        |
| **Admin**    | **Agregar teacher**              | Registrar un nuevo profesor.                          |
|              | **Agregar curso**                | Crear un nuevo curso.                                 |
|              | **Eliminar teachers y students** | Eliminar usuarios del sistema.                        |
|              | **Actualizar información**       | Actualizar datos de profesores o estudiantes.         |
|              | **Ver todos los users**          | Obtener la lista completa de usuarios.                |
